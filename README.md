#include <iostream>
using namespace std;

int mayor (int a, int b,int c) {
    int max=a;
    if (a >= b && a >= c) {
    return a;
    }
    else if (b >= a && b >= c) {
    return b;
    }
    else
    return c;
    
}


int main () {   
    int a, b, c;
    cout << "Ingrese el primer numero: ";
    cin >> a;
    cout << "Ingrese el segundo numero: ";
    cin >> b;
    cout << "Ingrese el tercer numero: ";
    cin >> c;
    cout << "El mayor es: " << mayor(a, b, c) << endl;
 
    return 0;
}