Descripción del Proyecto
Este proyecto es un sistema de gestión para una veterinaria, que permite manejar información sobre dueños de mascotas, veterinarios, mascotas (perros y gatos), y turnos para consultas y operaciones. La aplicación está diseñada para facilitar la administración de datos y mejorar la eficiencia en la atención al cliente.

Tecnologías Utilizadas
Java: Lenguaje de programación principal utilizado para desarrollar la lógica del sistema.
Maven: Herramienta de gestión de proyectos y automatización de construcción que se utiliza para manejar las dependencias y la construcción del proyecto.
MySQL: Sistema de gestión de bases de datos utilizado para almacenar la información de los dueños, mascotas, veterinarios y turnos.
Swing: Biblioteca de Java para crear interfaces gráficas de usuario (GUI) que permite la interacción con el usuario a través de ventanas y formularios.
JDBC: API de Java que permite la conexión y ejecución de consultas en bases de datos.
Estructura del Proyecto
El proyecto está organizado en varias clases y paquetes que representan diferentes entidades y funcionalidades:

Modelo: Contiene las clases que representan las entidades del sistema, como Mascota, Duenio, Veterinario, Turno, etc.
Repositorio: Contiene las clases que manejan la conexión a la base de datos y las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para las entidades.
Negocio: Contiene las clases que implementan la lógica de negocio, como ABMDuenio, ABMVeterinario, ABMPerro, etc.
Vista: Contiene las clases que implementan la interfaz gráfica de usuario, como jFromPrincipal y JFormCosnultaTurnoOperacion.
Funcionamiento
Inicio de la Aplicación: Al ejecutar la aplicación, se presenta un menú principal que permite al usuario seleccionar diferentes opciones para gestionar dueños, veterinarios, mascotas y turnos.

Gestión de Dueños: El usuario puede agregar, modificar y listar dueños de mascotas. Se valida la información ingresada para asegurar que no haya duplicados.

Gestión de Veterinarios: Similar a la gestión de dueños, se pueden agregar, modificar y listar veterinarios. También se valida la información ingresada.

Gestión de Mascotas: Se permite agregar mascotas (perros y gatos) asociándolas a un dueño. Se generan códigos únicos para cada mascota.

Gestión de Turnos: Los usuarios pueden crear turnos para consultas y operaciones, asociando un dueño, un veterinario y una mascota. Se valida que no existan turnos duplicados para la misma fecha y hora.

Interfaz Gráfica: La aplicación utiliza formularios y tablas para mostrar la información de manera clara y accesible, permitiendo al usuario interactuar fácilmente con el sistema.

Requisitos
JDK 19 o superior
MySQL Server
Maven
