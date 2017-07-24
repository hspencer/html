# HTML demos

Este repositorio sirve el propósito de ejemplificar diversos temas de diseño de interfaz (HTML + CSS) para el curso [Construcción de Diseño Gráfico 4](http://wiki.ead.pucv.cl/index.php/Construcci%C3%B3n_de_Dise%C3%B1o_Gr%C3%A1fico_4)


## Precompiladores

Revisamos el uso de [SASS](http://sass-lang.com/). Para compilar CSS a partir de archivos SASS se puede hacer por 2 vías. (Ver [documentación de instalación](http://sass-lang.com/install)):

* como línea de comando
* como un módulo independiente de Ruby
* como plugin de un framework de desarrollo 

### Instalación

	gem install sass

Si usas windows debes instalar Ruby primero

Para ejecutar SASS desde la línea de comando:

	sass input.scss output.css

También puedes usar SASS para que vigile y actualice el archivo de salida cada vez que se realicen cambios en el archivo fuente SASS:

	sass --watch input.scss:output.css

Si tienes un directorio con muchos archivos SASS vinculados, puedes vigilar el directorio completo:

	sass --watch app/sass:public/stylesheets

Para obtener ayuda: 
	
	sass --help 
	
y obtendrás toda la documentación. 