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
  <h2><i>Leucostethus fraterdanieli</i></h2>
  <h4>(Silverstone, 1971)</h4>
  <img src="{{ site.baseurl }}/images/especie_Leucostethus_fraterdanieli.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Leucostethus_fraterdanieli.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Leucostethus_fraterdanieli.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18683/IAvH-CSA-18683.wav" target="_blank">IAvH-CSA-18683</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-30545/IAvH-CSA-30545.wav" target="_blank">IAvH-CSA-30545</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-30546/IAvH-CSA-30546.wav" target="_blank">IAvH-CSA-30546</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34764/IAvH-CSA-34764.wav" target="_blank">IAvH-CSA-34764</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35773/IAvH-CSA-35773.wav" target="_blank">IAvH-CSA-35773</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=787625" target="_blank">Leucostethus fraterdanieli</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Marín, M.C., Molina-Zuluaga, C., Restrepo, A., Cano, E., Daza, J.M. </strong>2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia and the phylogenetic status of Colostethus fraterdanieli. <i>Zootaxa</i> 4461: 359–379. 
  <a href="https://doi.org/10.11646/zootaxa.4464.3.3" target="_blank">10.11646/zootaxa.4461.3.3</a></p>

</div>
