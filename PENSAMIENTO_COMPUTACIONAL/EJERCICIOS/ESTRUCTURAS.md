# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo

Algoritmo Numero_posoneg
	
	
	Escribir "Por favor escriba un número"
	
	Leer num
	
	Si num>0 Entonces
		
		Escribir "El numero " num " es positivo"
		
	SiNo
		
		Escribir "El número " num " es negativo"
		
	Fin Si
	
FinAlgoritmo

* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

Algoritmo caracter_sn
	
	Definir letra Como Caracter
	
	Repetir
  
		Escribir "caracter invalido"
    
		Leer letra
    
	Hasta Que letra="s" O letra="n"
		
	
FinAlgoritmo



* Un programa que pida una letra y detecte si es una vocal. 



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


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

Algoritmo numerorordenados

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
* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
Algoritmo Mes_numero
	
	Escribir "Por favor, introduzca un número del 1 al 12",num
	
	Leer num
	
	Segun num Hacer
		
		1:
			
			Escribir "El numero  ",num," corresponde al mes de enero"
			
		2:
			
			Escribir "El numero  ",num," corresponde al mes de febrero"
			
		3:
			
			Escribir "El numero  ",num," corresponde al mes de marzo"
			
		4:
			
			Escribir "El numero  ",num," corresponde al mes de abril"
			
		5:
			
			Escribir "El numero  ",num, " corresponde al mes de mayo"
			
		6:
			
			Escribir "El numero  ",num, " corresponde al mes de junio"
			
		7:
			
			Escribir "El numero  ",num, " corresponde al mes de julio"
			
		8:
			
			Escribir "El numero  ",num, " corresponde al mes de agosto"
			
		9: 
			
			Escribir "El numero  ",num, " corresponde al mes de septiembre"
			
		10:
			
			Escribir "El numero  ",num, " corresponde al mes de octubre"
			
		11:
			
			Escribir "El numero  ",num, " corresponde al mes de noviembre"
			
		12: 
			
			Escribir "El numero  ",num, " corresponde al mes de diciembre"
			
		De Otro Modo:
			
			Escribir "Por favor verifica tu entrada"
			
	Fin Segun
    
FinAlgoritmo


* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

Algoritmo votacion
	Escribir "Bienvenido a la votacion, los candidatos son:"
  
	Escribir "candidato A por el partido rojo"
  
	Escribir "candidato B por el partido verde"
  
	Escribir "candidato C por el partido azul"
	
	Leer voto
  
	Segun voto	 Hacer
  
		"A" o "a":
			Escribir "Usted ha votado por el partido rojo"
      
		"B" o "b":
    
			Escribir "Usted ha votado por el partido verde"
      
		"C" o "c":
    
			Escribir "Usted ha votado por el partido azul"
      
		De Otro Modo:
    
			Escribir "Por favor ingrese una opcion valida"
      
	Fin Segun
	
FinAlgoritmo

* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.




Algoritmo votacion

	correo="baltazardayana13@gmail.com"
  
	contraseña="dayana1234"
  
	Escribir "Bienvenido por favor ingrese su correo"
  
	Leer correo_escrito
  
	Escribir "Por favor ingrese su contraseña"
  
	Leer cont_escrita
  
	Si correo_escrito==correo Y cont_escrita==contraseña Entonces
  
		Escribir "Bienvenido"
    
	SiNo
  
		Escribir "Lo siento, solicitud invalida por favor revisa tu correo o contraseña"
    
	Fin Si
  
FinAlgoritmo

