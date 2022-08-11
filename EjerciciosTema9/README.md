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
	
	publica vacia setEdad(numero edad){
		this.edad = edad
	}
	
	publica vacia setNombre(texto nombre){
		this.nombre = nombre
	}
	
	publica vacia setTelefono(texto telefono){
		this.telefono = telefono
	}
	
}

Clase Cliente extiende Persona{

	privada decimal credito
	
	publica decimal getCredito(){
		retorna this.credito
	}
	
	publica vacia setCredito(decimal credito){
		this.credito = credito
	}
	
}

Clase Trabajador extiende Persona{
	privada decimal salario
	
	publica decimal getSalario(){
		retorna this.salario
	}
	
	publica vacia setSalario(decimal salario){
		this.salario = salario
	}
}

publica vacia main(){

	Cliente cliente = New Cliente()

	cliente.setEdad(30)
	cliente.setNombre("Juan")
	cliente.setTelefono("636099009")
	cliente.setCredito(345.05)
	
	imprimir cliente.getEdad()
	imprimir cliente.getNombre()
	imprimir cliente.getTelefono()
	imprimir cliente.getCredito()
	
	Trabajador trabajador = New Trabajador()
	
	trabajador.setEdad(25)
	trabajador.setNombre("Alba")
	trabajador.setTelefono("555555555")
	trabajador.setSalario(850)
	
	imprimir trabajador.getEdad()
	imprimir trabajador.getNombre()
	imprimir trabajador.getTelefono()
	imprimir trabajador.getSalario()

}
```