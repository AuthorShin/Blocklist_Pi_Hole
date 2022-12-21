# Blocklist_Pi_Hole
Amdr0meda Blocklist para Pi-hole

En este repositorio encontrarás mis listas de bloqueo personalizadas para el servicio PiHole. (Pi-hole es una aplicación para bloqueo de anuncios y rastreadores en Internet que actúa como un sumidero de DNS). Se pueden llegar a usar en servicios parecidos, AdGuard, Ublock...

Porque estas listas DNS 🔍

Este proyecto pretende unificar las listas de bloqueo de DNS añadiendo mis contribuciones, eliminando falsos positivos, manteniendo estas libres de errores y optimizadas. Te invito a que me ayudes en esta tarea.

Detalles de las listas de bloqueo 📖
Nombre de la lista 	Descripción breve 	Numero de entradas 	RAW
Ads and trackers 	Bloquea anuncios y rastreadores 	675.276 	list
Mining pages 	Bloquea paginas y servicios de mineria 	34.539 	list
Pages with porn 	Bloquea paginas con contenido XXX 	2.048.596 	list
Xiaomi Mi-Fit Amazfit Huami 	Bloqueo COMPLETO de cualquier conexión 	1.076 	list
Windows telemetry 	Bloquea toda la telemetria del SO Windows 	1.012 	list

Pre-requisitos 📋

Unicamente debes tener instalado el servicio Pi-Hole, puedes hacerlo en la terminal mediante el siguiente comando:

curl -sSL https://install.pi-hole.net | bash

Como instalar y utilizar 🔧

En la tabla descriptiva cada lista de bloqueo tiene un enlace RAW, debe copiarse esa dirección y posteriormente añadirla a las listas de bloqueo.

1º Accede al panel de control, en el lateral izquierdo haz click en Group Management y posteriormente en Adlist.

Imagen 1


2º Una vez dentro pegar la url en el campo Address y pulsar el botón Add para añadirla. (Repetir por cada lista que queramos añadir)

Imagen 2


3º En el panel izquierdo haz click en Tools y posteriormente en Update Gravity, dentro de la pestaña pulsar el botón Update.

Imagen 3

Como apoyar las listas de bloqueo 🙋

Tu soporte me ayudará a mantener el proyecto en marcha y sostener unas listas de calidad. Puedes apoyar de múltiples maneras:

    Enviar falsos positivos
    Enviar nuevas url a bloquear
    Compartir con otros usuarios


Autor/es ✒️

Este repositorio es de Amdr0meda, algunas partes de las listas pertenecen a otros usuarios de internet, los cuales permiten la reutilización y modificación, links a continuación:

Descargo de Responsabilidad 🚨

Las listas de bloqueo de Amdr0meda son archivos de hosts para bloquear el acceso a los dominios / sitios web. Si no sabes cómo funciona, por favor lee el apartado de instalación y utilización. Intenta esto bajo tu propio riesgo, no me hago responsable de cualquier daño, pérdida o problema causado.

Licencia 📄

El contenido de la Amdr0meda tiene una licencia de MIT LICENSE.
