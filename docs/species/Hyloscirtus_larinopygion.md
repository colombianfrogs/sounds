---
layout: page
title: "Hyloscirtus larinopygion"
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
  <h2><i>Hyloscirtus larinopygion</i></h2>
  <h4>(Duellman, 1973)</h4>
  <img src="{{ site.baseurl }}/images/especie_Hyloscirtus_larinopygion.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Hyloscirtus_larinopygion.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Hyloscirtus_larinopygion.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-20355/IAvH-CSA-20355.wav" target="_blank">IAvH-CSA-20355</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34476/IAvH-CSA-34476.wav" target="_blank">IAvH-CSA-34476</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34477/IAvH-CSA-34477.wav" target="_blank">IAvH-CSA-34477</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35772/IAvH-CSA-35772.wav" target="_blank">IAvH-CSA-35772</a></p>
  
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Hyloscirtus larinopygion. figshare. Media.  
    <a href="https://doi.org/10.6084/m9.figshare.27642150.v1" target="_blank">https://doi.org/10.6084/m9.figshare.27642150.v1</a></p>
  
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=65655" target="_blank">Hyloscirtus larinopygion</a></p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Bernal, M.H., Montealegre, D.P., Páez, C.A.</strong> 2004. Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. <i>Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales</i> 28: 385-390. 
  <a href="https://raccefyn.co/index.php/raccefyn/article/view/2135" target="_blank">https://raccefyn.co/index.php/raccefyn/article/view/2135</a></p>
  
  <p><strong>Rivera-Correa, M., Vargas-Salinas, F., Grant, T.</strong> 2017. Statistical differences and biological implications: a comparative analysis of the advertisement calls of two Andean stream treefrogs (Hylidae: <i>Hyloscirtus</i>) and the evolution of acoustic characters. <a href="https://www.salamandra-journal.com/index.php/contents/2017-vol-53/1827-rivera-correa-m-f-vargas-salinas-t-grant" target="_blank"><i>Salamandra</i> 53: 237-244.</a></p>
  
  <p><strong>***</strong><i>Los artículos donde se publicó el canto de advertencia no disponibiliza los audios o datos asociados.</i></p>
</div>
