AsyncModulesJS
==============

Es un quick & dirty cargador de modulos en JS, biene bien para cuando se trabaja en un entorno hostil y se necestian librerias de algun CDN. 

Modo de Uso: 

	<script type="text/javascript" src="lazy.js"></script>

y

	/*
	    codigo fuente 
	*/

	lazy.loadjs(["//cdnjs.cloudflare.com/ajax/libs/jquery/1.11.0/jquery.js", 
			       "//cdnjs.cloudflare.com/ajax/libs/jqueryui/1.10.4/jquery-ui.min.js"], 
			 function(){

			  $('.titulo').text("Hello world");
			 
			 });

	}());
	
