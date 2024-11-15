#include <iostream>

using namespace std;

int main()
{
    float R1, R2, R3, RT;

    cout << "INGRESE EL VALOR DE LA RESISTENCIA 1" << endl;
    cin>> R1;
    if (R1==0){
    cout<< "EL VALOR INGRESADO ES INCORRECTO"<<endl;
    return 0;
    }


    cout << "INGRESE EL VALOR DE LA RESISTENCIA 2" << endl;
    cin>> R2;
    if (R2==0 ){
    cout<< "EL VALOR INGRESADO ES INCORRECTO"<<endl;
    return 0;
    }

    cout << "INGRESE EL VALOR DE LA RESISTENCIA 3" << endl;
    cin>> R3;

    if (R3==0){
    cout<< "EL VALOR INGRESADO ES INCORRECTO"<<endl;
    }
    else
    RT= 1/(1/R1+1/R2+1/R3);
    cout<<"SU VALOR DE LA RESISTENCIA TOTAL ES: "<<RT<<endl;

    return 0;
}
