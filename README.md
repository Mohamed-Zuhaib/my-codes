#include<iostream>
using namespace std;
int main(){
 int o;
    int a = 1330;    
    cout<<" we want changes of 1330 in diffrent notes. choose 1 for 100rs  notes, choose 2 for 50rs  notes, choose 3 for 20 rs notes choose 4 for 1 rs notes"<<endl;
    cout<<endl;
    cout<<"enter your choice"<<endl;    
 cin>>o;
 switch(o){
    case 1 : cout<<(a/100)<<endl;
    break;
    case 2 : cout<<(a/50)<<endl;
    break;
    case 3 : cout<<(a/20)<<endl;
    break;
    case 4 :
      cout<<(a/1)<<endl;          
    break;
 default: cout<<"invalid opreation"<<endl;}
 }
