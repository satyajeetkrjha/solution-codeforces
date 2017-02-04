#include <bits/stdc++.h>

using namespace std;

int main()
{
   string s;
   cin>>s;
   int len=s.length();
   int evencount=0;
   int indexofeven=-1;
   for(int i=0;i<s.length();i++){//527
    if((s[i]-'0')%2==0){
        evencount ++;//1
        if((s[i]-'0')<(s[len-1]-'0')){
        //if((s[i]-'0')<(s([s.length()-1]-'0')){
           swap(s[i],s[len-1]);// swap 2 and 7
           cout<<s<<endl;
           return 0;
        }
    indexofeven=i;
   }
   }
   if(evencount ==0)
    cout<<-1<<endl;
    else{
        swap (s[indexofeven],s[len-1]);
        cout<<s<<endl;
    }
 return 0;
   }
