# Ejercicio 1

***

## Pregunta del Ejercicio

En un edificio de 10 departamentos se desea conocer cuantas personas viven en total. Para cada departamento se debe ingresar la cantidad de personas mayores y menores de edad. Al finalizar, calcular el total de personas del edificio y determinar si viven mas personas mayores de edad, mas menores de edad o si hay la misma cantidad de ambos.

R// Algoritmo sin_titulo
		Definir mayores, menores Como Entero
		Definir totalMayores, totalMenores, totalPersonas Como Entero
		Definir i Como Entero
		totalMayores <- 0
		totalMenores <- 0
		Para i <- 1 Hasta 10 Hacer
			Escribir "Departamento ", i
			Escribir "Ingrese cantidad de personas mayores de edad:"
			Leer mayores
			Escribir "Ingrese cantidad de personas menores de edad:"
			Leer menores
			totalMayores <- totalMayores + mayores
			totalMenores <- totalMenores + menores
		FinPara
		totalPersonas <- totalMayores + totalMenores
		Escribir "En el edificio viven ", totalPersonas, " personas."
		Si totalMayores > totalMenores Entonces
			Escribir "Viven mas personas mayores y son ", totalMayores
		SiNo
			Si totalMenores > totalMayores Entonces
				Escribir "Viven mas personas menores y son ", totalMenores
			SiNo
				Escribir "Viven la misma cantidad de personas mayores y menores."
			FinSi
		FinSi
FinAlgoritmo
