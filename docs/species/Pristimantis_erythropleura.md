---
layout: page
title: "Pristimantis erythropleura"
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
  <h2><i>Pristimantis erythropleura</i></h2>
  <h4>(Boulenger, 1896)</h4>
  <img src="{{ site.baseurl }}/images/especie_Pristimantis_erythropleura.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Pristimantis_erythropleura.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Pristimantis_erythropleura.png" style="width:15cm;">
</div>

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">
  <p><strong>Disponible en IAVH-CSA</strong></p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18275/IAvH-CSA-18275.wav" target="_blank">IAvH-CSA 18275</a>
  </p>
  <p><a href="https://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18276/IAvH-CSA-18276.wav" target="_blank">IAvH-CSA 18276</a>
  </p>
  <p><strong>Disponible en Figshare</strong></p>
  <p>Duarte-Marín, S. (2024). Pristimantis erythropleura. figshare. Media.  
    <a href="https://doi.org/10.6084/m9.figshare.25321690.v2" target="_blank">https://doi.org/10.6084/m9.figshare.25321690.v2</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Duarte-Marín, S. and Arango-Ospina.</strong> 2019. The advertisement call of <i>Pristimantis erythropleura</i> (Boulenger, 1896) (Craugastoridae) from a population in the central Andes of Colombia. <i>The Herpetological Bulletin</i> 148: 33–34.  
  <a href="https://doi.org/10.33256/hb148.3334" target="_blank">https://doi.org/10.33256/hb148.3334.</a></p>

</div>
