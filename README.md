#include<iosteam> 


 
float ,imc, peso, altura, idade ; 
char usuario; 
count <- 0 

void main () 
{
 imc <- peso / ((altura /100 ) * (altura /100 )) 
  // linguagem c++ para calcular o peso de um usuario  
  Cout <<" escreva o nome do usuario, "<< endl ; 
    sin >> " usuario é  "  usuario  , << endl ;  
  Cout << " informe o peso :  "<< endl ; 
    sin >> " ", peso << endl;
  Cout << " informe a altura do usuario " , altura << endl; 
   sin >>" " , altura << endl;    
    If ( imc < 19 ) 
         cout << " você precisa se alimentar melhor " ;   
             else if ( imc < 24.90 )    
                      cout << " você está se alimentando melhor"; 
                            else if ( imc < 29.90) 
                                      cout << " sobre peso" ; 
                                           else if ( imc < 34.90) 
                                                    cout << " obesidade grau 1" ; 
                                                          else if ( imc < 39.9 ) 
                                                                    cout << " obesidade grau 2 " ; 
                                                                   else  
                                                                      cout << " você está com obesidade morbida" ; 
  
    
   return 0; 
   system (" pause") ; 
}
