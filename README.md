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


            <h2 class="Box-title">
              <a href="#readme" data-view-component="true" class="Link--primary">README.md</a>
            </h2>
          </div>
        </div>

          <div data-target="readme-toc.content" class="Box-body px-5 pb-5">
            <article class="markdown-body entry-content container-lg" itemprop="text"><h1 dir="auto"><a id="user-content-amdr0meda-blocklist-para-pi-hole" class="anchor" aria-hidden="true" href="#amdr0meda-blocklist-para-pi-hole"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Amdr0meda Blocklist para Pi-hole</h1>
<p dir="auto">En este repositorio encontrarás mis listas de bloqueo personalizadas para el servicio PiHole. (Pi-hole es una aplicación para bloqueo de anuncios y rastreadores en Internet que actúa como un sumidero de DNS). Se pueden llegar a usar en servicios parecidos, AdGuard, Ublock...
<br><br></p>
<h2 dir="auto"><a id="user-content-porque-estas-listas-dns-" class="anchor" aria-hidden="true" href="#porque-estas-listas-dns-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Porque estas listas DNS <g-emoji class="g-emoji" alias="mag" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f50d.png">🔍</g-emoji></h2>
<p dir="auto">Este proyecto pretende unificar las listas de bloqueo de DNS añadiendo mis contribuciones, eliminando falsos positivos, manteniendo estas libres de errores y optimizadas. Te invito a que me ayudes en esta tarea.
<br><br></p>
<h2 dir="auto"><a id="user-content-detalles-de-las-listas-de-bloqueo-" class="anchor" aria-hidden="true" href="#detalles-de-las-listas-de-bloqueo-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Detalles de las listas de bloqueo <g-emoji class="g-emoji" alias="book" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4d6.png">📖</g-emoji></h2>
<table>
<thead>
<tr>
<th align="center">Nombre de la lista</th>
<th align="center">Descripción breve</th>
<th align="center">Numero de entradas</th>
<th align="center">RAW</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Ads and trackers</td>
<td align="center">Bloquea anuncios y rastreadores</td>
<td align="center">675.276</td>
<td align="center"><a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/Ads%20and%20trackers.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Mining pages</td>
<td align="center">Bloquea paginas y servicios de mineria</td>
<td align="center">34.539</td>
<td align="center"><a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/Mining%20pages.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Pages with porn</td>
<td align="center">Bloquea paginas con contenido XXX</td>
<td align="center">2.048.596</td>
<td align="center"><a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/Porn%20pages.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Xiaomi  Mi-Fit  Amazfit  Huami</td>
<td align="center">Bloqueo COMPLETO de cualquier conexión</td>
<td align="center">1.076</td>
<td align="center"><a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/Xiaomi%20Mi-Fit%20Amazfit%20Huami.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Windows telemetry</td>
<td align="center">Bloquea toda la telemetria del SO Windows</td>
<td align="center">1.012</td>
<td align="center"><a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/Windows%20telemetry.txt" rel="nofollow">list</a></td>
</tr>
</tbody>
</table>
<br>
<h2 dir="auto"><a id="user-content-pre-requisitos-" class="anchor" aria-hidden="true" href="#pre-requisitos-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Pre-requisitos <g-emoji class="g-emoji" alias="clipboard" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4cb.png">📋</g-emoji></h2>
<p dir="auto">Unicamente debes tener instalado el servicio Pi-Hole, puedes hacerlo en la terminal mediante el siguiente comando:</p>
<p dir="auto"><code>curl -sSL https://install.pi-hole.net | bash</code>
<br><br></p>
<h2 dir="auto"><a id="user-content-como-instalar-y-utilizar-" class="anchor" aria-hidden="true" href="#como-instalar-y-utilizar-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Como instalar y utilizar <g-emoji class="g-emoji" alias="wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f527.png">🔧</g-emoji></h2>
<p dir="auto">En la tabla descriptiva cada lista de bloqueo tiene un enlace RAW, debe copiarse esa dirección y posteriormente añadirla a las listas de bloqueo.<br></p>
<p dir="auto">1º	Accede al panel de control, en el lateral izquierdo haz click en <code>Group Management</code> y posteriormente en <code>Adlist</code>.<br><br>
<a target="_blank" rel="noopener noreferrer" href="https://web.archive.org/web/20220612160755/https://github.com/Amdr0meda/Blocklist_Pi_Hole/blob/master/readme_imagenes/group_management.png"><img src="https://web.archive.org/web/20220612160755im_/https://github.com/Amdr0meda/Blocklist_Pi_Hole/raw/master/readme_imagenes/group_management.png" alt="Imagen 1" style="max-width: 100%;"></a><br><br><br>
2º	Una vez dentro pegar la url en el campo <code>Address</code> y pulsar el botón <code>Add</code> para añadirla. (Repetir por cada lista que queramos añadir)<br><br>
<a target="_blank" rel="noopener noreferrer" href="https://web.archive.org/web/20220612160755/https://github.com/Amdr0meda/Blocklist_Pi_Hole/blob/master/readme_imagenes/address_add.png"><img src="https://web.archive.org/web/20220612160755im_/https://github.com/Amdr0meda/Blocklist_Pi_Hole/raw/master/readme_imagenes/address_add.png" alt="Imagen 2" style="max-width: 100%;"></a><br><br><br>
3º	En el panel izquierdo haz click en <code>Tools</code> y posteriormente en <code>Update Gravity</code>, dentro de la pestaña pulsar el botón <code>Update</code>.<br><br>
<a target="_blank" rel="noopener noreferrer" href="https://web.archive.org/web/20220612160755/https://github.com/Amdr0meda/Blocklist_Pi_Hole/blob/master/readme_imagenes/tools_update_gravity_update.png"><img src="https://web.archive.org/web/20220612160755im_/https://github.com/Amdr0meda/Blocklist_Pi_Hole/raw/master/readme_imagenes/tools_update_gravity_update.png" alt="Imagen 3" style="max-width: 100%;"></a><br><br></p>
<h2 dir="auto"><a id="user-content-como-apoyar-las-listas-de-bloqueo-" class="anchor" aria-hidden="true" href="#como-apoyar-las-listas-de-bloqueo-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Como apoyar las listas de bloqueo <g-emoji class="g-emoji" alias="raising_hand" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f64b.png">🙋</g-emoji></h2>
<p dir="auto">Tu soporte me ayudará a mantener el proyecto en marcha y sostener unas listas de calidad. Puedes apoyar de múltiples maneras:</p>
<ul dir="auto">
<li>Enviar falsos positivos</li>
<li>Enviar nuevas url a bloquear</li>
<li>Compartir con otros usuarios</li>
</ul>
<br>
<h2 dir="auto"><a id="user-content-autores-️" class="anchor" aria-hidden="true" href="#autores-️"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Autor/es <g-emoji class="g-emoji" alias="black_nib" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2712.png">✒️</g-emoji></h2>
<p dir="auto">Este repositorio es de Amdr0meda, algunas partes de las listas pertenecen a otros usuarios de internet, los cuales permiten la reutilización y modificación, links a continuación:
<br><br></p>
<h2 dir="auto"><a id="user-content-descargo-de-responsabilidad-" class="anchor" aria-hidden="true" href="#descargo-de-responsabilidad-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Descargo de Responsabilidad <g-emoji class="g-emoji" alias="rotating_light" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6a8.png">🚨</g-emoji></h2>
<p dir="auto">Las listas de bloqueo de Amdr0meda son <code>archivos de hosts</code> para bloquear el acceso a los dominios / sitios web. Si no sabes cómo funciona, por favor lee el apartado de instalación y utilización. Intenta esto bajo tu propio riesgo, no me hago responsable de cualquier daño, pérdida o problema causado.
<br><br></p>
<h2 dir="auto"><a id="user-content-licencia-" class="anchor" aria-hidden="true" href="#licencia-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Licencia <g-emoji class="g-emoji" alias="page_facing_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4c4.png">📄</g-emoji></h2>
<p dir="auto">El contenido de la Amdr0meda tiene una licencia de <a href="https://web.archive.org/web/20220612160755/https://raw.githubusercontent.com/Amdr0meda/Blocklist_Pi_Hole/master/LICENSE" rel="nofollow">MIT LICENSE</a>.
<br><br></p>
</article>
          </div>
      </div>

  </readme-toc>


</div>
  <div data-view-component="true" class="Layout-sidebar">      

      <div class="BorderGrid BorderGrid--spacious" data-pjax>
        <div class="BorderGrid-row hide-sm hide-md">
          <div class="BorderGrid-cell">
            <h2 class="mb-3 h4">About</h2>

    <p class="f4 my-3">
      En este repositorio encontrarás mis listas de bloqueo personalizadas para el servicio PiHole.. Se pueden llegar a usar en servicios parecidos (AdGuard, Ublock)
    </p>
    <div class="my-3 d-flex flex-items-center">
      <svg aria-hidden="true" height="16" viewbox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-link flex-shrink-0 mr-2">
    <path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path>
</svg>
      <span class="flex-auto min-width-0 css-truncate css-truncate-target width-fit">
        <a title="https://git.io/JzpnW" role="link" target="_blank" rel="noopener noreferrer nofollow" class="text-bold" href="https://web.archive.org/web/20220612160755/https://git.io/JzpnW">git.io/jzpnw</a>
      </span>
    </div>

  <h3 class="sr-only">Topics</h3>
  <div class="my-3">
      <div class="f6">
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:dns" href="/web/20220612160755/https://github.com/topics/dns" title="Topic: dns" data-view-component="true" class="topic-tag topic-tag-link">
  dns
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:privacy" href="/web/20220612160755/https://github.com/topics/privacy" title="Topic: privacy" data-view-component="true" class="topic-tag topic-tag-link">
  privacy
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:blocklist" href="/web/20220612160755/https://github.com/topics/blocklist" title="Topic: blocklist" data-view-component="true" class="topic-tag topic-tag-link">
  blocklist
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:telemetry" href="/web/20220612160755/https://github.com/topics/telemetry" title="Topic: telemetry" data-view-component="true" class="topic-tag topic-tag-link">
  telemetry
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:pi-hole" href="/web/20220612160755/https://github.com/topics/pi-hole" title="Topic: pi-hole" data-view-component="true" class="topic-tag topic-tag-link">
  pi-hole
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:adblock" href="/web/20220612160755/https://github.com/topics/adblock" title="Topic: adblock" data-view-component="true" class="topic-tag topic-tag-link">
  adblock
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:xiaomi" href="/web/20220612160755/https://github.com/topics/xiaomi" title="Topic: xiaomi" data-view-component="true" class="topic-tag topic-tag-link">
  xiaomi
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:hostsfile" href="/web/20220612160755/https://github.com/topics/hostsfile" title="Topic: hostsfile" data-view-component="true" class="topic-tag topic-tag-link">
  hostsfile
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:adserver" href="/web/20220612160755/https://github.com/topics/adserver" title="Topic: adserver" data-view-component="true" class="topic-tag topic-tag-link">
  adserver
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:blocklists" href="/web/20220612160755/https://github.com/topics/blocklists" title="Topic: blocklists" data-view-component="true" class="topic-tag topic-tag-link">
  blocklists
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:privacy-protection" href="/web/20220612160755/https://github.com/topics/privacy-protection" title="Topic: privacy-protection" data-view-component="true" class="topic-tag topic-tag-link">
  privacy-protection
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:pihole-blocklists" href="/web/20220612160755/https://github.com/topics/pihole-blocklists" title="Topic: pihole-blocklists" data-view-component="true" class="topic-tag topic-tag-link">
  pihole-blocklists
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:amazfit" href="/web/20220612160755/https://github.com/topics/amazfit" title="Topic: amazfit" data-view-component="true" class="topic-tag topic-tag-link">
  amazfit
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:porn-block" href="/web/20220612160755/https://github.com/topics/porn-block" title="Topic: porn-block" data-view-component="true" class="topic-tag topic-tag-link">
  porn-block
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:pihole-ads-list" href="/web/20220612160755/https://github.com/topics/pihole-ads-list" title="Topic: pihole-ads-list" data-view-component="true" class="topic-tag topic-tag-link">
  pihole-ads-list
</a>
      <a data-ga-click="Topic, repository page" data-octo-click="topic_click" data-octo-dimensions="topic:mifit" href="/web/20220612160755/https://github.com/topics/mifit" title="Topic: mifit" data-view-component="true" class="topic-tag topic-tag-link">
  mifit
</a>
  </div>

  </div>

  <h3 class="sr-only">Resources</h3>
  <div class="mt-2">
    <a class="Link--muted" data-analytics-event="{&quot;category&quot;:&quot;Repository Overview&quot;,&quot;action&quot;:&quot;click&quot;,&quot;label&quot;:&quot;location:sidebar;file:readme&quot;}" href="#readme">
      <svg aria-hidden="true" height="16" viewbox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book mr-2">
    <path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path>
</svg>
      Readme
</a>  </div>

<h3 class="sr-only">License</h3>
  <div class="mt-2">
    <a href="/web/20220612160755/https://github.com/Amdr0meda/Blocklist_Pi_Hole/blob/master/LICENSE" class="Link--muted" data-analytics-event="{&quot;category&quot;:&quot;Repository Overview&quot;,&quot;action&quot;:&quot;click&quot;,&quot;label&quot;:&quot;location:sidebar;file:license&quot;}">
      <svg aria-hidden="true" height="16" viewbox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-law mr-2">
    <path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path>
</svg>
     MIT license
    </a>
  </div>

