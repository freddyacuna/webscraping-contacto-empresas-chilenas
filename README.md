# Obejtivo
este proyecto consiste en extraer información de contacto (nombre, telefono, mail de contacto) de empresas que se encuentran registradas en [SII](https://www.sii.cl/). Se utiliza python para su ejecución.

El código automatiza la busqueda masiva de la información. Los pasos que deberá tener la busqueda son:



1.   Abrir una pestaña del buscador
2.   Ir a la pagina de google maps
3.   Ingresar el nombre de la empresas que aparece en nuestra bbdd del SII (filtrada para empresas excluye instituciones publicas y personas naturales).
4.   Abrir la coincidencia del buscador de google maps.
5.   Extraer los datos (nonmbre, telefono, sitio web) y guardarlos en un googlesheet.
6.   Si existe sitio web y se logra una coincidencia entre la busqueda de maps y el nombre de la empresa, procedemos a re-direccionar al sitio web.
7.   Realizar escrapeo del sitio web para extraer el mail contacto de al menos 15 pestañas del sitio. Luego se guarda en googlesheet los mail de contactos 
8.   Repetir el procedimiento N donde N corresponde al total de empresas registradas en el SII luego de filtrada la bbdd.


Por otro lado, será interesante replicar este mismo procedimiento usando R. Los paquetes relevantes para su aplicación son:



*   Realizar web scraping mediante el paquete [rvest] y [polite].
*   Acceder y modificar información en planillas de Google Sheets mediante el [googlesheets4].
*   Capturar información y tweets en Twitter mediante el paquete [rtweet]
*   Limpiar y modificar caracteres mediante expresiones regulares ([stringr])
*   Programación funcional para manejar sobre estructuras de datos como JSON o listas mediante funciones del paquete [purrr]

Si le interesa seguir este camino, no dude en contactarse con: 
1. [Github Freddy Acuña](https://github.com/freddyacuna)
2. [Linkedin Freddy Acuña](https://www.linkedin.com/in/freddyacuna/)
