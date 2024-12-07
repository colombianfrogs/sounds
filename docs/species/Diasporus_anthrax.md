---
layout: page
title: "Diasporus anthrax"
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
  <h2><i>Diasporus anthrax</i></h2>
  <h4>Lynch, 2001</h4>
  <img src="{{ site.baseurl }}/images/especie_Diasporus_anthrax.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Diasporus_anthrax.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="figLefr" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Diasporus_anthrax.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tabLefr" class="tabcontent">
  <p>Figshare <a href="https://doi.org/10.6084/m9.figshare.27985289">https://doi.org/10.6084/m9.figshare.27985289</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
<strong>Jiménez-Rivillas, C., L.M. Vargas-Ortíz, J.M. Fang-Ortega, J. Difilippo-Taborda & J.M. Daza.</strong> 2013. Advertisement call of <i>Diasporus anthrax</i> Lynch, 2001 (Anura: Eleutherodactylidae) with comparison to calls of congeneric species. <i>South American Journal of Herpetology</i> 8: 1--4. <a href="http://dx.doi.org/10.2994/SAJH-D-12-00020.1 ">http://dx.doi.org/10.2994/SAJH-D-12-00020.1</a>
