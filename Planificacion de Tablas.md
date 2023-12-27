1. **Tabla de Proyectos**: Almacena información sobre cada proyecto.
    
    - Campos: ID del Proyecto, Nombre del Proyecto, Descripción, Fecha de Inicio, Fecha de Finalización, etc.
2. **Tabla de Empleados**: Contiene información sobre los empleados.
    
    - Campos: ID del Empleado, Nombre, Rol, Información de Contacto, etc.
3. **Tabla de Asignaciones de Proyectos**: Relaciona empleados con proyectos.
    
    - Campos: ID de Asignación, ID del Proyecto, ID del Empleado, Rol en el Proyecto, etc.
4. **Tabla de Planificación**: Almacena los detalles de la planificación de proyectos.
    
    - Campos: ID de Planificación, ID del Proyecto, Detalles de la Planificación, Fechas, Recursos Asignados, etc.
5. **Tabla de Registro de Horas**: Para el seguimiento de las horas trabajadas por los empleados en los proyectos.
    
    - Campos: ID de Registro de Horas, ID del Empleado, ID del Proyecto, Horas Trabajadas, Fecha, etc.
6. **Tabla de Historial de Cambios**: Registra los cambios en la asignación de recursos y otros aspectos relevantes del proyecto.
    
    - Campos: ID de Cambio, ID del Proyecto, Descripción del Cambio, Fecha del Cambio, etc.
7. **Tabla de Autenticación de Usuarios**: Para gestionar el acceso de los empleados al sistema.
    
    - Campos: ID del Usuario, ID del Empleado, Credenciales, Rol, etc.