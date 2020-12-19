# FlujoModerno de Desarrollo de Software con CodeStream

- Definición de flujo: Es cuando estas trabajando y no sientes el paso del tiempo. Es estar tan concentrado que todo lo demás no importa.
Workflow o flujo de trabajo: Es una secuencia de tareas organizadas de tal manera que tengas mejor eficiencia.
Los ciclos de vida en software: Cascada y Moderno

- El ciclo en cascada el software es tratado en cada departamento de forma separada y va pasando de uno en uno.
El ciclo moderno se habla que todos los departamentos están conectados de tal manera que trabajan uno con otro haciendo un flujo de trabajo.

- El principio shift left es conocido en DevOps que moviendo el enfoque de la calidad a la izquierda para comprimir el ciclo se logra mejor calidad y mejor rendimiento.
Esto se hace porque al corregir errores en producción en 100 veces más caro que hacerlo al principio del diseño.

- Puedes comenzar con el flujo moderno implementandolo en ti mismo, conforme vas avanzando, podrás aplicarlo en tu equipo añadiendo feedback request y asi todos se beneficiarán.
Cuando varios equipos usen el flujo moderno, podrás llevarlo a la organización beneficiándolo incorporando el área administrativa, la documentación y la parte de analítica.

- En la colaboración tradicional se hace una revisión al código al terminar el desarrollo y en la colaboración moderna se hacen muchas revisiones de código pequeñas a medida que se va desarrollando el proyecto.
- Google atomiza la revisión de códigos para que dichas revisiones se tome un tiempo menos de 24 horas, teniendo un tiempo promedio de revisión de todo el ciclo en menos de 4 horas.

- Lo que se busca al integrar las herramientas en el editor de texto es** evitar el cambio de contexto** lo que esto significa es no cambiar de ventanas, porque esto puede ocasionar una distracción ademas se busca el** reducir pasos** para eficientar el tiempo para realizar las tareas.
  - Los beneficios son:
  - Ahorrar tiempo
  - Reducir Distracciones
  - Tener acceso a el código en todo momento
  - Mejorar la calidad
  - Mejorar la comunicación
  - No tener que cambiar de herramientas
 
- Beneficios al integrar GitHub en tu editor:
  - Eliminación del cambio de contexto.
  - Cambiar a una rama en un solo clic.
  - Ejecutar una compilación durante la revisión.
  - Saltar a la definición.
  - Utilizar tus atajos de teclado, temas y personalizaciones preferidos.
  - El contexto completo de tu repositorio.
  - Comentar en cualquier parte del repositorio relacionado con la revisión del código.
  - La herramienta 'diff' nativa de tu editor.
  - El contexto completo de tu repositorio.
  - Agregar comentarios en cualquier parte del repositorio relacionados con cualquier revisión de código.
  
- Eficiencia del Pull Request (PR) en tu editor
  - Agregar comentarios.
  - Crear issues en Asana.
  - Crear Feedback Request.
  - Crear un Pull Request.
  
- Feedback Request
  - Relacionado con el concepto de PR.
  - Se reaiza antes en el flujo para poder atomizar la colaboración.
  - Permite pedir feedback, es decir, comentarios sobre código en cualquier estado de tu repositorio.
  - Es mucho más fácil para el revisor.
  
- Principios de colaboración **Shift Left**
  - Antes mejor que después.
  - Colaboración atomizada.
  - Más consulta que aprobación.
  - Reducir fricción administrativa.
  - Compartir conocimientos.
 
- Ventajas de tener un issue tracker integrado
  - Agregar un ticket mientras escribes o revisas código.
  - Conectar el ticket directamente al código.
  - Notificar a la persona indicada que hay un ticket y dirigirlo al lugar correcto.
  - No tener que cambiar de aplicación o contexto.
  - Crear un registro de los tickets asociados al código mismo.

- Code chat
  - El Code Chat es mensajería de equipo diseñada para trabajar con líneas y bloques de código.
  - Detecta cambios y diferencias en distintas versiones del mismo bloque.
  - Contiene la meta-información para evolucionar con el código.
  - Se integra con Slack, Pull Request, Jira, Asana.
  - Se transforma en documentación.
  - Proposito
    - Colaboración informal atomizada.
    - Permite hacer preguntas y sugerencias sobre cualquier parte del código.
    - Conecta distintas partes del flujo.
    - Conecta distintos bloques de código.
    - Documenta el código.
    - Explica decisiones ya tomadas.
  
 - Codemarks
  - Cada vez que se crea una unidad de comunicación en CodeStream se crea un *codemark*.
  - Un codemark es un enlace entre la información sobre el código (metadata) y el bloque de código al que se refiere.
  - Un codemark puede ser un mensaje, un issue o un permalink (enlace permanente).
  - Codemarks son exportables.
  
- Documentación On Demand
  - En lugar de pensar qué documentar, fomentar las preguntas.
  - En lugar de esperar al PR, fomentar las sugerencias.
  - En lugar de armar documentos de inducción (onboarding), dejar que el nuevo desarrollador explique lo que necesita.
