GTPlanner, implica el uso de lenguajes de programación como Python y PowerApps. El proyecto se divide en cuatro procesos o módulos: Clientes, Proyectos, Planificación y Registro de Horas. Cada uno de estos procesos tiene subetapas y roles específicos dentro del flujo de trabajo.

**FASE I: Clientes**
	En la fase de Clientes, se evalúan y seleccionan los clientes a través de una evaluación. 
	
1.1 Datos Registro
	Cada registro incluye información clave del proyecto, como el nombre del proyecto, el cliente asociado, fecha de inicio, etc. Esta información contextualiza cada registro en el contexto general del proyecto.
	
1.2 Background Check
	Posteriormente, se inicia el proceso de fondo (Background check), donde se cargan datos relacionados con la empresa cliente, y se realiza una verificación de riesgos a través de servicios externos como BING, DICOM, etc.

1.3 Asignacion de Riegos
	En la asignación de riesgos, se clasifican los niveles de riesgo que un cliente puede representar para la firma. Los niveles de riesgo son:
	- Bajo: Si se determina que el cliente presenta un riesgo bajo para la firma, la aprobación es realizada únicamente por el Socio de Riesgo.
	- Medio: En el caso de un riesgo moderado, se requiere la aprobación del Socio Líder y del Socio de Riesgos.  
	- Alto: Cuando se identifica un riesgo significativo, se solicita la aprobación del Socio Líder, del Managing Partner y del Socio de Riesgo.
	    
1.4 Aprobacion
	La asignación de estos niveles se basa en la evaluación del riesgo por parte del socio responsable, considerando diversos factores y posiblemente investigaciones adicionales. Este proceso de aprobación asegura que los proyectos con diferentes niveles de riesgo sean revisados y aprobados por los niveles correspondientes de liderazgo en la firma.

Conclusión.
	Después de la aprobación, se genera una ficha técnica del cliente que contiene todos los datos asociados al cliente, y esta ficha se envía a todos los socios de la firma. Esta ficha técnica proporciona una visión integral de la empresa cliente y los detalles relevantes para el proyecto en cuestión.


**FASE II: Proyectos**
En la fase de Proyectos inicia una vez que el cliente ha sido aprobado, se registra el proyecto asociado, el cual se refiere al servicio entregado al cliente. Este proceso implica la automatización de la conciliación de documentos y la declaración de independencia.  La parte del proceso que implica la automatización de la conciliación de documentos y la declaración de independencia se puede desglosar en los siguientes pasos:

2.1. Registro del Proyecto:
	Un usuario, generalmente un socio responsable, accede al sistema GT Planner y registra un nuevo proyecto además durante este registro, se asocia el proyecto a un cliente específico. 
		Notas: ¿A través de? ¿Como? ¿De que manera?

2.2. Declaración de Independencia:
	Después de registrar el proyecto, se inicia la etapa de Declaración de Independencia. En esta etapa, se desencadenan una serie de formularios que se envían a todos los socios de la firma. Cada socio debe completar el formulario, que generalmente incluye cuatro preguntas clave relacionadas con posibles conflictos de interés. Si alguna respuesta implica un conflicto, se puede requerir que se incluyan observaciones adicionales.
	
 - Notificación a la Socia de Riesgo:
	Una vez que todos los formularios han sido completados, el sistema notifica a la Socia de Riesgo sobre la finalización de las declaraciones. La Socia de Riesgo es la responsable de evaluar estas declaraciones y tomar decisiones basadas en la presencia de conflictos potenciales.

2.3 Evaluación de Conflictos: (IRC: Incremental Risk Charge) 
	La Oficial Compliance revisa las declaraciones y determina si hay conflictos significativos que podrían afectar el proyecto. En caso de detectar conflictos, la (Socia de Riesgo) o (Oficial Compliance) PREGUNTAR ESTO SI ES QUE ES LA SOCIA DE RIESGO O LA OFICIAL COMPLIANCE decide si es apropiado continuar con el proyecto o detenerlo para evitar posibles problemas éticos o legales.

2.4 Actualizacion del proyecto: 
	La actualización del proyecto implica la identificación de ganancias y la actualización del precio, seguida de la asignación de riesgo y la aprobación, similar al proceso de clientes. Si la actualización del proyecto queda desierta, los pasos de asignación de riesgo y aprobación no se llevan a cabo.

2.5 **Asignacion del riesgo:
	Después de la aprobación del cliente, el socio responsable procede a la asignación de riesgo para el proyecto específico. Antes de este paso, en casos donde el cliente tiene filiales, matriz u operaciones internacionales, se puede solicitar el documento IRC (International Risk Compliance) como paso previo e intermedio.

2.6 **Aprobacion**:
- Dependiendo del nivel asignado, se activa el flujo de aprobación correspondiente. Se verifica que las aprobaciones coincidan con la clasificación de riesgo para garantizar una revisión adecuada. Una vez que se ha completado el proceso de asignación de riesgo y las aprobaciones necesarias, se genera un registro detallado de la asignación de riesgo para el proyecto.
	- Bajo Riesgo: Se considera que el proyecto presenta un riesgo bajo para la firma. La aprobación recae únicamente en el Socio de Riesgo.
	- Medio Riesgo: Se requiere la aprobación tanto del Socio Líder como del Socio de Riesgo para proyectos con un nivel de riesgo moderado.
	- Alto Riesgo: Proyectos con un riesgo significativo necesitan la aprobación del Socio Líder, del Managing Partner y del Socio de Riesgo.
	
	**Paso adicional en caso de Discrepancia de Asignación de Riesgo:**
	Si la asignación de riesgo propuesta por el socio responsable difiere de la evaluación realizada por la Socia de Riesgo y esta última considera que el riesgo es mayor, se activa un protocolo adicional. En este escenario, la Socia de Riesgo tiene la autoridad para detener el proyecto, ya que su evaluación se considera determinante en caso de discrepancia. Esta medida asegura una alineación crucial entre las percepciones de riesgo del equipo responsable y la evaluación especializada de la Socia de Riesgo, evitando posibles desviaciones y garantizando una gestión coherente de los riesgos asociados con el proyecto.

**FASE III: Planificacion**

La fase de Planificación es una etapa crucial que establece las bases para la ejecución exitosa del proyecto. En este proceso:

**Roles Autorizados para la Planificación:**
    - Cualquier persona con un cargo superior al personal, como supervisores, directores y socios, tiene la autoridad para llevar a cabo la planificación del proyecto.
    - Este enfoque garantiza que la planificación sea realizada por individuos con la experiencia y la capacidad de tomar decisiones estratégicas necesarias para el éxito del proyecto.

**Relación de Horas:**
    - Durante la planificación, se establece una relación detallada de las horas que se asignarán a actividades específicas dentro del proyecto.
    - Se utiliza un sistema de identificación único, como los últimos dígitos del RUT y un correlativo, para crear un ID asociado a la planificación.

**Actividades Asociadas:**
    - La planificación no se limita únicamente a la asignación de horas, sino que también está intrínsecamente asociada a diversas actividades dentro del proyecto.
    - Las actividades pueden incluir desarrollo de software, soporte técnico, pases de producción, análisis de recursos y otras tareas específicas necesarias para el logro de los objetivos del proyecto.
    
**Validación de la Aprobación:**
    - Antes de que la planificación entre en vigor, debe ser aprobada por los responsables jerárquicos, asegurando que las asignaciones de tiempo y recursos estén alineadas con las metas y objetivos del proyecto.
    - Este paso de validación garantiza que la planificación sea coherente con la estrategia general de la firma y que se asignen los recursos de manera eficiente.

**Registro Asociado:**
    - Se genera un registro detallado de la planificación que incluye el ID único, las horas asignadas a cada actividad y la aprobación correspondiente.
    - Este registro sirve como referencia para el seguimiento y control de las horas de trabajo a lo largo del desarrollo del proyecto.

**Iteración y Ajuste:**
    - La planificación no es estática y puede requerir ajustes a medida que el proyecto avanza.
    - Se permite la iteración y ajuste de la planificación según sea necesario para adaptarse a cambios en los requisitos del proyecto o en las circunstancias.

**FASE IV: Registro de Horas**

La fase de Registro de Horas es esencial para monitorear y documentar el tiempo dedicado a las actividades del proyecto. Este proceso involucra varios pasos clave:

**Responsabilidad de Registro:**
    Profesionales involucrados, incluidos supervisores, directores y socios, son responsables de registrar las horas trabajadas en el proyecto. Este enfoque descentralizado permite una captura precisa del tiempo por parte de aquellos directamente involucrados en las tareas.

**Asociación con la Planificación:**
    Las horas registradas deben asociarse directamente con la planificación previamente establecida en la fase anterior. Esto garantiza que las horas se asignen a las actividades específicas identificadas durante la planificación, permitiendo un seguimiento preciso.

**Sistema de Registro:**
    Se utiliza un sistema de registro que permite a los profesionales ingresar las horas trabajadas de manera eficiente y precisa.

**Validación y Aprobación:**
    Las horas registradas pasan por un proceso de validación y aprobación por parte de supervisores o responsables jerárquicos.
    La validación garantiza la precisión de los registros, y la aprobación confirma que el tiempo dedicado está alineado con la planificación y los objetivos del proyecto.

**Correlación con Actividades y Progreso:**
    - Cada registro de horas se correlaciona directamente con las actividades especificadas durante la planificación. Además de contabilizar el tiempo, este proceso proporciona una visión del progreso real en comparación con lo planificado.
    
**Seguimiento Continuo:**
    - El registro de horas no es un evento único; se realiza de manera continua a medida que avanza el proyecto. Se alienta un seguimiento constante para identificar posibles desviaciones en el uso del tiempo y realizar ajustes según sea necesario.

**Registro Histórico:**
    Cada registro de horas se almacena como parte del registro histórico del proyecto.
    Esto facilita el análisis retrospectivo, la generación de informes y la identificación de patrones para futuros proyectos similares.

	Preguntar acerca de lo siguiente para ver si lo podemos agregar a la FASE IV y asi poder identificarlo como ultimo punto:
**Iteración y Mejora:**
	El proceso de registro de horas es susceptible a mejoras continuas. Se fomenta la retroalimentación y la identificación de oportunidades para simplificar y optimizar el proceso de registro en proyectos futuros.

	Tambien preguntar acerca de:
2.3 Evaluación de Conflictos: (IRC: Incremental Risk Charge) 
	La Oficial Compliance revisa las declaraciones y determina si hay conflictos significativos que podrían afectar el proyecto. En caso de detectar conflictos, la (Socia de Riesgo) o (Oficial Compliance) PREGUNTAR ESTO SI ES QUE ES LA SOCIA DE RIESGO O LA OFICIAL COMPLIANCE decide si es apropiado continuar con el proyecto o detenerlo para evitar posibles problemas éticos o legales.
