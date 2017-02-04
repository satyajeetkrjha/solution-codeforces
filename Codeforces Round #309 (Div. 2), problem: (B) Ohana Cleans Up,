#include <iostream>
#include <bits/stdc++.h>
using namespace std;
vector <string>v;
int main()
{
    int n;
    cin>>n;
    int c;
    for(int i=0;i<n;i++){
            string s;
            cin>>s;
        v.push_back(s);
    }
    int res=-100;
    for(int i=0;i<n;i++){
            c=0;
        for(int j=0;j<n;j++){
            if(v[i]==v[j])
                c++;
        }
        res=max(res,c);
    }
    cout<<res<<endl;



    return 0;
}
