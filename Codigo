#include<iostream>
#include<conio.h>
#include<stdio.h>
#include<string.h>
#include<windows.h>

using namespace std;

int main()
{
    char texto[50];
    int a=1,b,aux;
    cout<<"Indique el texto a codificar"<<endl;
    gets(texto);
    b=strlen(texto);
    for(int i=0;i<b;i++)
    {
      aux=texto[i];
      if(aux+a>122)
      {
         aux=((aux+a)-122)+96;
      }
      else
      {
          aux=aux+3;
      }
      if(texto[i]!=' ')
      {
         texto[i]=aux;
      }
    }
    cout<<"Texto codificado a: "<<texto<<endl;
   system("pause");
}
