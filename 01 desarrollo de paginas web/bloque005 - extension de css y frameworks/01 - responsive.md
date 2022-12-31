responsive web design permite a cualquier usuario ver correctamente una web en cualquier dispositivo.

viewport, define el area visible de una página web. ayuda desde html a definir cuál es el anchode la página web.
<meta name="viewport" content="width=device-width, initial-scale=1.0">

no hacer un sitio responsivo en el cual el usuario deba scrolear horizontalmente. 

grid view, se toma el tamaño de pantalla y se parte en columnas. 
"para desktop, esto va a tomar 12 columnas. para tablet, 6 columnas. para celular, 4 columnas"
la grilla suele estar entre 12 a 16 columnas.

primero hay que definir box-sizing: border-box; para que el padding y el border no se sumen al ancho del elemento.
*{
	box-sizing: border-box;
}


media queries, permite aplicar estilos segun el tamaño de pantalla
