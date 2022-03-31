
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

Algoritmo MiPrimerAlgoritmo

	Escribir "Ingresa un numero"
  
	Leer numero
  
	multiplicacion=numero*9
  
	Escribir numero, " multiplicado por 9 es ", multiplicacion
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101912013/160259892-6b0934e6-97f6-4c53-9f2e-fa011cf86599.png)

2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 
![image](https://user-images.githubusercontent.com/101912013/160260544-a7c3aabd-d835-41c9-a405-bed226d094a7.png)



3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo MiPrimerAlgoritmo

	i=0
  
	Mientras i<4 Hacer
  
		i=i+1
    
		Escribir "ingresa la calificacion", i
    
		Leer num
    
		suma=suma + num
		
	Fin Mientras
  
	promedio=suma/4
  
	Escribir "el promedio es ",promedio
  
	
	Si promedio>=6 Entonces
  
		Escribir "Felicidades aprobaste"
    
	SiNo
  
		Escribir "Lo siento no aprobaste"
    
	Fin Si
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101912013/160260736-e4373d93-f842-4735-811c-ff57866c2a95.png)


4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo MiPrimerAlgoritmo

	Escribir "ingresa un numero"
  
	Leer num
	
	residuo = num MOD 2
	
	
	Si residuo=0 Entonces
  
		Escribir "el numero es par"
    
	SiNo
  
		Escribir "El numero es impar"
    
	Fin Si
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101912013/160260917-a05e9670-4b0c-4ccf-b9fd-bf4ba4a51bf8.png)


5. Un programa que pida una letra y detecte si es una vocal.

Algoritmo MiPrimerAlgoritmo

	Escribir "escribe una letra"
  
	Leer letra
	
	Segun letra Hacer
  
		"a" O "A":
    
			Escribir "Es una vocal"
      
		"e"O "E":
    
			Escribir "Es una vocal"
      
		"i"O "I":
    
			Escribir "Es una vocal"
      
		"o"O "O":
    
			Escribir "Es una vocal"
      
		"u"O "U":
    
			Escribir "Es una vocal"
			
		De Otro Modo:
    
			Escribir "No es una vocal"
      
	Fin Segun
	
	
FinAlgoritmo

6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.


Algoritmo MiPrimerAlgoritmo
	
		Escribir "ingrese el primer numero"
		
		Leer a
		
		Escribir "ingrese el segundo numero"
		
		Leer b
		
		Escribir "ingrese el tercer numero"
		
		Leer c
	
		
		Si a<b Entonces
			Si a<c Entonces
				Si b<c Entonces
					Escribir "Los valores ordenados de menor a mayor son",a , b, c
				SiNo
					Escribir "Los valores ordenados de menor a mayor son",a , c, b
				Fin Si
			SiNo
				Escribir "Los valores ordenados de menor a mayor son",c , a, b
			Fin Si
		SiNo
			Si a<c Entonces
				Escribir "Los valores ordenados de menor a mayor son",b,a,c
			SiNo
				Si c<b Entonces
					Escribir "Los valores ordenados de menor a mayor son",c,b,a
				SiNo
					Escribir "Los valores ordenados de menor a mayor son",b,c,a
				Fin Si
			Fin Si
		Fin Si

		
		
FinAlgoritmo


7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.


Algoritmo Repetir_nombre

	Definir nombre Como Caracter;
	
	Definir numero_derep Como Entero;
	
	Escribir "Ingrese un nombre"
	
	Leer nombre
	
	Escribir "Ingrese el numero de repeticiones"
	
	Leer repeticiones
	
	numero_derep=1
	
	Mientras numero_derep<=repeticiones Hacer
	
		Escribir nombre," "
		
		numero_derep=numero_derep+1
		
	FinMientras
	
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101912013/160952902-cd7a728e-6aeb-40e0-9080-440635d45eef.png)



8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.


Algoritmo MiPrimerAlgoritmo
	
	i=0

	Repetir
		
		i=i+1
		
		Escribir "ingresa un numero", i
		
		Leer num
		
		Si num>= 0 Entonces
		
			suma=suma + num
			
		SiNo
		
			suma=suma
			
		Fin Si
		
		
	Hasta Que num<= 0
	
	Escribir suma

FinAlgoritmo


![image](https://user-images.githubusercontent.com/101912013/160954120-c0330732-ea3a-485d-9fc0-0339800c15ad.png)



