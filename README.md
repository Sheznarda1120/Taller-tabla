# Taller-tabla
Tabla de multiplicar
#include <iostream.h>
main()
{int x=0,y,a,n;
 cout<<"\n Tabla de multiplicar";
 cout<<"\n Ingrese un numero del 1 al 9:";
 cin>>y;
do{a=x*y;
   cout<<"\n Ingrese el resultado de"<<x<<"*"<<y<<"=";
   cin>>n;
   if(n==a)
   cout<<"\n CORRECTO";
   else
   cout<<"\n ERROR";
   x++;
  }while(x<10);
  return 0;
}
