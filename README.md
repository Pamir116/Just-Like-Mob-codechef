# Just-Like-Mob-codechef
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	while(t--)
	{
	    int n,m,k,s,c,p,q,a;
	    cin>>n>>m>>k>>s;
	    c=(n*k)+m;
	    p=s/c;
	    q=s-(p*c);
	    a=(n*(k-1));
	   if(a<q&&q<=c)
	     cout<<"YES"<<endl;
	    else
	     cout<<"NO"<<endl;
	}
	return 0;
}
