#include <bits/stdc++.h>
using namespace std;
bool cmp1(pair <int,int> a,pair <int,int> b){
    if(a.second==b.second) return a.first>b.first;
    return a.second>b.second;
}
bool cmp2(pair <int,int> a,pair <int,int> b){
    return a.first>b.first;
}
int main(){
    int t;
    cin>>t;
    while(t--){
        string a;
        cin>>a;
        int b[10]={0};
        vector <pair <int,int> > a1,a2;
        for(int i=0;i<a.size();i++) b[a[i]-'0']++;
        for(int i=0;i<10;i++){
            if(b[i]%2==1) a1.push_back(make_pair(i,b[i]));
            else if(b[i]!=0) a2.push_back(make_pair(i,b[i]));
        }
        sort(a1.begin(),a1.end(),cmp1);
        sort(a2.begin(),a2.end(),cmp2);
        if(b[0]%2==1){
            for(int i=0;i<a2.size();i++){
                for(int j=0;j<a2[i].second/2;j++) cout<<a2[i].first;
            }
            if(a2.size()==0){
                if(a1.size()==1) for(int i=0;i<b[0];i++) cout<<0;
                else for(int i=0;i<a1[1].second;i++) cout<<a1[1].first;
            }
            else{
                if(b[0]>a1[0].second) for(int i=0;i<b[0];i++) cout<<0;
                else for(int i=0;i<a1[0].second;i++) cout<<a1[0].first;
            }
            for(int i=a2.size()-1;i>=0;i--){
                for(int j=0;j<a2[i].second/2;j++) cout<<a2[i].first;
            }
        }
        else{
	        if(a2.size()>0&&a2[0].first!=0){
	            for(int i=0;i<a2.size();i++){
	                for(int j=0;j<a2[i].second/2;j++) cout<<a2[i].first;
	            }
			    }
          for(int i=0;i<a1[0].second;i++) cout<<a1[0].first;
          if(a2.size()>0&&a2[0].first!=0){
	            for(int i=a2.size()-1;i>=0;i--){
	                for(int j=0;j<a2[i].second/2;j++) cout<<a2[i].first;
	            }
			    }
        }
        cout<<endl;
    }
}
