# Programas-TIC-2

#include<iostream>
#include<stdlib.h> //Rand está en la librería stdlib.h
//Introducir números al azar en una matriz
//Rand devuelve un número pseudoaleatorio entre 0 y RAND_MAX (variable que hay que fijar)

int main(){
  int matrix[3][3];
  int filas;
  int col;
  int num;
  int salir;
  for (filas=0;filas<3;filas++){
    for (col=0;col<3;col++){
      num=rand()%11;
      matrix[filas][col]=num;
      std::cout<<matrix[filas][col] << '\n';
  
      
    
    }
  
  
  }
  std::cin>> salir;
  return 0;



}
