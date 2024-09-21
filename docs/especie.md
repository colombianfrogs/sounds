---
layout: page
title: "Leucostethus fraterdanieli"
output: html_document
---

<style>
/* Simplified CSS for tabs */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #a2c11c;
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
  <h2><i>Leucostethus fraterdanieli</i> (Silverstone, 1971)</h2>
  <img src="{{ site.baseurl }}/images/especie_Leucostethus_fraterdanieli.png" style="width:15cm;">
</div>

<br><br>

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'EspectroLefr')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'figLefr')">Figura</button>
  <button class="tablinks" onclick="openTab(event, 'tabLefr')">Datos</button>
</div>

<!-- Seccion Espectrograma -->
<div id="EspectroLefr" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/Leucostethus_fraterdanieli.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="figLefr" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/espectrograma_Diasporus_anthrax.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tabLefr" class="tabcontent">
  <p>Descarga <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br>
<strong>Marín, C.M., C. Molina-Zuluaga, A. Restrepo, E. Cano & J.M. Daza.</strong> 2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia with comments on the phylogenetic position of <i>Colostethus fraterdanieli</i>. <i>Zootaxa</i> 4461: 359--380. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a>
