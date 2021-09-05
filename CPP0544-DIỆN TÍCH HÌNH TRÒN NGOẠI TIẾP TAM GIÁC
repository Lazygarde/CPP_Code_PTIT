#include<bits/stdc++.h>
using namespace std;
int main(){
	int t;
	cin>>t;
	while(t--){
		double x1,y1,x2,y2,x3,y3;
		cin>>x1>>y1>>x2>>y2>>x3>>y3;
		double a=sqrt((x2-x1)*(x2-x1)+(y2-y1)*(y2-y1));
		double b=sqrt((x2-x3)*(x2-x3)+(y2-y3)*(y2-y3));
		double c=sqrt((x1-x3)*(x1-x3)+(y1-y3)*(y1-y3));
		if(a+b<=c||b+c<=a||a+c<=b) cout<<"INVALID"<<endl;
		else{
			double k=sqrt((a+b+c)*(a+b-c)*(-a+b+c)*(a-b+c))/4;
			k=(a*b*c)/(4*k);
			k*=3.141592653589793238*k;
			printf("%.3lf\n",k);
		}
	}
}
