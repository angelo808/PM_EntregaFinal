Breve explicación del entorno de desarrollo

Flutter es un marco de desarrollo de código abierto creado por Google para la creación de aplicaciones móviles. Utilizando el lenguaje de programación Dart, Flutter permite a los desarrolladores construir interfaces de usuario atractivas y fluidas que funcionan de manera consistente en iOS y Android. Una de las características destacadas de Flutter es su enfoque en la creación de interfaces de usuario mediante la composición de widgets personalizables, lo que facilita la construcción de aplicaciones visualmente atractivas y receptivas. Además, Flutter ofrece un rendimiento optimizado al aprovechar la compilación anticipada, y su naturaleza de código único facilita el mantenimiento y la actualización de aplicaciones en múltiples plataformas.

Para instalar Flutter en Android Studio, primero, descargar e instalar Android Studio desde el sitio oficial. Luego, abra Android Studio y acceda al menú "Configuración" para instalar el complemento Flutter y Dart. Descargue el SDK de Flutter y establezca la variable de entorno PATH para apuntar al directorio "bin" del SDK. En Android Studio, crear un nuevo proyecto Flutter y configurar la ubicación del SDK. Finalmente, ejecute "flutter doctor" en la terminal para asegurarse de que todo esté configurado correctamente. Este proceso garantiza una configuración adecuada para el desarrollo de aplicaciones Flutter en Android Studio.

Diagrama de despliegue

![diagramaDespliegue](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/b232481a-4b1d-4c8b-a313-f4f5fc5ace95)


Requerimientos no funcionales

Los requerimientos no funcionales son aquellas características que no se encuentran relacionadas directamente con las funcionalidades principales del sistema, sino que explican aspectos más generales del mismo. Estas condiciones prioriza cómo debe responder el sistema en términos de rendimiento,seguridad,
 confiabilidad entre otros.

Teniendo en cuenta el concepto principal de lo que es un requerimiento no funcional, es momento de analizar nuestro proyecto , el cual , consiste en realizar un aplicativo móvil donde se pueda tener una cuenta y se observe la rutina de ejercicios que se le asignó a dicho usuario. Cada ejercicio de esta lista está totalmente detallado, desde una premisa de texto explicando cómo se realiza el ejercicio hasta un video demostrativo del mismo ejercicio. Sabiendo cómo funciona el programa y los conceptos claros se pasa a declarar los requerimientos no funcionales en diferentes campos.

1.Rendimiento del sistema:

Para este campo se requiere que el sistema debe tener un tiempo de carga aceptable, es decir que el sistema no demore en iniciar teniendo un tiempo máximo aceptable. También se debe tener en cuenta el tiempo de respuesta que hay entre la interacción del usuario con el sistema hasta que la aplicación da una respuesta.

2.Consumo de recursos

Se debe limitar la cantidad de recursos como la capacidad de procesamiento( CPU), memoria y batería para garantizar un rendimiento eficiente.

3.Experiencia del usuario:

En este campo se define la calidad de la experiencia del usuario. qué tan cómodo y que tan satisfecho se encuentra al momento de utilizar el aplicativo implementado, la facilidad de uso ,la navegación y el diseño del mismo.

4.Disponibilidad del producto:

Para este requerimiento se debe especificar el tiempo máximo de inactividad permitido y la capacidad de recuperación ante algún fallo.

5. Tolerancia a fallos:

Describe cómo la aplicación maneja situaciones de error y se recupera de ellas sin afectar la experiencia del usuario.

6. Autenticación y autorización:

Define los mecanismos de autenticación como lo son el uso de credenciales usuario y contraseña para poder acceder al sistema y a los datos completos con las funcionalidades.

7. Protección de datos:

Establece pautas para garantizar la privacidad y seguridad de la información del usuario.

8.Modularidad del sistema:

Facilita la capacidad de modificar , actualizar y ampliar la aplicación sin tener que comprometer otros campos o partes del sistema.

9.Correcta documentación:

Proporciona una documentación clara y completa para facilitar el mantenimiento del aplicativo por parte de cualquier equipo de desarrollo.

10.Compatibilidad con los sistemas operativos:

Indicar qué dispositivos y versiones del sistema operativo son compatibles con la aplicación que se está implementando.

Diagrama de casos de uso (requerimientos funcionales)

![](RackMultipart20231120-1-xgwkik_html_671a66c3b9ad5e10.png)

Descripción de casos de uso (incluye mockups)

1. Acceso al sistema:

Permite a los usuarios autenticarse en la aplicación con sus credenciales de la Universidad de Lima, brindándoles acceso personalizado a sus datos y funcionalidades.

![ingreso](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/07fd85d5-038c-4548-88cb-ebe3ed50c057)

1. Cambio de contraseña

Da a los usuarios la capacidad de modificar su contraseña de acceso para mantener la seguridad de su cuenta.

![cambioPassword](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/8419d331-ea4b-48d3-9c7f-72eb724d014f)

1. Crear una cuenta

Facilita a nuevos usuarios la creación de una cuenta en la aplicación del gimnasio, proporcionando la información necesaria y validando la pertenencia a la Universidad de Lima.

![](RackMultipart20231120-1-xgwkik_html_d3cf0632de09977b.png)

1. Mostrar rutina

Muestra la rutina de ejercicios asignada a un usuario específico, detallando los ejercicios, repeticiones y series planificadas.

![](RackMultipart20231120-1-xgwkik_html_840d4436488892b1.png)

1. Filtrar ejercicios de rutina

ermite a los usuarios filtrar la lista de ejercicios según la parte del cuerpo que deseen trabajar, facilitando la personalización de sus rutinas de entrenamiento.

![](RackMultipart20231120-1-xgwkik_html_e4b2f81588d1a0c7.png)

1. Mostrar ejercicios de rutina

Proporciona detalles específicos de cada ejercicio dentro de la rutina, incluyendo videos instructivos y explicaciones detalladas para una ejecución correcta.

![](RackMultipart20231120-1-xgwkik_html_cb688a4ed2dc7977.png)

1. Mostrar ejercicios

Similar al caso anterior, pero accedido desde la sección general de ejercicios en lugar de la rutina personalizada.

![](RackMultipart20231120-1-xgwkik_html_4aa57fe45e8fbe00.png)

1. Filtrar ejercicios

Permite a los usuarios filtrar la lista de ejercicios según la parte del cuerpo que deseen trabajar, facilitando la personalización de sus rutinas de entrenamiento.

![](RackMultipart20231120-1-xgwkik_html_154221a686344315.png)

1. Compartir de redes sociales

​​Permite a los usuarios compartir sus logros, rutinas o ejercicios favoritos en redes sociales, fomentando la interacción social y la motivación entre los miembros del gimnasio.

![](RackMultipart20231120-1-xgwkik_html_57c024772070e0ae.png)

1. Mostrar integrantes

Presenta una lista de los miembros del gimnasio que forman parte de un grupo específico, fomentando la comunidad y la colaboración en el logro de objetivos de acondicionamiento físico.

![](RackMultipart20231120-1-xgwkik_html_9cc6d0b5014af049.png)

1. Actualizar perfil

Permite a los usuarios modificar y mantener actualizada su información personal, preferencias y objetivos de entrenamiento en su perfil de la aplicación.

![](RackMultipart20231120-1-xgwkik_html_fb5cb66c038f7ec.png)
