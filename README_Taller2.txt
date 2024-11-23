Esta estructura HTML detalla la página web para un hospital, consta de una sección inicial, reseñas, presentación del equipo médico, servicios ofrecidos y el formulario de contacto para dejar a la página. 

[Taller2, Módulo3] En esta ocasión se incorpora funcionalidades de JavaScript
básico en el proyecto del hospital. Además de manipular el DOM, validar datos, y manejar
errores, se pedirá la entrada de información del usuario a través de un prompt, mostrando los resultados por consola o como alertas en el navegador.


************************AVISO********************************
ES NECESARIO AGREGAR DATOS EN EL PROMPT Y ABRIR EL HTML DESDE VSC PARA QUE LA PÁGINA CARGUE CORRECTAMENTE LOS DATOS DE DOCTORES FILTRADOS.

------CÓMO ABRIR EL ARCHIVO------

-->descargar el Taller2.raw-->descomprimirlo 
-->VSC-->File-->Open Folder-->Taller 2

------Carpeta y subcarpetas-------
TALLER 2
--images
--JavaScript
--json
--node_modules
--scss
--index.html
--package
--package-lock
--README

------Explicación de implementaciones en WEB-------
Explicación de stack, heap, queue: estos son básicamente tipos de estructuras de datos.
Empezando con stack, estas son pilas en las que el último elemento en entrar al arreglo es el primero en salir. 
Queue: se basa en que el primer elemento en ser agregado al arreglo es el primero en salir.
Heap: es el espacio de memoria en el que se almacenan todas las variables y constantes declaradas en el código.

PROMPT:
-Al cargar la página surgirá un pop-up que solicite datos como nombre, email y numero.
En el primero verificará que se ingresen solo letras, en el segundo validará la existencia de un @ y en el último, se asegura que los datos ingresados sean solo números.

-Se utilizan let y const en el código JavaScript para declarar variables como nombres, email y números. También agrega los doctores filtrados por años de experiencia en un arreglo llamado 'doctor-list'.

-Uso de ciclos:
Se hace manipulación del DOM para obtener datos de un JSON, agregarlos a un arreglo, agregando una condicional que filtre los doctores con ciertos años de experiencia.

-Debugger
Se utiliza try/catch en todo el JavaScript para explicar cualquier error que surja durante la ejecución del código o carga de la página.



------CRÉDITOS------
images
https://www.pexels.com/es-es/
https://blog.getbootstrap.com/2022/11/11/bootstrap-icons-1-10-0/
https://github.com/404GamerNotFound/bootstrap-5.3-dark-mode-light-mode-switch