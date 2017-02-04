#include<bits/stdc++.h>
using namespace std;
typedef long long ll;
int main()
{
    ll a,b;
    cin>>a>>b;
    ll sum=0;
    for(ll i=0;i<63;i++){
        for(ll j=0;j<i;j++){// j==i gives 31 and 15 which is 0111 so equal not included

            ll d=(2LL<<i)-(1LL<<j)-1;//
            if(d>=a&&d<=b)
            {
                sum++;
            }
        }
    }
    cout<<sum<<endl;
    return 0;
}
