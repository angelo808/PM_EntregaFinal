########################################################################################################

# **Asignación numero 4.**
# **Creación archivo markdown en github.**
 ## *Integrantes*
 ### - *Guillen Chara Angelo*
 ### - *Izaguirre Castro Andoni Tomas*
 ### - *Linares Alzamora Rodrigo Gabriel*
 ### - *Meneses Gutierrez Hector Jose*
 ### - *Sotelo Gomez Franco*

########################################################################################################



 
# 1. **Breve explicación del entorno de desarrollo**
 Flutter es un marco de desarrollo de código abierto creado por Google para la creación de aplicaciones móviles. Utilizando el lenguaje de programación Dart, Flutter permite a los desarrolladores construir interfaces de usuario atractivas y fluidas que funcionan de manera consistente en iOS y Android. Una de las características destacadas de Flutter es su enfoque en la creación de interfaces de usuario mediante la composición de widgets personalizables, lo que facilita la construcción de aplicaciones visualmente atractivas y receptivas. Además, Flutter ofrece un rendimiento optimizado al aprovechar la compilación anticipada, y su naturaleza de código único facilita el mantenimiento y la actualización de aplicaciones en múltiples plataformas.
 
 Para instalar Flutter en Android Studio, primero, descargar e instalar Android Studio desde el sitio oficial. Luego, abra Android Studio y acceda al menú "Configuración" para instalar el complemento Flutter y Dart. Descargue el SDK de Flutter y establezca la variable de entorno PATH para apuntar al directorio "bin" del SDK. En Android Studio, crear un nuevo proyecto Flutter y configurar la ubicación del SDK. Finalmente, ejecute "flutter doctor" en la terminal para asegurarse de que todo esté configurado correctamente. Este proceso garantiza una configuración adecuada para el desarrollo de aplicaciones Flutter en Android Studio.


# 2. Diagrama de despliegue

![diagramaDespliegue](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/b232481a-4b1d-4c8b-a313-f4f5fc5ace95)


# 3. Requerimientos no funcionales

Los requerimientos no funcionales son aquellas características que no se encuentran relacionadas directamente con las funcionalidades principales del sistema, sino que explican aspectos más generales del mismo. Estas condiciones prioriza cómo debe responder el sistema en términos de rendimiento,seguridad,
 confiabilidad entre otros.

Teniendo en cuenta el concepto principal de lo que es un requerimiento no funcional, es momento de analizar nuestro proyecto , el cual , consiste en realizar un aplicativo móvil donde se pueda tener una cuenta y se observe la rutina de ejercicios que se le asignó a dicho usuario. Cada ejercicio de esta lista está totalmente detallado, desde una premisa de texto explicando cómo se realiza el ejercicio hasta un video demostrativo del mismo ejercicio. Sabiendo cómo funciona el programa y los conceptos claros se pasa a declarar los requerimientos no funcionales en diferentes campos.

### *3.1. Rendimiento del sistema:*

Para este campo se requiere que el sistema debe tener un tiempo de carga aceptable, es decir que el sistema no demore en iniciar teniendo un tiempo máximo aceptable. También se debe tener en cuenta el tiempo de respuesta que hay entre la interacción del usuario con el sistema hasta que la aplicación da una respuesta.

### *3.2. Consumo de recursos*

Se debe limitar la cantidad de recursos como la capacidad de procesamiento( CPU), memoria y batería para garantizar un rendimiento eficiente.

### *3.3. Experiencia del usuario:*

En este campo se define la calidad de la experiencia del usuario. qué tan cómodo y que tan satisfecho se encuentra al momento de utilizar el aplicativo implementado, la facilidad de uso ,la navegación y el diseño del mismo.

### *3.4. Disponibilidad del producto:*

Para este requerimiento se debe especificar el tiempo máximo de inactividad permitido y la capacidad de recuperación ante algún fallo.

### *3.5. Tolerancia a fallos:*

Describe cómo la aplicación maneja situaciones de error y se recupera de ellas sin afectar la experiencia del usuario.

### *3.6. Autenticación y autorización:*

Define los mecanismos de autenticación como lo son el uso de credenciales usuario y contraseña para poder acceder al sistema y a los datos completos con las funcionalidades.

### *3.7. Protección de datos:*

Establece pautas para garantizar la privacidad y seguridad de la información del usuario.

### *3.8. Modularidad del sistema:*

Facilita la capacidad de modificar , actualizar y ampliar la aplicación sin tener que comprometer otros campos o partes del sistema.

### *3.9. Correcta documentación:*

Proporciona una documentación clara y completa para facilitar el mantenimiento del aplicativo por parte de cualquier equipo de desarrollo.

### *3.10. Compatibilidad con los sistemas operativos:*

Indicar qué dispositivos y versiones del sistema operativo son compatibles con la aplicación que se está implementando.

# 4. **Diagrama de casos de uso (requerimientos funcionales)**

![diagramaCasosUso](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/0dd8cee5-ef39-43ef-9e67-ad729f38eaf1)

# 5. **Descripción de casos de uso (incluye mockups)**

### *5.1.Acceso al sistema:*

Permite a los usuarios autenticarse en la aplicación con sus credenciales de la Universidad de Lima, brindándoles acceso personalizado a sus datos y funcionalidades.
Con esta pantalla se tiene cubierto la navegación entre vistas usando parametros.


![ingreso](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/07fd85d5-038c-4548-88cb-ebe3ed50c057)


### *5.2. Crear una cuenta*

Facilita a nuevos usuarios la creación de una cuenta en la aplicación del gimnasio, proporcionando la información necesaria y validando la pertenencia a la Universidad de Lima.
Con esta pantalla se tiene cubierta la petición post a un servidor de aplicaciones

![creacionCuenta](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/3e43cd0d-5980-419f-9a0c-d6ac6ca568ba)


### *5.3. Mostrar rutina*

Muestra la rutina de ejercicios asignada a un usuario específico, detallando los ejercicios, repeticiones y series planificadas.
Con esta pantalla se tiene se tiene cubierto la petición get a un servidor de aplicaciones

![miRutina](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/a6c2de85-3554-4cb1-b87f-15aaa8fc57b4)


### *5.4. Mostrar ejercicios de rutina*

Proporciona detalles específicos de cada ejercicio dentro de la rutina, incluyendo videos instructivos y explicaciones detalladas para una ejecución correcta.

![detalleMiejercicio](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/39c69b4e-aac0-463a-b6d0-aa47418f656c)



### *5.5. Mostrar integrantes*

Presenta una lista de los miembros del gimnasio que forman parte de un grupo específico, fomentando la comunidad y la colaboración en el logro de objetivos de acondicionamiento físico.

![mostrarIntegrantes](https://github.com/angelo808/PM_EntregaFinal/assets/79600376/76096d06-8859-4747-ae25-ccc05748246f)

