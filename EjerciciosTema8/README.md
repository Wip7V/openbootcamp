/* En pseudocódigo */

Classe Persona{
	privada numero edad
	privada texto nombre
	privada texto telefono
	
	constructor(numero edad, texto nombre, texto telefono){
		this.edad = edad
		this.texto = texto
		this.telefono = telefono
	}
	
	publica numero getEdad(){
		retorna this.edad
	}
	
	publica texto getNombre(){
		retorna this.nombre
	}
	
	publica texto getTelefono(){
		retorna this.telefono
	}
	
	publica setEdad(numero edad){
		this.edad = edad
	}
	
	publica setNombre(texto nombre){
		this.nombre = nombre
	}
	
	publica setTelefono(texto telefono){
		this.telefono = telefono
	}
	
}


publica vacia main(){

Persona persona = New Persona()


persona.setEdad(30)

persona.setNombre("Juan")

persona.setTelefono("636099009")


imprimir persona.getEdad

imprimir persona.getNombre

imprimir persona.getTelefono


}