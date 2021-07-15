# Algoritmos

## Algoritmos cálculos de cilindro 

### Algoritmo para cálculo del volumen de un cilindro 

Algoritmo Volumen_Cilindro

	Escribir "Digite el diámetro del cilindro"
	
	Leer A
	
	Escribir "A =" A
	
	C <- (A/2)
	
	Escribir "El radio del  cilindro es:", C 
	
	D <- (C*C)
	
	Escribir "El radio al cuadrado corresponde a:" D
	
	Escribir "Digite la altura del cilindro"
	
	Leer F
	
	Escribir "Digite el valor de Pi" 
	
	Leer G 
	
	Escribir "El volumen del cilindro corresponde a:" D * F * G
	
FinAlgoritmo

### Algoritmo para cáculo del volumen del cilindro #2

Algoritmo Volumen_cilindro
	
	Escribir "Para calcular el volumen de un cilindro"
	
	P <- 3.1416
	
	Escribir sinsaltar "Digite el radio del cilindro"
	
	Leer R
	
	Escribir sinsaltar "Digite la altura del cilindro"
	
	Leer H 
	
	R2 <- (R*R)
	
	Escribir "El volumen del cilindro es:" H * R2 * P 
FinAlgoritmo

### Algoritmo para cálculo del área de un cilindro 

Algoritmo Área_Superficie_Cilindro

	Escribir "El área de un cilidro es: área de su superficie es 2Pi r h + 2Pi r²."
	
	Escribir "Digite el diámetro del cilindro"
	
	Leer A
	
	Escribir "A =" A
	
	C <- (A/2)
	
	Escribir "El radio del  cilindro es:", C 
	
	D <- (C*C)
	
	Escribir "El radio al cuadrado corresponde a:" D
	
	Escribir "Digite la altura del cilindro"
	
	Leer F
	
	Escribir "Digite el valor de Pi" 
	
	Leer G
	
	Escribir "El área del cilindro corresponde a:" ((2*G) * C * F) + ((2*G)*D)
	
FinAlgoritmo

### Algoritmo cálculo área de un cilindro 

Algoritmo Volumen_cilindro
	
	Escribir "Para calcular área de un cilindro"
	
	P <- 3.1416 
	
	Escribir sinsaltar "Por favor digite el radio del cilindro"
	
	Leer R
	
	Escribir Sinsaltar "Por favor digite la altura del cilindro"
	
	Leer H 
	
	Escribir "El área de su cilindro es:" ((2*P) * R *  H) + ((2*P) * (R*R)) 

FinAlgoritmo

## Algortimo cálculo calificaciones 

Algoritmo Cálculo_Calificaciones

	Escribir "El promedio ponderado de la calificación de un alumno es: Parcial 1 = 25%, Parcial 2 = 25%, Participación = 20%, Examen final = 30%"
	
	Escribir "Digite la calificación del primer parcial"
	
	Leer A
	
	B <- (A * 0.25)
	
	Escribir "Digite la calificación del segundo parcial" 
	
	Leer C
	
	D <- (C * 0.25)
	
	Escribir "Digite la calificación del examen final"
	
	Leer E
	
	F <- (E*0.3)
	
	Escribir "Digite la calificación de la nota de participación"
	
	Leer G
	
	H <- (G * 0.2)
	
	Escribir "La calificación ponderada del estudiante es:" B + D + F + H

FinAlgoritmo
