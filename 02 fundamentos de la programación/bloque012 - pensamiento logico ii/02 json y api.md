json, javascript object notation
clave, 
valor, 

parsear es convertir un string a un objeto
stringify es convertir un objeto a un string

api, application programming interface
para consumir una api, se necesita una url, un método y un body


fetch('https://jsonplaceholder.typicode.com/todos/1')
  .then(response => response.json())
  .then(json => console.log(json))

devolverá un objeto con la información de la api

{
	userId: 1,
	id: 1,
	title: 'delectus aut autem',
	completed: false
	}