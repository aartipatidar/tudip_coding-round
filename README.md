# tudip_coding-round
# 1. if a number is divisible by 13 then print "Foo", if it is divisible by 17 print "Bar" and if it is divisible by 13 and 17 print "Foo Bar".

```
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n;
    cin>>n;
    if(n%13==0 && n%17==0){
        cout<<"Foo Bar";
    }
    else if(n%17==0){
        cout<<"Bar";
    }
    else if(n%13==0){
        cout<<"Foo";
    }
    return 0;
}
```

# 3. find the all the factors of a number

```
#include<bits/stdc++.h>
using namespace std;
int main(){
    int n; 
    cin>>n;  
    int i=1;   
    while(i<=n){        
        if(n%i==0){        
            cout<<i<<" ";   
            i++; 

        }
        else{
            i++;
        }

    }
    return 0;
}
```
