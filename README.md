# -Quiz06-q1.cpp

#include <iostream>

using namespace std;

//Recive valores en parametros y da valor o algo

long superpower (long a, long b){

    if(b==0){
    
    return 1;//
    
    }
    else{
    
    return a*superpower(a, b-1);
    
    }
}

int main(){

   long z;
   
   z = superpower(3,0);
   
   cout << z << endl;
   
}
