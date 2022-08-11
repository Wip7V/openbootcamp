```sh
## En pseudocódigo 

Classe Persona{
	privada numero edad
	privada texto nombre
	privada texto telefono
	
	publica numero getEdad(){
		retorna this.edad
	}
	
	publica texto getNombre(){
		retorna this.nombre
	}
	
	publica texto getTelefono(){
		retorna this.telefono
	}
	
	publica vacio setEdad(numero edad){
		this.edad = edad
	}
	
	publica vacio setNombre(texto nombre){
		this.nombre = nombre
	}
	
	publica vacio setTelefono(texto telefono){
		this.telefono = telefono
	}
	
}


publica vacia main(){
	Persona persona = New Persona()

	persona.setEdad(30)
	persona.setNombre("Juan")
	persona.setTelefono("636099009")


	imprimir persona.getEdad()
	imprimir persona.getNombre()
	imprimir persona.getTelefono()

}
```