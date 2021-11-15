#include <bits/stdc++.h>
using namespace std;
int main(){
    map <string,long long> Res;
    string tmp, type, num, check, time;
    int n;
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        cin >> tmp;
        cin >> type >> num >> check >> time;
        if (check == "IN")
        {
            if (type == "Xe_con" && num == "5")
                Res[time] += 10000;
            else if (type == "Xe_con" && num == "7")
                Res[time] += 15000;
            else if (type == "Xe_tai" && num == "2")
                Res[time] += 20000;
            else if (type == "Xe_khach" && num == "29")
                Res[time] += 50000;
            else if (type == "Xe_khach" && num == "45")
                Res[time] += 70000;
        }
    }

    for (auto it : Res)
    {
        cout << it.first << ": " << it.second << endl;
    }
}
