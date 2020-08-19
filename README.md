#include<upstream>
Using namespace std;
int main()
{
   int n,d;
   Cin>>n;
   Cin>>d;
   int *a=new int[n];
   for(int i=0;i<n;i++)
   Cin>>a[(i+n-d)%n];
    for(int i=0;i<n;i++)
     Cout<<a[i]<<" ";

       return 0;
}
