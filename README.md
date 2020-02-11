# Admin-Proy-Homework

Este repositorio es para realizar las tareas de la materia de Administración de Proyectos. 

#include<stdio.h>
#include<math.h>
 
int main(int argc, char** args){
   float a, b, c, disc, x1, x2, xi, xr;
   printf("\n\t\tSolucion de una ecuacion de segundo grado");
   printf("\n\t\t_________________________________________\n\n\n");
   printf("\t\t\tEscribe el valor de a --> ");
   scanf("%f", &a);
   while(a==0){
   printf("\t\tEl valor de a no puede ser 0 ingrese el valor de nuevo -->");
   scanf("%f", &a);
   }
   printf("\t\t\tEscribe el valor de b --> ");
   scanf("%f", &b);
   printf("\t\t\tEscribe el valor de c --> ");
   scanf("%f", &c);
