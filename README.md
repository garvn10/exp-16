# To study and implement Exception Handling

# Code 1
```
//garv nandwana
//23070123167
#include<iostream>
using namespace std;

int main(){
    float n1, n2, ans;
    cout<<"Enter values of number 1 & 2: ";
    cin>>n1>>n2;
    try{
        if(n2==0){
            throw n2;
        }
        else{
            ans=n1/n2;
            cout<<"Answer = "<<ans<<endl;
        }
    }
    catch(float num){
        cout <<"\nERROR: Division by "<<num<<endl;
    }
}
```
<img width="359" alt="Screenshot 2024-09-13 at 11 44 56 AM" src="https://github.com/user-attachments/assets/a4660f3b-30bf-44ed-b026-8236e1a27e68">

# Code 2
```
//garv nandwana
//23070123167
#include<iostream>
using namespace std;

int main(){
    int age;
    cout<<"Enter age: ";
    cin>>age;
    try{
        if(age<18){
            throw age;
        }
        else{
            cout<<"Age: "<<age<<"\nAPPROVED"<<endl;
        }
    }
    catch(int a){
        cout<<"\nERROR: Underage! ("<<age<<")"<<endl;
    }
}
```
<img width="338" alt="Screenshot 2024-09-13 at 11 46 16 AM" src="https://github.com/user-attachments/assets/13b51f66-ee8f-4905-9b46-4913d4978eae">
