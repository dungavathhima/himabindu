#include<iostream> 
using namespace std;
int main(){
int array[100],num,i;
cout<<"Enter number of  elements ";
cin>>num;
cout<<"\n Enter"<<num<<"elements of array";
cout<<"\n";
for(i=0;i<num;i++){
cin>>array[i];
}
cout<<"You entered elements are:";
for(i=0;i<num;i++){
cout<<*(array+i)<<"  ";
cout<<"\n";
}
return 0;
}
