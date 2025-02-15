---
layout: page
title: "Atelopus laetissimus"
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
  <h2><i>Atelopus laetissimus</i></h2>
  <h4>Ruiz-Carranza, Ardila-Robayo, and Hernández-Camacho, 1994</h4>
  <img src="{{ site.baseurl }}/images/especie_Atelopus_laetissimus.png" style="width:15cm;">
</div>

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Espectro')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'fig')">Figura</button>
  <button class="tablinks" onclick="openTab(event, 'tab')">Datos</button>
</div>

<!-- Seccion Espectrograma -->
<div id="Espectro" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Atelopus_laetissimus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Atelopus_laetissimus.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tab" class="tabcontent">
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34148/IAvH-CSA-34148.wav">IAVH-CSA-34148</a></p>
  <p>IAVH-CSA-34234 <a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34234/IAvH-CSA-34234.wav">http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34234/IAvH-CSA-34234.wav</a>.</p>
  <p>IAVH-CSA-34235 <a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34235/IAvH-CSA-34235.wav">http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34235/IAvH-CSA-34235.wav</a>.</p>
  <p>IAVH-CSA-34236 <a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34236/IAvH-CSA-34236.wav">http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34236/IAvH-CSA-34236.wav</a>.</p>
  <p>IAVH-CSA-34237 <a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34237/IAvH-CSA-34237.wav">http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34237/IAvH-CSA-34237.wav</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
<strong>Rueda–Solano, L. A., Gonzalez Pérez, Jl., Rivera-Correa, M., CITA Vargas Salinas, F.</strong> 2020. Acoustic signal diversity in the Harlequin Toad <i>Atelopus laetissimus</i> (Anura: Bufonidae). <i>Copeia</i> 108(3): 503–513. <a href="https://doi.org/10.1643/CE-19-251">https://doi.org/10.1643/CE-19-251.</a>
