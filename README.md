/*escribe la esxpresion matematica como en expresion e c++ a+b / a+b
*/

#include <iostream>

using namespace std;

int main(){
	float a = 0, b = 0, c = 0, d = 0, resultado = 0;
	
	cout<<"introduce el valor de a:"; cin>>a;
	cout<<"introduce el valor de b:"; cin>>b;

    cout<<"introduce el valor de c:"; cin>>c;
	cout<<"introduce el valor de d:"; cin>>d;
	
	resultado = (a+b) / (c+d);
	cout<<"\nel resultados es:"<<resultado<<endl;
	
	
	
	return 0;
}
