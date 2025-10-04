---
layout: page
title: "Dendrobates truncatus"
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
  <h2><i>Dendrobates truncatus</i></h2>
  <h4>(Cope, 1861)</h4>
  <img src="{{ site.baseurl }}/images/especie_Dendrobates_truncatus.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Dendrobates_truncatus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Dendrobates_truncatus.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34978/IAvH-CSA-34978.wav" target="_blank">IAvH-CSA-34978</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35089/IAvH-CSA-35089.wav" target="_blank">IAvH-CSA-35089</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=21116" target="_blank">Dendrobates truncatus</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  
  <p><strong>Erdtmann, L., Amezquita, A.</strong> (2009). Differential evolution of advertisement call traits in dart‐poison frogs (Anura: Dendrobatidae). Ethology 115: 801-811. 
   <a href="https://doi.org/10.1111/j.1439-0310.2009.01673.x" target="_blank">https://doi.org/10.1111/j.1439-0310.2009.01673.x</a></p>
  
  <p><strong>Gualdrón-Duarte, J.E., Luna-Mora, V.F., Rivera-Correa, M., Kahn, T.R. </strong>(2016). Yellow-striped poison frog <i>Dendrobates truncatus</i> Cope,1861 "1860". In T.R. Kahn, E. La Marca, S. Lötters, J.L. Brown, E. Twomey & A. Amézquita (Eds.), Aposematic poison frogs (Dendrobatidae) of the Andean countries: Bolivia, Colombia, Ecuador, Perú and Venezuela. Tropical field guide series (pp. 323-328). Arlington, USA: Conservation International.  
  
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios o datos asociados.</i></p>
</div>
