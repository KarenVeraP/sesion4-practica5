#Práctica 5. Uso de Azure Functions

##Crear la función
Para crear nuestra funciín buscaremos la Aplicación de funciones en [Azure Portal](https://portal.azure.com/).

![p5p1](imagenes\p5p1.png)

Creamos una función.

![p5p2](imagenes\p5p2.png)

Llenamos los siguiente parámetros:
- Susrcipción
- Grupo de recursos: sesion 4
- Nombre de la aplicación de funiones (debe ser único): mifuncion321
- Pila: Node.js
- Región: Central US
- SO: Linux, aunque si durante la creación nos marca error, cambimos a Windows

![p5p3](imagenes\p5p3.png)

Elegimos el plan de _Consumo (sin servidor)_, y dejamos los emás parámetros igual. Revisamos y creamos, luego Creamos.

![p5p4](imagenes\p5p4.png)

--------------------------------
##Programar la función

En la función buscamos en el apartado de Funciones _Funciones_, y creamos una.

![p5p5](imagenes\p5p5.png)

En el trigger elegimos la plantilla _HTTP_ trigger y creamos

![p5p6](imagenes\p5p6.png)

###Programar el Trigger
En el trigger creado buscamos en Developer _Código y prueba_.

![p5p7](imagenes\p5p7.png)

Nos aparecerá un código. Seleccionamos Probar/ejecutar.

![p5p8](imagenes\p5p8.png)

Se abrirá una ventana que nos pedirá nuestro nombre.

![p5p9](imagenes\p5p9.png)

Al ejecutar la ventana que nos aareció nos mostrará el sguiente texto:

![p5p11](imagenes\p5p10.png)

 Podemos modificar los mensajes, así como el código; antes de seleccionar Probar/ejecutar debemos guardar los cambios realizados.

![p5p11](imagenes\p5p11.png)

La ventana se abrirá de nuevo y podemos observar los cambios realizados

![p5p13](imagenes\p5p13.png)

##Obtener URL
Podemos obtenerel URL de la función si seleccionamos  _Obtener la dirección URL de la función_ y compiando el URL.

![p5p12](imagenes\p5p12.png)

Para obtener la clave de la función, en el apartado Developer seleccionamos _claves de función_.

![p5p14](imagenes\p5p14.png)

En la clave _default_ tenemos una opción para visualizar el valor, seleccionamor y copiamos la clave.

![p5p15](imagenes\p5p15.png)

##Extra
Recursos creados por la función
- Aplicación de funciones
- Aplicación Insights

![p5p16](imagenes\p5p16.png)