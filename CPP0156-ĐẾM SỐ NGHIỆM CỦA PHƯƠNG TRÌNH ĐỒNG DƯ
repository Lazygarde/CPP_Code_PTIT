#include <stdio.h>
int main(){
	int t;
	scanf("%d",&t);
	while(t--){
		long long b,p,s=0;
		scanf("%lld%lld",&b,&p);
	    for(long long i=1;i<p;i++){ 
	        if((i*i)%p==1){
	            long long k=i+p*(b/p); 
	            if(k>b) k-=p; 
	            s+=(k-i)/p+1; 
	        } 
	    }
	    printf("%lld\n",s);
	}
}
