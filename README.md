# Operators-and-For-loop

Bitwise operators===>
#include <iostream>

using namespace std;

int main()
{
    int a=-2;
    cout<<(a>>1);
    return 0;
}
  
 
  Conditionals and for loops==>
  #include <iostream>

using namespace std;
void isPrime(int n){
    bool prime=true;
    for(int i=1;i<n;i++){
        if(n%i==0){
            prime=false;
        }
    }
    if(prime){
        cout<<n<<endl;
    }

}

int main()
{
   //Write a program to check whether a number is prime or not using for loops:
/*   int n;
   cout<<"Type in the number you want to check as prime"<<endl;
   cin>>n;
   bool isPrime=true;
   for(int i=2;i<n;i++){
    if(n%i==0){
        isPrime=false;
        break;
    }
   }
   if(isPrime){
    cout<<"Prime"<<endl;
   }
   else{
    cout<<"Not a Prime"<<endl;
   }

   //Break and continue statement,
   //Using break and continue, change the code of square pattern into triangular stairs pattern
   int m;
   cout<<"Type in the value of the length of side of square"<<endl;
   cin>>m;
   int i=1;
   while(i<=m){
        int j=1;
        while(j<=m){
            cout<<j;
            j++;
            if(j>i){
                break;
            }
        }
        cout<<endl;
        i++;
   }
                */
/*    int i=1;
    while(i<5){
        if(i==3){
            continue;
        }
        cout<<i<<" ";
        i++;
    }  */
    cout<<"Enter the number greater than 2 and less than desired N. I will print all the prime numbers between it."<<endl;
    int n;
    cin>>n;
    for(int i=2;i<n;i++){
        isPrime(i);
    }



    return 0;
}

                          
                          
