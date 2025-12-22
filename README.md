# Caso de uso 

Caso de uso: restricción de terrazas en Madrid por covid-19.

Contratan a nuestro equipo para actualizar las restricciones de ciertos locales y terrazas en Madrid por cuestiones del covid-19. Los datos para actualizar están en el fichero llamado act-grupal-openDataLocalesMadrid.cvs y se os pide que consolidéis dichos cambios en una base de datos MongoDB llamada Madrid con la colección Terrazas. La información del dataset a utilizar lo tenéis en la siguiente [URL: Open Data Censo de locales, sus actividades y terrazas de hostelería y restauración (Terrazas)](https://datos.madrid.es/FWProjects/egob/Catalogo/Economia/Ficheros/Estructura_DS_FicheroCLA_Terrazas.pdf)

**En el alcance del contrato se nos solicita:**

a. Convertir el fichero CVS a formato JSON.\
b. Descargar el fichero generado en el paso anterior, en formato JSON indicando la opción Array. En el fichero hay un problema de espacios en muchos campos de tipo String, que se solicitan corregir en esta etapa.\
c. Editar el archivo generado, y al principio de todo añadir la línea: `var datos_insertar =`\
d. Guardar el fichero en una ruta conocida y cambiar su extensión a formato .js y explicar que tipo de fichero es un `.js`\
e. Abrir el cliente *mongo* y ejecutar las siguientes instrucciones:\
        `load("PATH\fichero.js")`\
        `datos_insertar[0]`\
f. Describir brevemente las instrucciones anteriores\
g. Se consulta si con el elemento: `datos_insertar ` ¿se podría realizar un ´insert´ masivo? ¿Cómo?\
h. Desde la terminar, nos solicitar proponer una alternativa que evite realizar los pasos anteriores, con una descripción de máximo de dos líneas.  


**Para realizar esta parte de la actividad realizamos lo siguiente:**
1. Alojamos la base de datos en github en la carpeta data
2. Escribirmos todo el codigo y las explicaciones de los paso a paso en un notebook de Google Google Colab al que se puede ingresar por el siguiente [ENLACE](https://github.com/Merenguimona/act_2/blob/4b0ffd19980390b77c38a8afdabd5e86e8cf129a/notebook/Actividad_2.ipynb)
3. Las bases de datos en formato json y js se encuentrán en la carpeta [outputs](https://github.com/Merenguimona/act_2/tree/4b0ffd19980390b77c38a8afdabd5e86e8cf129a/outputs)
