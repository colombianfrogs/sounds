---
layout: page
title: "Boana platanera"
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
  <h2><i>Boana platanera</i></h2>
  <h4>La Marca, Escalona, Castellanos, Rojas-Runjaic, Crawford, Señaris, Fouquet, Giaretta, and Castroviejo-Fisher, 2021</h4>
  <img src="{{ site.baseurl }}/images/especie_Boana_platanera.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Boana_platanera.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Boana_platanera.png" style="width:15cm;">
</div>

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">

  <p><strong>Disponibles en CSA-IAVH</strong></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34265/IAvH-CSA-34265.wav" target="_blank">IAvH-CSA-34265</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34268/IAvH-CSA-34268.wav" target="_blank">IAvH-CSA-34268</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34272/IAvH-CSA-34272.wav" target="_blank">IAvH-CSA-34272</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34409/IAvH-CSA-34409.wav" target="_blank">IAvH-CSA-34409</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34470/IAvH-CSA-34470.wav" target="_blank">IAvH-CSA-34470</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34639/IAvH-CSA-34639.wav" target="_blank">IAvH-CSA-34639</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36550/IAvH-CSA-36550.wav" target="_blank">IAvH-CSA-36550</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36552/IAvH-CSA-36552.wav" target="_blank">IAvH-CSA-36552</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=1251425" target="_blank">Boana platanera</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Autor_aqui</strong>Bernal, M.H., Montealegre, D.P., Páez, C.A. (2004). Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales 28: 385-390.. 
  <a href="https://doi.org/10.18257/raccefyn.28(108).2004.2135" target="_blank">https://doi.org/10.18257/raccefyn.28(108).2004.2135</a></p>
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios o datos asociados.</i></p>
</div>
