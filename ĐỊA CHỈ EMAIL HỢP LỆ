#include <bits/stdc++.h>
using namespace std;

bool check(string s)
{
    bool flag = 0;
    int dem = 0,i,ch=0;
    for (int i = 0; i < s.length(); i++)
    {
        if (!isalnum(s[i]) && !isalpha(s[i]) && s[i] != '.' && s[i] != '_' && s[i] != '@')
        {
            return 0;
        }
        if (s[i] == '@')
            dem++;
        if (dem > 1)
            return 0;
    }
    for (i = 0; s[i] != '@'; i++)
    {
        if (isalpha(s[i]) && isalnum(s[i]))
            ch = 1;
        if (i > 64)
            return 0;
    }
    if (ch == 0)
        return 0;
    dem = 0;
    for (int j = i + 1; j < s.length(); j++)
    {
        if (s[j] == '.')
            flag = 1;
        dem++;
        if (dem > 254)
            return 0;
    }
    if (flag == 0)
        return 0;
    if (s[s.length() - 1] == '.')
        return 0;
    return 1;
}

int main()
{
    int t;
    cin >> t;
    scanf("\n");
    while (t--)
    {
        string s;
        getline(cin, s);
        if (check(s))
            cout << "YES";
        else
            cout << "NO";
        cout << endl;
    }
}
