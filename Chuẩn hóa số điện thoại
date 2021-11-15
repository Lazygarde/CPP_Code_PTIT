#include <bits/stdc++.h>
using namespace std;
int main(){
    int t;
    cin>>t;
    cin.ignore();
    while(t--){
	    string s;
	    regex rex("[\\D]");
        getline(cin, s);
        if(s[0]=='+'&&s[1]=='8'&&s[2]=='4'){
            s[0]=s[1]=' ';
            s[2]='0';
        }
        else if(s[0]=='8'&&s[1]=='4'){
            s[0]=' ';
            s[1]='0';
        }
        s=regex_replace(s,rex,"");
        cout<<s<<endl;
    }
}
