🌌 PSP-RMI-CONSTELACIONES
Aplicación Java que implementa un sistema cliente-servidor utilizando Java RMI (Remote Method Invocation) para consultar información sobre constelaciones. Este proyecto fue desarrollado como parte de la Unidad Formativa 3 del módulo de Programación de Servicios y Procesos (PSP) del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM).

🚀 Funcionalidades
Servidor RMI que ofrece información detallada sobre diversas constelaciones.

Cliente RMI que permite al usuario consultar datos de constelaciones específicas.

Comunicación remota entre cliente y servidor mediante la tecnología Java RMI.

Estructura modular que facilita la comprensión y mantenimiento del código.

📁 Estructura del repositorio
plaintext
Copiar
Editar
PSP-RMI-CONSTELACIONES/
├── Cliente UF3-1/             → Código fuente del cliente RMI
│   └── Cliente.java
├── Servidor UF3-1/            → Código fuente del servidor RMI
│   ├── Servidor.java
│   └── Constelaciones.java    → Interfaz remota
├── Actividad2 Obligatoria. Servidor RMI de constelaciones.docx
├── Actividad2 Obligatoria. Servidor RMI de constelaciones.pdf
└── .gitattributes             → Configuraciones de Git
🛠️ Requisitos
Java Development Kit (JDK) 8 o superior.

Entorno de desarrollo como IntelliJ IDEA, Eclipse o NetBeans.

Consola de comandos para compilación y ejecución manual.

🖥️ Instrucciones de ejecución
1. Compilar las clases
bash
Copiar
Editar
# Compilar la interfaz remota
javac Constelaciones.java

# Compilar el servidor
javac Servidor.java

# Compilar el cliente
javac Cliente.java
2. Iniciar el registro RMI
bash
Copiar
Editar
start rmiregistry
Asegúrate de ejecutar este comando en el directorio donde se encuentran las clases compiladas.

3. Ejecutar el servidor
bash
Copiar
Editar
java Servidor
4. Ejecutar el cliente
En una nueva terminal:

bash
Copiar
Editar
java Cliente
📌 Notas adicionales
La interfaz Constelaciones.java define los métodos remotos que el servidor ofrece al cliente.

El servidor debe estar en ejecución antes de iniciar el cliente para establecer la conexión correctamente.

Este proyecto es una base para entender la comunicación cliente-servidor utilizando Java RMI y puede ser ampliado con funcionalidades adicionales como manejo de múltiples clientes, autenticación, etc.

👨‍💻 Autor
Iván Núñez Rodríguez
📧 ivannr20@gmail.com
🎓 Técnico Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)
