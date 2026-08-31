### algoritmo
realizar un algoritmo para encontrar el precio más caro entre varios artículos.

Algoritmo ejercicio
		Definir N, i Como Entero
		Definir precio, mayor Como Real
		Escribir "¿Cuántos artículos desea ingresar?"
		Leer N
		Escribir "Ingrese el precio del artículo 1:"
		Leer mayor
		Para i <- 2 Hasta N Hacer
			Escribir "Ingrese el precio del artículo ", i, ":"
			Leer precio
			Si precio > mayor Entonces
				mayor <- precio
			FinSi
		FinPara
		Escribir "El precio del artículo más caro es: ", mayor
FinAlgoritmo

### algoritmo
realizar un algoritmo que me de el area del circulo
Algoritmo areacirculo
	Escribir "dame el radio del circulo"
	leer r
	area = 3.14 * r^2
	Escribir "el area de la circunferencia es" area
FinAlgoritmo