---
layout: page
title: "Andinobates opisthomelas"
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
  <h2><i>Andinobates opisthomelas</i></h2>
  <h4>(Boulenger, 1899)</h4>
  <img src="{{ site.baseurl }}/images/especie_Andinobates_opisthomelas.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Andinobates_opisthomelas.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Andinobates_opisthomelas.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34760/IAvH-CSA-34760.wav" target="_blank>IAVH-CSA-34760</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34762/IAvH-CSA-34762.wav" target="_blank>IAVH-CSA-34762</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-3/IAvH-CSA-34763.wav" target="_blank>IAVH-CSA-34763</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34765/IAvH-CSA-34765.wav" target="_blank>IAVH-CSA-34765</a></p>

  <p><strong>Disponibles en </strong><a href="https://www.inaturalist.org/observations?sounds&taxon_id=135045" target="_blank>iNaturalist</a></p>
  
  <p><a href="https://static.inaturalist.org/sounds/48803.mp3?1571616401" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/327127.mp3?1636399406" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/765147.mp3?1688976288" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1122209.mp3?1720220343" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1207345.wav?1726941892" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1208549.wav?1727025029" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1208550.wav?1727025058" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1208551.wav?1727025148" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1208552.wav?1727025377" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1208572.wav?1727026112" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1211316.wav?1727299777" target="_blank>iNat_obs_</a></p>
  <p><a href="https://static.inaturalist.org/sounds/1212155.wav?1727372844" target="_blank>iNat_obs_</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Brown, J.L., Twomey, E., Amezquita, A., de Souza, M.B., Caldwell, J.P., Lötters, S., von May, R., Melo-Sampaio, P.R., Mejia-Vargas, D., Perez-Peña, P., Pepper, M., Poelman, E.H., Sanchez-Rodriguez, M., Summers, K. </strong>2011. A taxonomic revision of the Neotropical poison frog genus <i>Ranitomeya</i> (Amphibia: Dendrobatidae). <i>Zootaxa</i> 3083: 1-120. <a href="https://doi.org/10.11646/zootaxa.3083.1.1" target="_blank">https://doi.org/10.11646/zootaxa.3083.1.1</a></p>
  
  <p><strong>Rivera-Correa, M., Urbina, J., Galeano, S.P., Kahn, T.R. </strong>2016b. Andean poison frog <i>Andinobates opisthomelas</i> Boulenger, 1899. In T.R. Kahn, E. La Marca, S. Lötters, J.L. Brown, E. Twomey, and A. Amézquita (Eds.), Aposematic poison frogs (Dendrobatidae) of the Andean countries: Bolivia, Colombia, Ecuador, Perú and Venezuela. Tropical field guide series (pp. 284-289). Arlington, USA: Conservation International.</p>
  
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios y datos asociados.</i></p>
</div>
