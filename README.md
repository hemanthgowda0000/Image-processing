# Image-processing
Identification of the leaf Using Machine Learning
#include<iostrem.h>
#include<conio.h>
int fact(int);
int gcd(int,int);
void main()
{
  int n,n1,n2;
  clrscr();
  cout<<"enter two number";
  cin>>n;
  cout<<"factorial is:"<<fact(n)<<endl;
  cout<<"enter two numbers to find gcd :";
  cin>>n1>>n2;
  cout<<"gcd is"<<gcd(n1,n2);
  getch();
  }
  int fact(int m)
  {
    if(m==0)
    return(1);
    else
    return(m*fact(m-1));
   }
   int gcd(int n1, int n2)
   {
   if(n2!=0)
   return gcd(n2,n1%n2);
   else 
   return n1;
  }
  
