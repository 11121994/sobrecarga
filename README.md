
#include<iostream>
using namespace std;


int operador(int a,int b)

{

	return (a*b);
}


double operador (double a, double b)

{
	return (a/b);
}

int main()

{

	int x=5,y=2;
	
	double n=5.0,m=2.0;
	
	cout<<operador(x,y)<<'\n';
	
	cout<< operador (n,m) <<'\n';
	
	return 0;
	
}
