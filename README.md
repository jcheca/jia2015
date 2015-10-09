# jia2015
Buscador local de Ponencias para USB/CD/DVD

A los asistentes de congresos, jornadas, etc. se le suele dar un CD/DVD/USB con la recopilación de la documentación
expuesta, en este caso todas las ponencias en formato .pdf. Para que no tenga que explorar todo el sistema de archivos
para localizar un documento conreto, se ha creado este interface web con la relación de documentos y una herramienta
con un motor de búsqueda local por diferentes criterios.

Software utilizado:

- HTML5
- Bootstrap
- Angularjs
- Plugin para visor PDF de brojask en http://bootsnipp.com/snippets/VX7EN

Instalación:

Volcar en el directorio raiz del CD/DVD/USB en contenido de este repositorio. La información que se muestra en el índice
se encuetra en la app de angular "bower_components/jia2015/jia2015.js" en una variable (trabajos) que mantienen en memoria 
un array de objetos adaptable a las necesidades.