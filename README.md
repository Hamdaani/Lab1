#include <iostream>

using namespace std;

// declaration of fcts

int min(int , int);
int max(int , int);
double average(double , double);
int abst(int);

int main(){
    
    int a;
    cout<< "First number? "<< endl;
    cin>> a;
    
    
    int b;
    cout<< "Second number? "<< endl;
    cin>> b;
    
    max( a , b);
    min(a , b);
    average(a , b);
    abst(b);
    abst(a);
    
    return 0;
}

int max(int x , int y){
    if(x<y){
        cout<<"The maximun of "<< x << " "<< "and" <<" " << y << " is" << " "<< y <<endl;
    }
    else
        cout<<"The maximun of "<< x << " "<< "and" <<" " << y << " is" << " "<< x <<endl;
    return x;
    
}

int min(int x , int y){
    if(x<y){
        cout<<"The minimum of "<< x << " "<< "and" <<" " << y << " is" << " "<< x <<endl;
    }
    else
        cout<<"The minimum of "<< x << " "<< "and" <<" " << y << " is" << " "<< y <<endl;
    return x;
    
}

double average(double x , double y){
    
    double avg;
    avg = (x+y)/2.;
    
    cout<<"The average of "<< x << " "<< "and" <<" " << y << " is" << " "<< avg <<endl;
    
    return avg;
}

int abst(int x){
    int absolut;
    absolut = abs(x);
    
    cout<<"The absolute value of "<< x << " "<< absolut << endl;
    return absolut;
    
}
