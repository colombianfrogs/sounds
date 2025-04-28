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

#### Señal acústica

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Espectro')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'fig')">Figura</button>
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

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">
  <p><strong>Disponibles en CSA-IAVH</strong></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34148/IAvH-CSA-34148.wav">IAVH-CSA-34148</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34149/IAvH-CSA-34149.wav">IAVH-CSA-34149</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34150/IAvH-CSA-34150.wav">IAVH-CSA-34150</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34151/IAvH-CSA-34151.wav">IAVH-CSA-34151</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34152/IAvH-CSA-34152.wav">IAVH-CSA-34152</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34153/IAvH-CSA-34153.wav">IAVH-CSA-34153</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34154/IAvH-CSA-34154.wav">IAVH-CSA-34154</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34155/IAvH-CSA-34155.wav">IAVH-CSA-34155</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34156/IAvH-CSA-34156.wav">IAVH-CSA-34156</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34157/IAvH-CSA-34157.wav">IAVH-CSA-34157</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34158/IAvH-CSA-34158.wav">IAVH-CSA-34158</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34159/IAvH-CSA-34159.wav">IAVH-CSA-34159</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34160/IAvH-CSA-34160.wav">IAVH-CSA-34160</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34161/IAvH-CSA-34161.wav">IAVH-CSA-34161</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34162/IAvH-CSA-34162.wav">IAVH-CSA-34162</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34163/IAvH-CSA-34163.wav">IAVH-CSA-34163</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34164/IAvH-CSA-34164.wav">IAVH-CSA-34164</a></p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p>Rueda–Solano, L. A., Gonzalez Pérez, Jl., Rivera-Correa, M., and Vargas Salinas, F. 2020. Acoustic signal diversity in the Harlequin Toad <i>Atelopus laetissimus</i> (Anura: Bufonidae). <i>Copeia</i> 108(3): 503–513. https://doi.org/10.1643/CE-19-251. 
  <a href="https://doi.org/10.1643/CE-19-251" target="_blank">Link</a></p>
</div>
