---
layout: page
title: "Dendropsophus norandinus"
output: html_document
---

<style>
/* Simplified CSS for tabs */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #0092ca;
}
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: background-color 0.3s;
}
.tab button:hover {
  background-color: #ddd;
}
.tab button.active {
  background-color: #ccc;
}
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
.audio-container {
  margin-bottom: 10px;
}
body h1 {
  display: none;
}
</style>

<script>
function openTab(evt, tabName) {
  document.querySelectorAll('.tabcontent').forEach(tab => tab.style.display = "none");
  document.querySelectorAll('.tablinks').forEach(link => link.classList.remove('active'));
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.classList.add('active');
}
</script>

<!-- Species presentation -->
<div style="text-align: center;">
  <h2><i>Dendropsophus norandinus</i></h2>
  <h4>Rivera-Correa and Gutiérrez-Cárdenas, 2012</h4>
  <img src="{{ site.baseurl }}/images/especie_Dendropsophus_norandinus.png" style="width:15cm;">
</div>

#### Señal acústica

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Espectro')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'fig')">Figura</button>
</div>

<!-- Seccion Espectrograma -->
<div id="Espectro" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Dendropsophus_norandinus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Dendropsophus_norandinus.png" style="width:15cm;">
</div>

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">
  <p><strong>Disponibles en Figshare</strong></p>
  <p>NA 
    <a href="NA" target="_blank">NA</a>
  </p>
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="NA" target="_blank">Dendropsophus norandinus</a>
  </p>
  <p><strong>Disponibles en CSA-IAVH</strong></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34766/IAvH-CSA-34766.wav; https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=199727" target="_blank">codigo</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Autor_aqui</strong>Rivera-Correa, M., Gutiérrez-Cárdenas, P.D.A. (2013). Dendropsophus norandinus Rivera-Correa y Gutiérrez-Cárdenas 2012. Catálogo de Anfibios y Reptiles de Colombia 1: 6-9.. 
  <a href="NA" target="_blank">NA</a></p>
  <p><strong>***</strong><i>No existen artículos con sonidos de poblaciones colombianas.</i></p>
</div>
