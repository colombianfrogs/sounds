---
layout: page
title: "Craugastor metriosistus"
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
  <h2><i>Craugastor metriosistus</i></h2>
  <h4>Ospina-Sarria, Angarita-Sierra, and Pedroza-Banda, 2015</h4>
  <img src="{{ site.baseurl }}/images/especie_Craugastor_metriosistus.png" style="width:15cm;">
</div>

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'EspectroLefr')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'figLefr')">Figura</button>
  <button class="tablinks" onclick="openTab(event, 'tabLefr')">Datos</button>
</div>

<!-- Seccion Espectrograma -->
<div id="EspectroLefr" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Craugastor_metriosistus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="figLefr" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Craugastor_metriosistus.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tabLefr" class="tabcontent">
  <p>Figshare <a href="https://doi.org/10.6084/m9.figshare.27798534.v3">https://doi.org/10.6084/m9.figshare.27798534.v3</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
<strong>Ospina-Sarria, J. J., Angarita-Sierra, T., & Pedroza-Banda, R.</strong> 2015. A new species of <i>Craugastor</i> (Anura: Craugastoridae) from the Magdalena River Valley, Colombia, with evaluation of the characters used to identify species of the <i>Craugastor fitzingeri</i> group. <i>South American Journal of Herpetology</i> 10: 1653--177. <a href="http://dx.doi.org/10.2994/SAJH-D-14-00014.1 ">http://dx.doi.org/10.2994/SAJH-D-14-00014.1</a>
