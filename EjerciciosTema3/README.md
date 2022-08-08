/*

Ejecicios del tema 3 del apartado de Introducción.
Como no se piden en ningun leguaje especifico lo escribo en pseudocódigo.

*/

publica entero SumarTres( valor1, valor2, valor3){
	retorna valor1+valor2+valor3
}


imprimir SumarTres(10,5,8)



Classe coche{
	privada entero puertas
	
	constructor(){
		puertas = 0
	}

	publico entero ObtenerPuertas(){
		retona puertas
	}
	
	publico IncrementaPuertas(){
		puertas ++
	}

}

miCoche = nuevo coche

miCoche.IncrementarPuertas()

imprimir miCoche.ObtenerPuertas()
