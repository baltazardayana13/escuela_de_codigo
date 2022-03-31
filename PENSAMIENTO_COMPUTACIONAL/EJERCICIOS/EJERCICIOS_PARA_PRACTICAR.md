### ESTOS EJERCICIOS REALIZALOS EN PSEINT PARA QUE PUEDAS PRACTICAR EL PENSAMIENTO COMPUTACIONAL.

Escribe un programa que permita saber si un año es bisiesto.(Para que un año sea bisiesto debe ser divisible por 4 y no debe ser divisible por 100, excepto que también sea divisible por 400.)
Algoritmo añoBis

	Escribir ingresa un año
	Leer anio
  
	
	division1=anio MOD 4 
  
	division2=anio MOD 100 
  
	division3=anio MOD 400
	
				Si division1==0 Entonces
        
					Si division2==0 Entonces
          
						Si division3==0 Entonces
            
							Escribir "El año es bisiesto"
              
						SiNo
            
							Escribir "El año es NO es bisiesto"
              
						Fin Si
            
					SiNo
          
						Escribir "El año es bisiesto"
            
					Fin Si
          
				SiNo
        
					Escribir "El año es NO es bisiesto"
          
				Fin Si

FinAlgoritmo


Escribe un programa que permita al usuario ingresar 6 números enteros, que pueden ser positivos o negativos. Al finalizar, mostrar la sumatoria de los números negativos y el promedio de los positivos.

Escribe un programa que permita al usuario ingresar los montos de las compras de un cliente (se desconoce la cantidad de datos que cargará, la cual puede cambiar en cada ejecución), cortando el ingreso de datos cuando el usuario ingrese el monto 0. Si ingresa un monto negativo, no se debe procesar y se debe pedir que ingrese un nuevo monto.

Hallar Aumento al Sueldo de un empleado; si el sueldo es mayor a $500.000 su aumento será del 12%, pero si su sueldo es menor El aumento será del 15%. 
