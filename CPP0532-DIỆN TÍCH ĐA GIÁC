#include<bits/stdc++.h>
using namespace std;
struct data{
	double x;
	double y;
};
double ss(data a,data b,data c){
	return 0.5*abs((b.x-a.x)*(c.y-a.y)-(c.x-a.x)*(b.y-a.y));
}
int main(){
	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
		double s=0;
		struct data a[n];
		for(int i=0;i<n;i++) cin>>a[i].x>>a[i].y;
		for(int i=1;i<=n-2;i++){
			s+=ss(a[0],a[i],a[i+1]);
		}
		printf("%.3lf\n",s);
	}
}
