# Reto-3-codigitoeyprimo
## ¡ HOLA ! 
### En este repositorio se plantea un pseudocodigo para saber los números primos menores a un número determinado "x" y tambien se recrea en un diagrama de flujo.
#### Para saber si un número es primo, este debe ser divisible unicamente por si mismo y por 1.
#### Aqui presento el pseudocodigo 


   
   ALGORITMO DE NUMEROS PRIMOS
	
     Algoritmo primos
		// Solicitar el número límite
		Escribir "Ingrese un número para hallar los primos antes de el:"
		Leer x
		
		Si x < 2 Entonces
			Escribir "No se pueden hallar numeros menores que 2"
		FinSi
		si x >= 2 Entonces
			Escribir "Números primos en la lista del 1 al ", x, ":"
			Escribir 2
		FinSi	
		// Verificar cada número de 2 a x
		Para i <- 2 Hasta x Hacer// ciclo que recorre los numeros 
			esPrimo <- Verdadero
			
			// Verificar si i es divisible por algún número entre 2 y raíz(i)
			// La raiz esta relacionada con la criba de erastotenes
			Para j <- 2 Hasta raiz(i) Hacer // recorre los divisores
				Si i Mod j = 0 Entonces    // Mod significa residuo,si es cero no es primo
					esPrimo <- Falso
					j <- raiz(i) // Salir del bucle
				Fin Si
			Fin Para
			
			// Si es primo, mostrarlo
			Si esPrimo Entonces
				Escribir i
			Fin Si
		Fin Para
    FinAlgoritmo

 ![Captura de pantalla 2024-11-24 213116](https://github.com/user-attachments/assets/3f78198e-c070-481b-9b0d-4611c30242ce) 

 #### Es mucho mas practico en Pseint ya que incluye el diagrama de flujo.
 #### Muchas Gracias :)


