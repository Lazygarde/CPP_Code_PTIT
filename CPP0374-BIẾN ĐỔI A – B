#include <bits/stdc++.h>
using namespace std;
int main(){
    string s;
    cin>>s;
    vector <string> a;
    int c=0,d=0,ss=0,k=0;
    while(c<s.size()){
        while(s[d]==s[d+1]){
            d++;
            if(d==s.size()) break;
        }
        a.push_back(s.substr(c,d+1-c));
        c=++d;
    }
    for(int i=a.size()-1;i>=0;i--){
        if((a[i][0]=='A'&&k%2==0)||(a[i][0]=='B'&&k%2==1)) continue;
        if(a[i].size()==1) ss++;
        else{
            ss++;
            k++;
        }
    }
    cout<<ss;
}
