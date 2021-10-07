#include <bits/stdc++.h>
using namespace std;
int n,s,k,a[25][25];
void Do(int x,int y,int ss){
    if(x==n-1&&y==n-1&&ss==k){
        s++;
        return;
    }
    if(x<n-1&&ss+a[x+1][y]<=k) Do(x+1,y,ss+a[x+1][y]);
    if(y<n-1&&ss+a[x][y+1]<=k) Do(x,y+1,ss+a[x][y+1]);
}
int main(){
    int t;
    cin>>t;
    while(t--){
        s=0;
        cin>>n>>k;
        for(int i=0;i<n;i++){
            for(int j=0;j<n;j++){
                cin>>a[i][j];
            }
        }
        Do(0,0,a[0][0]);
        cout<<s<<endl;
    }
}
