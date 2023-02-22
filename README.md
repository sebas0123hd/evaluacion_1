# evaluacion_1
Aplicación de citas
@date<22-02-2023>
@author<Ramos Espinoza Martin Sebastian>
@version<1.0>

  #include <stdio.h>
  

int main(){
  
  //@name<Nombres de las variables> //
  
    int sm, p1, p2, p3, p4, p5, p6, p7, p8, p9, p10;
  
    //Son variables de tipo entero//
  
    char opc1, opc2, opc3, opc4, opc5, opc6, opc7, opc8, opc9, opc10;
  
    printf("Bienvenido o bienvenida a Compatibilidad o Aburrimiento");
  
     printf("\nContesta las siguientes preguntas para saber si te arriesgas con esta relacion o no");
     
      printf("\n1.-¿Es celoso o celosa? \na)Si \nb)No \n");
        scanf(" %c ",&opc1);
        
        if(opc1 == 'a') { 
            p1=3;
        }
        else if(opc1 == 'b') {
            p1=10;
        }
        
        
        printf("\n2.-¿Ha tenido pareja anteriormente? \na)Si \nb)No \n");
        scanf(" %c",&opc2);
        
        if(opc2 == 'a') { 
            p2=10;
        }
        else if(opc2 == 'b') {
            p2=5;
        }
        
        
        printf("\n3.-¿Quiere tener hijos? \na)Si \nb)No \n");
        scanf(" %c",&opc3);
        
        if(opc3 == 'a') { 
            p3=10;
        }
        else if(opc3 == 'b') {
            p3=5;
        }
        
        printf("\n4.-¿Se viste de acuerdo a la ocasion? \na)Si \nb)No \n");
        scanf(" %c",&opc4);
        
        if(opc4 == 'a') { 
            p4=10;
        }
        else if(opc4 == 'b') {
            p4=5;
        }
        
        
        printf("\n5.-¿Se preocupa en no romperte el corazon? \na)Si \nb)No \n");
        scanf(" %c",&opc5);
        
        if(opc5 == 'a') { 
            p5=10;
        }
        else if(opc5 == 'b') {
            p5=0;
        }
        
        
        printf("\n6.-¿Ayuda con los labores del hogar? \na)Si \nb)No \n");
        scanf(" %c",&opc6);
        
        if(opc6 == 'a') { 
            p6=10;
        }
        else if(opc6 == 'b') {
            p6=5;
        }
        
        
        printf("\n7.-¿Habla mucho de su ex? \na)Si \nb)No \n");
        scanf(" %c",&opc7);
        
        if(opc7 == 'a') { 
            p7=0;
        }
        else if(opc7 == 'b') {
            p7=10;
        }
        
        
        printf("\n8.-¿Limita tus amistades? \na)Si \nb)No \n");
        scanf(" %c",&opc8);
        
        if(opc8 == 'a') { 
            p8=0;
        }
        else if(opc8 == 'b') {
            p8=10;
        }
        
        
        printf("\n9.-¿Tiene malas amistades? \na)Si \nb)No \n");
        scanf(" %c",&opc9);
        
        if(opc9 == 'a') { 
            p9=0;
        }
        else if(opc9 == 'b') {
            p9=10;
        }
        
        
        printf("\n10.-¿Con quien prefiere pasar el domingo? \na)Amigos \nb)Familia \nc)Solo \n");
        scanf(" %c",&opc10);
        
        if(opc10 == 'a') { 
            p10=8;
        }
        else if(opc10 == 'b') {
            p10=10;
        }
        else if(opc10 == 'c') {
            p10=4;
        }
        
        //@param<Es una suma de valores tipo entero>//
        sm = p1+p2+p3+p4+p5+p6+p7+p8+p9+p10;
        
      if(sm>70){
          printf("\nEl resultado es: %i", sm);
          printf("\nSi se puede, no hay peligro XD");
      }
      else{
          printf("\nEl resultado es: %i", sm);
          printf("\nEscapa de ahi Esponja :V");
      }
        return 0;
    //@return<Regresa valores de tipo entero>//
}
    
