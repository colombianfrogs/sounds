---
layout: page
title: "Allobates niputidea"
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
  <h2><i>Allobates niputidea</i></h2>
  <h4>Grant, Acosta-Galvis, and Rada, 2007</h4>
  <img src="{{ site.baseurl }}/images/especie_Allobates_niputidea.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Allobates_niputidea.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Allobates_niputidea.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18218/IAvH-CSA-18218.wav">IAVH-CSA-18218</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18222/IAvH-CSA-18222.wav">IAVH-CSA-18222</a></p>
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). <i>Allobates niputidea</i>. Figshare. Media. https://doi.org/10.6084/m9.figshare.27640602.v2 
    <a href="https://doi.org/10.6084/m9.figshare.27640602.v2">URL</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Ospina-L, A.M., Murillo-Bedoya, D., García-Cobos, D., Colón-Piñeiro, Z., Acosta-Galvis, A.R. </strong>2019. The advertisement call of <i>Allobates niputidea</i> (Anura: Aromobatidae). <i>Zootaxa</i> 4656: 196-200. 
  <a href="https://doi.org/10.11646/zootaxa.4656.1.14" target="_blank">https://doi.org/10.11646/zootaxa.4656.1.14</a></p>
</div>
