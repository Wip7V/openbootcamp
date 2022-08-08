/* tambien en pseudocódigo */

entero numeroIf = -5

if( numeroIf < 0 ) {
	imprimir "El numeroIf es negativo"
}

if( numeroIf > 0 ) {
	imprimir "El numeroIf es positivo"
}

if( numeroIf == 0 ) {
	imprimir "El numeroIf es 0"
}

/* No tengo por costumbre usar Else If, me parece mas dificil de entender y mantener, y uso el Else normal cuando necesito manipular la condición contraria al If original */

entero numeroWhile = 0

While( numeroWhile < 3 ){

	imprimir numeroWhile
	numeroWhile++
	
}

do {

	imprimir numeroWhile
	
}While( numeroWhile < 3 )


for( numeroFor=0 ; numeroFor <= 3; numeroFor++){

	imprimir numeroFor
	
}

texto estacion = "Verano"

Switch(estacion){

caso "Primavera":
	imprimir "Estamos en Primavera"
	break

caso "Verano":
	imprimir "Estamos en Verano"
	break

caso "Otoño":
	imprimir "Estamos en Otoño"
	break

caso "Invierno":
	imprimir "Estamos en Invierno"
	break

default:
	imprimir "Ninguna de las anteriores"
	break
	
}