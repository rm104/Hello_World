/* Z(N) function, trailing zeroes. */
#include <bits/stdc++.h>
using namespace std;
 
int main(){
int n,k,t,c;
cin>>t;
   for(int i=0;i<t;i++){
   	cin>>n;
   	c=0;
   	k=5;
   	while(k<=n){   
   	c+=n/k;
   	k=k*5;
   	}
  cout<<c<<endl;
   }
   return 0;
} 
