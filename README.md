# CALCULADORA Algoritmo Calculadora
	Definir seguir Como Entero
	Definir num1,num2,resultado Como Real
	
		Escribir "Bienvenido a calculadora"
		Escribir "1. sumar"
		Escribir "2. restar"
		Escribir "3. multiplicar"
		Escribir "4. dividir"
		Escribir "5. potencia"
		Escribir "6. raiz cuadrada"
		Escribir "7. seno"
		Escribir "8. coseno"
		Escribir "9. tangente"
		Escribir "10. logaritmo natural (in)"
		Escribir "11. valor de pi"
		Escribir "12. valor e"
		Escribir "Elige una opción: "
		Leer opcion
		Segun opcion hacer
			1:
				Escribir "ingresa el primer número: "
				Leer num1 
				Escribir  "ingresar el segundo número: "
				leer num2
				resultado = num1 + num2
				Escribir "el resultado de la suma es: ", resultado
				
			2:
				Escribir "ingresa el primer número: "
				Leer num1 
				Escribir  "ingresar el segundo número: "
				leer num2
				resultado = num1 - num2
				Escribir "el resultado de la resta es: ", resultado
			3:
				Escribir "ingresa el primer número: "
				Leer num1 
				Escribir  "ingresar el segundo número: "
				leer num2
				resultado = num1 * num2
				Escribir "el resultado de la multiplicación es: ", resultado
			4:
				Escribir "ingresa el primer número: "
				Leer num1 
				Escribir  "ingresar el segundo número: "
				leer num2
				si num2 = 0 Entonces
					Escribir "Error: División entre cero no permitida."
				SiNo
					resultado = num1 / num2
					Escribir "el resultado de la división es: ", resultado 
				
				FinSi
			5:
				Escribir "ingresa la base: "
				Leer num1 
				Escribir  "ingresar el exponente: "
				leer num2
				resultado = num1 ^ num2
				Escribir "el resultado de la potencia es: ", resultado
			6:
				Escribir "ingresa el número: "
				Leer num1
				si num1 < 0 Entonces
					Escribir "Error: no se puede calcular la raiz cuadrada de un numero negativo."
				SiNo
					resultado = raiz ( num1) 
					Escribir " el resultado de la raiz cuadrada es: ", resultado
				FinSi
			7:
				Escribir "ingresa el angulo en grados: " 
				Leer num1 
				resultado = sen(num1) * pi / 180
				Escribir " el resultado del seno es:",resultado
			8: 
				Escribir "ingresa el angulo en grado:"
				leer num1
				resultado =cos(num1 * pi / 180) 
				Escribir " el resultado del coseno es: ", resultado
			9: 
				Escribir " ingresa el angulo en grado:"
				Leer num1 
				resultado = tan(num1* pi / 180)
				Escribir " el resultado de la tangente es:",resultado
			10:
				Escribir " ingresa el numero: " 
				Leer num1 
				si num1 <= 0 Entonces
					Escribir "error: el logaritmo natural no esta definido para numero menores o iguales a cero."
				SiNo
					resultado = ln(num1)
					Escribir "el resultado del lagoritmo natural es:", resultado
				FinSi
				
			11: 
				Escribir "el valor de pi es:",pi
			12: 
				Escribir " el valor de e es:",e
				
			De Otro Modo:
				Escribir "opcion no validad." 
			
		FinSegun
FinAlgoritmo

