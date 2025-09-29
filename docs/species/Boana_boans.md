---
layout: page
title: "Boana boans"
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
  <h2><i>Boana boans</i></h2>
  <h4>(Linnaeus, 1758)</h4>
  <img src="{{ site.baseurl }}/images/especie_Boana_boans.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Boana_boans.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Boana_boans.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18225/IAvH-CSA-18225.wav" target="_blank">IAvH-CSA-18225</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18226/IAvH-CSA-18226.wav" target="_blank">IAvH-CSA-18226</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18227/IAvH-CSA-18227.wav" target="_blank">IAvH-CSA-18227</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18228/IAvH-CSA-18228.wav" target="_blank">IAvH-CSA-18228</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18688/IAvH-CSA-18688.wav" target="_blank">IAvH-CSA-18688</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18699/IAvH-CSA-18699.wav" target="_blank">IAvH-CSA-18699</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18702/IAvH-CSA-18702.wav" target="_blank">IAvH-CSA-18702</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18720/IAvH-CSA-18720.wav" target="_blank">IAvH-CSA-18720</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34365/IAvH-CSA-34365.wav" target="_blank">IAvH-CSA-34365</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34370/IAvH-CSA-34370.wav" target="_blank">IAvH-CSA-34370</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34371/IAvH-CSA-34371.wav" target="_blank">IAvH-CSA-34371</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34372/IAvH-CSA-34372.wav" target="_blank">IAvH-CSA-34372</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34373/IAvH-CSA-34373.wav" target="_blank">IAvH-CSA-34373</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34375/IAvH-CSA-34375.wav" target="_blank">IAvH-CSA-34375</a></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34384/IAvH-CSA-34384.wav" target="_blank">IAvH-CSA-34384</a></p>
 
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Boana boans. Figshare. Media.<a href="https://doi.org/10.6084/m9.figshare.27642186.v1" target="_blank">https://doi.org/10.6084/m9.figshare.27642186.v1</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=555086" target="_blank">Boana boans</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>***</strong><i>No existen artículos con sonidos de poblaciones colombianas</i></p>
</div>
