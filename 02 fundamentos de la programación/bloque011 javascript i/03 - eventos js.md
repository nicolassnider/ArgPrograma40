los eventos de javascript son acciones que se ejecutan cuando se produce un evento en el navegador. por ejemplo, cuando se hace click en un botón, cuando se carga una página, cuando se hace scroll, etc.

document.getElementById('btn').onClick = function() {
  alert('hola mundo')
  document.getElementById('demo').innerHTML = 'fafafafafafafaf'
}

agregar un listener, tipo y a qué se aplica

document.addEventListener('click', function() {
  alert('hola mundo');
})

listado de eventos
https://developer.mozilla.org/es/docs/Web/Events

