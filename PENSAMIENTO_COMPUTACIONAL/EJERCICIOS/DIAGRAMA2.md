## RETO
1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
Algoritmo mayorr

	Escribir "Ingrese un numero "
  
	Leer num1
  
	Escribir "Ingrese otro numero "
  
	Leer num2
  
	Si num1 <= num2 Entonces
  
		Escribir num2, " Es mayor que ", num1
    
	SiNo
  
		Escribir num1, " Es mayor que ", num1
    
	Fin Si
  
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101912013/160969357-f592105d-c718-4e4c-a386-a10860171046.png)

2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

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

![image](https://user-images.githubusercontent.com/101912013/160970811-c7a66b28-70a5-4799-87b4-2eba3cd18dbc.png)


3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo ParOimpar

Escribir "ingresa un numero"

Leer num

residuo = num MOD 2


Si residuo=0 Entonces
	
	Escribir "el numero es par"
	
SiNo
	
	Escribir "El numero es impar"
	
Fin Si

FinAlgoritmo

