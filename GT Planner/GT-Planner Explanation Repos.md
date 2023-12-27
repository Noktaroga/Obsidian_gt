Conocer algunos detalles específicos. Lista de preguntas y acciones clave para entender cómo funciona el proyecto y cómo puedes empezar a trabajar con él. Dado que mencionaste que el proyecto utiliza React, Python, Azure SQL, Azure Functions y está dividido en dos repositorios para el backend y el frontend, las siguientes preguntas y pasos son relevantes:

Comprender la Estructura del Proyecto

Estructura de los Repositorios:

- ¿Cómo están organizados los directorios y archivos en gtplanner-back y gtplanner-front?
- ¿Hay algún documento de README o de documentación que describa la arquitectura o la configuración del proyecto?

Dependencias:

- ¿Qué librerías o frameworks específicos se utilizan en el frontend (React) y en el backend (Python)?
- ¿Cómo se manejan las dependencias (por ejemplo, package.json para React, requirements.txt o Pipfile para Python)?

Configuración del Entorno:

- ¿Existen archivos de configuración específicos (como .env) para las variables de entorno?
- ¿Cómo se configura y se conecta a la base de datos de Azure SQL y a Azure Functions?
- Entender la Comunicación entre Frontend y Backend

API y Puntos de Conexión:
- ¿Cómo se definen las API en el backend (Python)? Busca archivos que definan rutas o endpoints.
- ¿Cómo el frontend (React) realiza llamadas a estas API? Busca donde se usen funciones como fetch o librerías como Axios.

Autenticación y Autorización:

¿Cómo se maneja la autenticación y la autorización entre el frontend y el backend?
¿Se utiliza algún servicio de Azure para la autenticación, como Azure Active Directory?

Flujo de Datos:

¿Cómo fluyen los datos entre el frontend, el backend y la base de datos?
¿Hay algún esquema o diagrama que ilustre este flujo?
Configurar el Entorno de Desarrollo
Clonar los Repositorios:



git clone [URL de gtplanner-back]
git clone [URL de gtplanner-front]

Instalar Dependencias:
Para el frontend (React), normalmente ejecutarás npm install o yarn dentro del directorio del proyecto.
Para el backend (Python), necesitarás ejecutar pip install -r requirements.txt o un comando similar.

Configurar Bases de Datos y Servicios Azure:
Configura las conexiones a Azure SQL y Azure Functions según la documentación del proyecto.
Asegúrate de tener acceso a las credenciales y configuraciones necesarias.
Ejecutar los Proyectos Localmente:

Inicia el servidor backend (Python) y el servidor de desarrollo frontend (React).
Pruebas y Simulación
Pruebas Unitarias y de Integración:

Revisa si hay pruebas automatizadas y cómo ejecutarlas.
Estas pruebas pueden darte una idea de cómo se espera que funcionen diferentes partes del sistema.
Simulación de Flujos de Usuario:

Intenta reproducir acciones comunes de los usuarios para entender el flujo de la aplicación.
Verifica cómo las acciones en el frontend afectan al backend y a la base de datos.
Aprender de la Documentación y el Código
Lee la Documentación Disponible: Si hay documentación, dedica tiempo a leerla detenidamente.
Explora el Código: A menudo, explorar el código es la mejor manera de entender cómo funciona un proyecto.
Preguntas Adicionales
¿Hay algún equipo de desarrollo con el que puedas hablar para obtener una comprensión más profunda del proyecto?
¿Existen diagramas de arquitectura o documentos que expliquen las decisiones de diseño?
Esta es una guía general para comenzar. Dependiendo de las respuestas a estas preguntas y lo que encuentres en los repositorios, es posible que necesites adaptar estos pasos.