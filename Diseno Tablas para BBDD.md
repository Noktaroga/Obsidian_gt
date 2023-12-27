Tabla de Proyectos (Proyectos)

IDProyecto (clave primaria)
NombreProyecto
Descripción
FechaInicio
FechaFin
Estado (ej. en progreso, completado)
Tabla de Empleados (Empleados)

IDEmpleado (clave primaria)
Nombre
Apellido
Rol
Email
Departamento
Tabla de Planificación de Proyectos (PlanificacionProyectos)

IDPlanificacion (clave primaria)
IDProyecto (clave foránea de Proyectos)
FechasClave
RecursosNecesarios
Metas
Estado
Tabla de Registro de Horas (RegistroHoras)

IDRegistro (clave primaria)
IDEmpleado (clave foránea de Empleados)
IDProyecto (clave foránea de Proyectos)
Fecha
HorasTrabajadas
Actividad
Tabla de Historial de Cambios (HistorialCambios)

IDCambio (clave primaria)
IDProyecto (clave foránea de Proyectos)
FechaCambio
DescripcionCambio
TipoCambio (ej. cambio de recursos, modificación de planificación)
Tabla de Autenticación de Empleados (AutenticacionEmpleados)

IDEmpleado (clave foránea de Empleados)
Usuario
Contraseña
ÚltimoAcceso
Tabla de Recursos del Proyecto (RecursosProyecto)

IDRecurso (clave primaria)
IDProyecto (clave foránea de Proyectos)
TipoRecurso
Cantidad
Estado
Tabla de Vista 360 (Vista360)

IDVista (clave primaria)
IDProyecto (clave foránea de Proyectos)
ResumenPlanificacion
ResumenHoras
ResumenCambios