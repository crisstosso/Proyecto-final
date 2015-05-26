#Desallorro colaborativo

#Desallorro de software colaborativo

#¿Qué es el desarrollo de software colaborativo?

Podríamos definir el desarrollo colaborativo como un modelo de creación de software cuyo código se encuentra disponible en la red que es desarrollado por un conjunto/equipo de personas con diversidad de conocimientos que se comunican a través de internet.
Su augue se inició en la década de los 90 debido al uso de este modelo de desarrollo para desarrollar Linux.
En contraposición a la forma de desarrollo de software tradicional el desallorro de software colaborativo permite una mayor flexibilidad, un desarrollo descentralizado, aplicación del modelo bazar y se presupone que contendrá un menor número de errores debido a que el número de colaboradores es mayor y serán capaces de verlos mejor.
 
#Software Libre

El software libre hace referencia a la capacidad y libertad de los usuarios para realizar cambios en dicho software. 
La organización Free Software Foundation defiende que el software libre se refiere a la seguridad de los usuarios para ejecutar, copiar, distribuir y estudiar el software, e incluso modificarlo y distribuirlo modificado.
Richard Stallman define que un software es "libre" cuando garantiza las siguientes libertades:
Libertad 0: La libertad de usar el programa, con cualquier propósito.
Libertad 1: La libertad de estudiar cómo funciona el programa, y adaptarlo a tus necesidades. El acceso al código fuente es una condición previa para esto.
Libertad 2: La libertad de distribuir copias.
Libertad 3: La libertad de mejorar el programa y hacer públicas las mejoras a los demás, de modo que toda la comunidad se beneficie. El acceso al código fuente es un requisito previo para esto.

#Sistemas de control de versión

El sistema de control de versiones es una herramienta que permiter el control y seguimiento de los cambios que han sido realizados en los archivos que componen un proyecto.
El control de versiones permite la comunicación entre comunicación entre los desarrolladores, manejo de los lanzamientos, administración de fallos, estabilidad entre el código y los esfuerzos de desarrollo experimental y atribución o autorización en los cambios de los desarrolladores.
Se trata de un medio de comunicación donde los cambios suponen las unidades básicas de información.

#Tipos de sistemas de control de versiones

  Sistemas de control de versiones locales

Se trata de una técnica muy común debido su simpleza, consiste en copiar los archivos a otro directorio, pero también presenta una alta propensión a los errores.
Para intentar solventar esta problemática los programadores llevaron a cabo el desarrollo de VCs locales cuyo contenido consistía en una base de datos simplificada que registraba los cambios que se iban realizando en los archivos de los proyectos.
Mac OS X incluye en rcs, la herramienta de este sistema de control de versiones más conocida, la cual va guadando conjuntos de parches.

  Sistemas de control de versiones centralizado

Dichos sistemas tienen un único servidor, en el que se encuentran todas las versiones que han sido creadas de los archivos del proyecto, del cual es reponsable un único usuario o varios colaboradores el/los cual/cuales tienen el poder de aprobar o no ciertas modificaciones.

Ejemplos de sistemas de versiones centralizado: 

[Concurrent Versions System o CVS]:  


Aplicación informática que implementa un sistema de control de versiones cuyos desarrolladores difunden el sistema bajo la licencia GPL.
CVS utiliza una arquitectura cliente-servidor: un servidor guarda la(s) versión(es) actual(es) del proyecto y su historial. Los clientes se conectan al servidor para sacar una copia completa del proyecto. 
Pueden trabajar con la copia y más tarde ingresar sus cambios con comandos GNU.
Los clientes pueden comparar diferentes versiones de archivos, solicitar una historia completa de los cambios, mantener diferentes ramas en un proyecto y actualizar sus copias a la última versión entre otras cosas.

[Subversión]: 


Es una herramienta de control de versiones open source basada en un repositorio cuyo funcionamiento se asemeja enormemente al de un sistema de ficheros. Es software libre bajo una licencia de tipo Apache/BSD.
Utiliza el concepto de revisión para guardar los cambios producidos en el repositorio. Permite al usuario crear, copiar y borrar carpetas y acceder al repositorio a través de redes.

  Sistemas de control de versiones distribuidos

En un DVCS los clientes replican el repositorio al completo, el cual hace las veces a su vez de copia de seguridad de todos los datos.
Esto te permite establecer varios flujos de trabajo que no son posibles en sistemas centralizados, como pueden ser los modelos jerárquicos y colaborar con diversos grupos de gente simultáneamente dentro de un mismo proyecto.

Ejemplos de sistemas de versiones distribuidos:

Git: Como ya lo hemos tratado en el curso vamos a obviarlo

[Mercurial]:


Sistema de control de versiones multiplataforma. Hace uso del lenguaje de programación Python, pero incluye una implementación binaria de diff escrita en C. Escrito originalmente para funcionar sobre GNU/Linuxen la actualidad ha sido adaptado para Windows, Mac OS X y la mayoría de otros sistemas tipo Unix. Mercurial es, sobre todo, un programa para la línea de comandos. 
Todas las operaciones de Mercurial se invocan como opciones dadas a su programa motor, hg .
El código fuente se encuentra disponible bajo los términos de la licencia GNU GPL versión 2, lo que clasifica a Mercurial como software libre.
Al igual que git y Monotone, Mercurial usa resúmenes SHA-1 para identificar revisiones.
Para el acceso a repositorios mediante red, Mercurial usa un protocolo eficiente, basado en HTTP, que persigue reducir el tamaño de los datos a transferir, así como la proliferación de peticiones y conexiones nuevas. Mercurial puede funcionar también sobre ssh, siendo el protocolo muy similar al basado en HTTP.
Mercurial incluye un gran rendimiento y escalabilidad, un desarrollo completamente distribuido sin necesidad de un servidor, gestión robusta de archivos tanto de texto como binarios y capacidades avanzadas de ramificación e integración, todo ello manteniendo sencillez conceptual. Incluye una interfaz web integrada.

[Bazaar]:


Sistema de control de versiones diseñado para facilitar la contribución en proyectos de software libre y opensource.
Bazaar funciona en GNU/Linux, UNIX, Windows y OS X, está programado en Python y es software libre y parte del proyecto GNU.
La operación básica para el control de versiones distribuido es el branching y merging, por lo que Bazaar está diseñado en gran parte para asegurarse que se puedan hacer branch y merge de forma eficiente entre individuos y equipos, usando ramas locales o remotas. Para los desarrolladores, hay un API de extensión y una suite de plugins para permitirles extender Bazaar, y bzrlib facilita la tarea de incluir la funcionalidad de Bazaar en sus propias aplicaciones GPL.
Puede representar las operaciones de cualquier otro sistema, y hay plugins que permiten leer el log de versiones para un proyecto en Bazaar desde Subversion, Git, CVS y otros proyectos.

#Otras Herramientas de trabajo colaborativo

[Mindomo](https://www.mindomo.com/es/)

Se trata de una herramienta que permite realizar mapas mentales tanto en equipo como en solitario, en línea o desde el escritorio, con esto se puede diseñar el funcionamiento de servicios o procesos de forma visual, o definir un plan estratégico, una lluvia de ideas, etc. Tiene una versión gratuita limitada y versiones empresariales de pago


[Mantis](http://www.mantisbt.org/)

Es una herramienta que permite realizar el seguimiento de incidencias. Principalmente orientado al seguimiento de bugs en el desarrollo de aplicaciones, gracias a su sistema de tickets al detectar fallos. Corre sobre la combinación Apache+PHP+MySQL.


[Basecamp](https://basecamp.com/)

Es una herramienta de gestión que incluye gestión documental, de tareas, foros de debate, notificaciones y avisos por correo. Dispone de gran cantidad de "addons" oficiales y creados por la comunidad. No cuenta con versión gratuita.


[Dotproject](http://dotproject.net/)

Esta aplicación sigue el modelo clásico de gestión de proyectos, es decir, división en subproyectos, asignación de recursos, gestión económica, representación de un diagrama de Gantt,etc. Se trata de una aplicación web.


[Redmine](http://www.redmine.org/)

Es una herramienta para la gestión de proyectos y el seguimiento de errores escrita usando Ruby on Rails. Incluye calendario y diagramas de Gantt para la visualización del tiempo de los proyectos. También cuenta con una Wiki colaborativa para cada proyecto, notificaciones por correo electrónico, integración SCM,etc. Software libre y de código abierto.


[The Dead Line](https://the-deadline.appspot.com/login)

Es una herramienta orientada a la gestión de tareas, puesto que presenta las mismas como una lista de cosas que hacer ("to do list"), sobre la que se asignarán las tareas a los miembros del equipo.


[Mikogo](http://www.mikogo.es/)

Permite montar presentaciones en línea, reuniones o conferencias con hasta 25 participantes de forma gratuita, en las que se permite compartir escritorio, ceder el control de la reunión, transferir archivos o utilizar una pizarra virtual.


[Do.com](https://do.com/)

Software creado para incluir proyectos y tareas desde dispositivos móviles. Permite trabajar con archivos, notas, traeas, perfiles, fechas o actualizaciones en tiempo real. Cuenta con un diseño muy intuitivo realizado en HTML5.


[Wunderlist](https://www.wunderlist.com/es/)

Se trata de un gestor de tareas y proyectos de una forma mucho más social para llevar proyectos con tus contactos. Permite crear diferentes espacios para cada uno de los proyectos con un escritorio que mostrará toda la actividad e información del espacio en cuestión. Posee una interfaz muy cuidada y sincronización de tareas en la nube.


[Project-Open](http://www.project-open.com/)

Es un conjunto de soluciones ERP open source para la gestión empresarial de proyectos. Se subdivide en diversos proyectos:
- project-translation: para agencias de traducción-
- project-consulting: para consultoras con intranet de plataforma colaborativa.
- project-agency: para agencias de publicidad e Internet.
- project-lifecycle: para laboratorios I+D, ingeniería y empresas de producción industrial.
Cuenta con un almacén de ficheros, sistema Wiki integrado, foro colaborativo, Workflow, gestión financiera, Intranet colaborativa, diagramas de Gantt. Es un referente gracias a su amplia comunidad.


[Trac](http://trac.edgewall.org/)

Es una herramienta para la gestión de proyectos y el seguimiento de errores escrita en Python. Permite enlazar información entre una base de datos de errores de software, un sistema de control de versiones y el contenido de una Wiki, sirve como interfaz web de un sistema de control de versiones, posee línea de tiempo con avances de los proyectos, utiliza un sitema de plantillas web propio. Software libre y de código abierto.


[TeamLab](https://www.onlyoffice.com/es/)

Es una plataforma de colaboración y gestión de proyectos bajo el paradigma SaaS("Software as a Service"). Ofrece calendario, gestión de documentos, o un CRM("Customer relationship management como sistema multifuncional para mejorar las relaciones con clientes y aumentar ventas. Permite crear un portal corporativo en minutos desde su web o descargar el código y configurar manualmente el servidor y mantenerlo por cuenta propia. Software gratuito y de código abierto.


[eGroupWare](http://www.egroupware.org/start.html)

Es una solución de trabajo en grupo vía web escrita en PHP usando bases de datos. Cuenta con calendario, gestor de contactos con base de datos, cliente de correo webmail integrado, una aplicación para tareas y notas, gestor de recursos, gestor de archivos, sistema de autor de web con listas de control de acceso, seguimiento de proyecto integrado con el gestor de proyectos, seguimiento de errores, Wiki,etc. Es de código abierto.


[Open Atrium](http://openatrium.com/#!/)

Es una herramienta que incluye una Wiki, un gestor documental y un gestor de incidencias. Altamente personalizable, construida sobre Apache, PHP, MySQL y un core de Drupal, permite crear distintos grupos de trabajo y añadir usuarios a los mismos. Dentro de cada grupo se dispone de distintas características como calendario, gestor de incidencias, documentos organizados en libros, blogs, un escritorio y un muro en el que compartir enlaces o ideas. Es de código abierto.


[Google Docs](https://docs.google.com)

Es un sistema en línea de edición de documentos. Permite crear y compartir fácilmente trabajo en la red: hojas de cálculo, documentos, presentaciones, formas y dibujos. Además, estas herramientas dejan que todo el mundo pueda trabajar de forma simultánea en el mismo archivo.


[Google Calendar](https://www.google.com/calendar/)

Es una aplicación de calendario compartido que permite establecer distintos tipos de acceso. Además, posibilita la gestión compartida de agendas, se integra con el correo electrónico y puede funcionar con otras aplicaciones calendario.


[Google Sites](https://sites.google.com/)
Es una herramienta que permite crear una página web, por ejemplo, para intranets y equipos, donde centralizar documentos, presentaciónes y otros archivos, así como recibir alertas de las novedades y documentos subidos al portal.


[Remember the milk](https://www.rememberthemilk.com/)

Es una aplicación web que permite administrar listas de tareas y su tiempo de gestión desde cualquier ordenador o dispositivo móvil. Cuenta con clasificación de tareas mediante etiquetas, compartición de las mismas y envío de recordatorio de tareas mediante SMS y aplicaciones de mensajería instantánea.


[Join.me](https://www.join.me/)

Es una herramienta para compartir el contenido de la pantalla de un ususario con otros. Permite mantener reuniones con audioconferencia, chats con todos los participantes o con grupos, ver los participantes de la sesión, permitiendo ceder el control de la pantalla, enviarle un archivo o expulsarlo.


[EVLY](http://www.evly.com/)

Se trata de una plataforma para crear webs de crowsourcing siguiendo un esquema predeterminado:
- Creación de resúmenes
- Invitación de participantes
- Revisión de ideas
- Implementación de las ideas generadas
