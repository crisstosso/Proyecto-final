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

Concurrent Versions System o CVS:
Aplicación informática que implementa un sistema de control de versiones cuyos desarrolladores difunden el sistema bajo la licencia GPL.
CVS utiliza una arquitectura cliente-servidor: un servidor guarda la(s) versión(es) actual(es) del proyecto y su historial. Los clientes se conectan al servidor para sacar una copia completa del proyecto.
Pueden trabajar con la copia y más tarde ingresar sus cambios con comandos GNU.
Los clientes pueden comparar diferentes versiones de archivos, solicitar una historia completa de los cambios, mantener diferentes ramas en un proyecto y actualizar sus copias a la última versión entre otras cosas.

Subversión:
Es una herramienta de control de versiones open source basada en un repositorio cuyo funcionamiento se asemeja enormemente al de un sistema de ficheros. Es software libre bajo una licencia de tipo Apache/BSD.
Utiliza el concepto de revisión para guardar los cambios producidos en el repositorio. Permite al usuario crear, copiar y borrar carpetas y acceder al repositorio a través de redes.


     Sistemas de control de versiones distribuidos

En un DVCS los clientes replican el repositorio al completo, el cual hace las veces a su vez de copia de seguridad de todos los datos.
Esto te permite establecer varios flujos de trabajo que no son posibles en sistemas centralizados, como pueden ser los modelos jerárquicos y colaborar con diversos grupos de gente simultáneamente dentro de un mismo proyecto.

Ejemplos de sistemas de versiones distribuidos:

Git: (Como ya lo hemos tratado en el curso vamos a obviarlo)

Mercurial:
Sistema de control de versiones multiplataforma. Hace uso del lenguaje de programación Python, pero incluye una implementación binaria de diff escrita en C. Escrito originalmente para funcionar sobre GNU/Linuxen la actualidad ha sido adaptado para Windows, Mac OS X y la mayoría de otros sistemas tipo Unix. Mercurial es, sobre todo, un programa para la línea de comandos. 
Todas las operaciones de Mercurial se invocan como opciones dadas a su programa motor, hg .
El código fuente se encuentra disponible bajo los términos de la licencia GNU GPL versión 2, lo que clasifica a Mercurial como software libre.
Al igual que git y Monotone, Mercurial usa resúmenes SHA-1 para identificar revisiones.
Para el acceso a repositorios mediante red, Mercurial usa un protocolo eficiente, basado en HTTP, que persigue reducir el tamaño de los datos a transferir, así como la proliferación de peticiones y conexiones nuevas. Mercurial puede funcionar también sobre ssh, siendo el protocolo muy similar al basado en HTTP.
Mercurial incluye un gran rendimiento y escalabilidad, un desarrollo completamente distribuido sin necesidad de un servidor, gestión robusta de archivos tanto de texto como binarios y capacidades avanzadas de ramificación e integración, todo ello manteniendo sencillez conceptual. Incluye una interfaz web integrada.

Bazaar:
Sistema de control de versiones diseñado para facilitar la contribución en proyectos de software libre y opensource.
Bazaar funciona en GNU/Linux, UNIX, Windows y OS X, está programado en Python y es software libre y parte del proyecto GNU.
La operación básica para el control de versiones distribuido es el branching y merging, por lo que Bazaar está diseñado en gran parte para asegurarse que se puedan hacer branch y merge de forma eficiente entre individuos y equipos, usando ramas locales o remotas. Para los desarrolladores, hay un API de extensión y una suite de plugins para permitirles extender Bazaar, y bzrlib facilita la tarea de incluir la funcionalidad de Bazaar en sus propias aplicaciones GPL.
Puede representar las operaciones de cualquier otro sistema, y hay plugins que permiten leer el log de versiones para un proyecto en Bazaar desde Subversion, Git, CVS y otros proyectos.

