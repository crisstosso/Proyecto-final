#Desallorro de software colaborativo



#�Qu� es el desarrollo de software colaborativo?

Podr�amos definir el desarrollo colaborativo como un modelo de creaci�n de software cuyo c�digo se encuentra disponible en la red que es desarrollado por un conjunto/equipo de personas con diversidad de conocimientos que se comunican a trav�s de internet.
Su augue se inici� en la d�cada de los 90 debido al uso de este modelo de desarrollo para desarrollar Linux.
En contraposici�n a la forma de desarrollo de software tradicional el desallorro de software colaborativo permite una mayor flexibilidad, un desarrollo descentralizado, aplicaci�n del modelo bazar y se presupone que contendr� un menor n�mero de errores debido a que el n�mero de colaboradores es mayor y ser�n capaces de verlos mejor.


#Software Libre

El software libre hace referencia a la capacidad y libertad de los usuarios para realizar cambios en dicho software.
La organizaci�n Free Software Foundation defiende que el software libre se refiere a la seguridad de los usuarios para ejecutar, copiar, distribuir y estudiar el software, e incluso modificarlo y distribuirlo modificado.
Richard Stallman define que un software es "libre" cuando garantiza las siguientes libertades:
Libertad 0: La libertad de usar el programa, con cualquier prop�sito.
Libertad 1: La libertad de estudiar c�mo funciona el programa, y adaptarlo a tus necesidades. El acceso al c�digo fuente es una condici�n previa para esto.
Libertad 2: La libertad de distribuir copias.
Libertad 3: La libertad de mejorar el programa y hacer p�blicas las mejoras a los dem�s, de modo que toda la comunidad se beneficie. El acceso al c�digo fuente es un requisito previo para esto.


#Sistemas de control de versi�n

El sistema de control de versiones es una herramienta que permiter el control y seguimiento de los cambios que han sido realizados en los archivos que componen un proyecto.
El control de versiones permite la comunicaci�n entre comunicaci�n entre los desarrolladores, manejo de los lanzamientos, administraci�n de fallos, estabilidad entre el c�digo y los esfuerzos de desarrollo experimental y atribuci�n o autorizaci�n en los cambios de los desarrolladores.
Se trata de un medio de comunicaci�n donde los cambios suponen las unidades b�sicas de informaci�n.


#Tipos de sistemas de control de versiones

     Sistemas de control de versiones locales

Se trata de una t�cnica muy com�n debido su simpleza, consiste en copiar los archivos a otro directorio, pero tambi�n presenta una alta propensi�n a los errores.
Para intentar solventar esta problem�tica los programadores llevaron a cabo el desarrollo de VCs locales cuyo contenido consist�a en una base de datos simplificada que registraba los cambios que se iban realizando en los archivos de los proyectos.
Mac OS X incluye en rcs, la herramienta de este sistema de control de versiones m�s conocida, la cual va guadando conjuntos de parches.

     Sistemas de control de versiones centralizado

Dichos sistemas tienen un �nico servidor, en el que se encuentran todas las versiones que han sido creadas de los archivos del proyecto, del cual es reponsable un �nico usuario o varios colaboradores el/los cual/cuales tienen el poder de aprobar o no ciertas modificaciones.

Ejemplos de sistemas de versiones centralizado:

Concurrent Versions System o CVS:
Aplicaci�n inform�tica que implementa un sistema de control de versiones cuyos desarrolladores difunden el sistema bajo la licencia GPL.
CVS utiliza una arquitectura cliente-servidor: un servidor guarda la(s) versi�n(es) actual(es) del proyecto y su historial. Los clientes se conectan al servidor para sacar una copia completa del proyecto.
Pueden trabajar con la copia y m�s tarde ingresar sus cambios con comandos GNU.
Los clientes pueden comparar diferentes versiones de archivos, solicitar una historia completa de los cambios, mantener diferentes ramas en un proyecto y actualizar sus copias a la �ltima versi�n entre otras cosas.

Subversi�n:
Es una herramienta de control de versiones open source basada en un repositorio cuyo funcionamiento se asemeja enormemente al de un sistema de ficheros. Es software libre bajo una licencia de tipo Apache/BSD.
Utiliza el concepto de revisi�n para guardar los cambios producidos en el repositorio. Permite al usuario crear, copiar y borrar carpetas y acceder al repositorio a trav�s de redes.


     Sistemas de control de versiones distribuidos

En un DVCS los clientes replican el repositorio al completo, el cual hace las veces a su vez de copia de seguridad de todos los datos.
Esto te permite establecer varios flujos de trabajo que no son posibles en sistemas centralizados, como pueden ser los modelos jer�rquicos y colaborar con diversos grupos de gente simult�neamente dentro de un mismo proyecto.

Ejemplos de sistemas de versiones distribuidos:

Git: Como ya lo hemos tratado en el curso vamos a obviarlo

Mercurial:

Bazaar: