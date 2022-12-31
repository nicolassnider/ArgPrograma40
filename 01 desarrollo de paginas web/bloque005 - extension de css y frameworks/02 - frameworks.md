que es un media query?
un media query es una condición que se evalúa para determinar si se aplica un estilo o no.
@media only screen and (max-width: 600px){
	/* styles for screens smaller than 600px; */
	body{
		background-color: red;
	}
}
@media (min-width: 600px) and (orientation:landscape){
	/* styles for screens larger than 600px in landscape orientation; */
	body{
		background-color: blue;
	}
}

librerías full responsive.

bootstrap, permie con definiciones de clases crear sitios responsivos sin tener que declarar todas las medias query.
foundation y tailwind