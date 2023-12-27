Guion para Explicar el Diagrama de Flujo del Proyecto GET

Inicio de Extracción de Datos: El proceso comienza con el objetivo de extraer datos relevantes de los proyectos desde la base de datos.

Conexión a la Base de Datos:Se establece una conexión con la base de datos para acceder a los datos necesarios para la planificación.

Decisión: ¿Conexión Exitosa?: Se verifica si la conexión a la base de datos fue exitosa. En caso de fallo, se reintenta la conexión.

Selección de Datos de Proyectos:Se eligen los datos específicos de los proyectos que se requieren para la planificación y gestión.

Recuperación de Datos Seleccionados: Los datos seleccionados se recuperan de la base de datos.

Decisión: ¿Datos Recuperados Correctos y Listos?: Se valida que los datos recuperados sean correctos y completos. Si no lo son, se regresa a la fase de recuperación o selección de datos.

Fin de Extracción de Datos: Concluye la fase de extracción de datos.

Inicio de Planificación Masiva: Se inicia el proceso de cargar en masa la planificación de proyectos y recursos.

Preparar Planificación para Carga: Se preparan los datos de planificación para su carga en el sistema.

Validar Planificación Pre-Carga: Se valida la planificación antes de proceder con la carga.

Iniciar Carga de Planificación: Se inicia el proceso de cargar los datos de planificación en el sistema.

Monitorear Carga de Planificación: Se supervisa el proceso de carga para asegurarse de que se realice correctamente.

Decisión: Verificar Planificación Post-Carga: Se verifica si la carga de la planificación se ha realizado correctamente. Si hay errores, se regresa a la fase de inicio de carga.

Actualizar Base de Datos con Planificación: Se actualiza la base de datos con la nueva planificación.

Fin de Planificación Masiva: Concluye el proceso de carga masiva de la planificación.

Inicio de la Gestión del Historial de Cambios: Se inicia el proceso de registrar y gestionar los cambios y movimientos de recursos.

Registrar Movimientos de Recursos: Se registran todos los cambios y movimientos de recursos en el sistema.

Actualizar para ver Tabla de Historial: Se actualiza y gestiona la tabla de historial para su visualización y análisis.

Fin del Proceso de Gestión del Historial: Concluye el proceso de gestión del historial de cambios.

Inicio de Ingreso de Horas por Empleados: Se inicia el proceso donde los empleados ingresan sus horas trabajadas.

Autenticación y Recuperación de Información Asociada al Empleado: Los empleados se autentican en el sistema y recuperan su información asociada, incluyendo proyectos y actividades asignadas.

Decisión: Selección de Proyecto y Actividades de Planificación: Los empleados seleccionan el proyecto y las actividades correspondientes de la planificación para registrar sus horas.

Registro de Horas Trabajadas: Se registran las horas trabajadas en el sistema por parte de los empleados.

Decisión: Validar Información Ingresada: Se valida la información ingresada sobre las horas trabajadas. Si hay errores, se regresa a la fase de registro.

Actualizar Base de Datos con Horas Trabajadas: Se actualiza la base de datos con la información de las horas trabajadas por los empleados.

Fin del Proceso de Ingreso de Horas: Concluye el proceso de ingreso de horas por los empleados.

Inicio de Vista 360 de Actualizaciones: Se inicia la visualización de una vista 360 de todas las actualizaciones, incluyendo planificación, gestión de horas y cambios de recursos.