#include <bits/stdc++.h>
using namespace std;
int main(){
    int n,x;
    stack <int> st;
    cin>>n>>x;
    st.push(x);
    n--;
    while(n--){
        cin>>x;
        if(!st.empty()&&(x+st.top())%2==0) st.pop();
        else st.push(x);
    }
    cout<<st.size();
}
