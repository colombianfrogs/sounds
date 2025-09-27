---
layout: page
title: "Rulyrana susatamai"
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
  <h2><i>Rulyrana susatamai</i></h2>
  <h4>(Ruiz-Carranza and Duellman, 1995)</h4>
  <img src="{{ site.baseurl }}/images/especie_Rulyrana_susatamai.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Rulyrana_susatamai.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Rulyrana_susatamai.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34245/IAvH-CSA-34245.wav" target="_blank">IAVH-CSA-34245</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34246/IAvH-CSA-34246.wav" target="_blank">IAVH-CSA-34246</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34247/IAvH-CSA-34247.wav" target="_blank">IAVH-CSA-34247</a></p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">

  <p><strong>Galindo, C.A., Viuche-Lozano, A. and Bernal, M.H.</strong> 2020. The advertisement call of the Colombian endemic glassfrog <i>Rulyrana susatamai</i> (Anura: Centrolenidae). <i>Zootaxa</i>, 4852 (5), 586–589. <a href="https://doi.org/10.11646/zootaxa.4852.5.8" target="_blank">https://doi.org/10.11646/zootaxa.4852.5.8</a></p> 
  
  <p><strong>Mendoza-Henao, A. M., Duarte-Marin, S., and Rada, M.</strong> 2021. Advertisement calls of six glassfrog species in the Colombian Andes, and comments on priorities for future research and conservation. <i>Amphibian and Reptile Conservation</i> 15: 156-171.<a href="https://archive.org/details/biostor-286491" target="_blank">https://archive.org/details/biostor-286491</a></p>

</div>
