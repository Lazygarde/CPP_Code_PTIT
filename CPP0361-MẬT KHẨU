#include <stdio.h>
#include <string.h>
char a[100005][15];
struct data{
	char s[15];
	int ss;
};
void qsort(int l,int r){
	int i=l,j=r;
	char k[15];
	strcpy(k,a[(l+r)/2]);
	while(i<=j){
		while(strcmp(a[i],k)<0) i++;
		while(strcmp(a[j],k)>0) j--;
		if(i<=j){
			char c[15];
			strcpy(c,a[i]);
			strcpy(a[i],a[j]);
			strcpy(a[j],c);
			i++;
			j--;
		}
	}
	if(l<j) qsort(l,j);
	if(i<r) qsort(i,r);
}
int main(){
	int n,j=0,xx=0,sss=0;
	scanf("%d\n",&n);
	for(int i=0;i<n;i++) scanf("%s",a[i]);
	qsort(0,n-1);
	struct data b[n];
	while(j<n){
		int i=j+1;
		strcpy(b[xx].s,a[j]);
		b[xx].ss=1;
		while(strcmp(a[i],a[j])==0){
			b[xx].ss++;
			i++;
			if(i==n) break;
		}
		j=i;
		xx++;
	}
	for(int i=0;i<xx;i++) sss+=b[i].ss*(b[i].ss-1);
	for(int i=0;i<xx-1;i++){
		for(int x=i+1;x<xx;x++){
			if(strstr(b[x].s,b[i].s)) sss+=b[i].ss*b[x].ss;
			if(strstr(b[i].s,b[x].s)) sss+=b[x].ss*b[i].ss;
		}
	}
	printf("%d",sss);
}
