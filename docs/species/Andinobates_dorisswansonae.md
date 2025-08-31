---
layout: page
title: "Andinobates dorisswansonae"
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
  <h2><i>Andinobates dorisswansonae</i></h2>
  <h4>(Rueda-Almonacid, Rada, Sánchez-Pacheco, Velásquez-Álvarez, and Quevedo-Gil, 2006)</h4>
  <img src="{{ site.baseurl }}/images/especie_Andinobates_dorisswansonae.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Andinobates_dorisswansonae.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Andinobates_dorisswansonae.png" style="width:15cm;">
</div>

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=135042" target="_blank">iNat</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Brown, J.L., Twomey, E., Amezquita, A., de Souza, M.B., Caldwell, J.P., Lötters, S., von May, R., Melo-Sampaio, P.R., Mejia-Vargas, D., Perez-Peña, P., Pepper, M., Poelman, E.H., Sanchez-Rodriguez, M., Summers, K.</strong> 2011. A taxonomic revision of the Neotropical poison frog genus <i>Ranitomeya</i> (Amphibia: Dendrobatidae). <i>Zootaxa</i> 3083: 1-120. <a href="https://doi.org/10.11646/zootaxa.3083.1.1" target="_blank">https://doi.org/10.11646/zootaxa.3083.1.1</a></p> 
  
  <p><strong>Luna-Mora, V.F., Bernal, M.H., Gallego-Carvajal, O.J., Kahn, T.R.</strong> 2016. Doris Swanson's poison frog Andinobates dorisswansonae Rueda-Almonacid, Rada, Sánchez-Pacheco, Velásquez-Álvarez, and Quevedo-Gil, 2006. In T.R. Kahn, E. La Marca, S. Lötters, J.L. Brown, E. Twomey and A. Amézquita (Eds.), Aposematic poison frogs (Dendrobatidae) of the Andean countries: Bolivia, Colombia, Ecuador, Perú and Venezuela. Tropical field guide series (pp. 268-273). Arlington, USA: Conservation International.</p>
  
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios o datos asociados.</i></p>
</div>
