# Proyecto Chat

### Objetivo

Proyecto en el que teníamos que programar el frontend de un chat de texto usando un backend y base de datos dada por nuestro profesor.
He usado tanto el backend como la base de datos sin tocar nada dentro, incluso he usado las mismas librerias, así que no debería haber ningún problema de dependencias.

El diseño de la página web era de libre elección, y he intentado hacer una web de temática retro como si de un foro antiguo se tratase, aunque con un toque más moderno y responsive.

He usado Eclipse con Tomcat 10.1 para administrar el backend y XAMPP 8.2.4 de Linux para la base de datos.

## Login y Registro

Páginas simples que contienen un formulario a rellenar y en el caso del login detectan que sen correctas las credenciales y el registro detecta que todo lo que hayas insertado esté bien e inserta los datos en la BBDD. Cabe remarcar el tratamiento de JSON en el registro con los países.

Página del login:

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/c4661a81-6f2e-450b-a019-ab78be149d2e)

Página del registro:

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/271f490e-e82e-401f-ac76-905d1df84229)

## Chat

Esta página es la más compleja del proyecto, así que iré parte por parte con como funciona.

Página del chat vacía:

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/d7c6ed19-26e9-49f8-af92-3eb446f15d16)

Los botones *Mostrar conversación* y *Ocultar conversación* sirven para mostrar y ocultar la conversación seleccionada en el *select*. Si llega algún mensaje y tenemos la conversación oculta, recibiremos un aviso en la barra lateral.

Muestra de recibo de aviso:

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/cdf232af-7259-40b6-bfeb-e2a482e9e83d)

Ejemplo de conversación entre dos personas:

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/9b762c28-c7e6-4bc1-ab7d-0be8d2a196a1)

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/6afc042d-013c-42d8-8e1c-e2ba8fe4784d)

Ejemplo de recibo de varios avisos y mensajes de diferentes personas (pueden ocultarse o mostrarse los mensajes de cada una):

![imagen](https://github.com/joanmrt/Chat-Lenguaje-de-Marcas/assets/74322611/90035860-90ac-4b97-af83-201150f52c6a)
