#include<bits/stdc++.h>
#include<string.h>
#define ll long long int
#define br <<"\n";
#define For(i,n) for(int i=0;i<n;i++)
#define Forran(i,n,a) for(int i=n;i<a;i++)
#define Forrev(i,n) for(int i = n-1; i >= 0; i--)
#define fastio ios_base::sync_with_stdio(0); cin.tie(0); cout.tie(0);
using namespace std;
int main()
{
    fastio
    int t,i,n,a,sum;
    cin>>t;
    vector<int>v;
    while(t--)
    {
        v.clear();
        sum=1;
        cin>>n;
        For(i,n){
            cin>>a;
            v.push_back(a);
        }
        sort(v.begin(),v.end());
        v[0]++;
        For(i,n){
            sum*=v[i];
        }
        cout<<sum br;
    }
    return 0;
}
