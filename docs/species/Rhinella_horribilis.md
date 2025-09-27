---
layout: page
title: "Rhinella horribilis"
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
  <h2><i>Rhinella horribilis</i></h2>
  <h4>(Wiegmann, 1833)</h4>
  <img src="{{ site.baseurl }}/images/especie_Rhinella_horribilis.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Rhinella_horribilis.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Rhinella_horribilis.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34493.wav" target="_blank">IAVH-CSA-34493</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34494.wav" target="_blank">IAVH-CSA-34494</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34495.wav" target="_blank">IAVH-CSA-34495</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34496.wav" target="_blank">IAVH-CSA-34496</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34497.wav" target="_blank">IAVH-CSA-34497</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34498.wav" target="_blank">IAVH-CSA-34498</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34499.wav" target="_blank">IAVH-CSA-34499</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34493/IAvH-CSA-34500.wav" target="_blank">IAVH-CSA-34500</a></p>  
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34149/IAvH-CSA-35775.wav" target="_blank">IAVH-CSA-35775</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34150/IAvH-CSA-36266.wav" target="_blank">IAVH-CSA-36266</a></p>

  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Rhinella horribilis. figshare. Media.  
    <a href="https://doi.org/10.6084/m9.figshare.27640617.v2" target="_blank">https://doi.org/10.6084/m9.figshare.27640617.v2</a>
  </p>
  
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=517119" target="_blank">Rhinella horribilis</a>
  </p>
  
</div>


<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Bernal, M.H., Montealegre, D.P., Páez, C.A.</strong> 2004. Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. <i>Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales</i> 28: 385-390. 
  <a href="https://raccefyn.co/index.php/raccefyn/article/view/2135" target="_blank">https://raccefyn.co/index.php/raccefyn/article/view/2135</a></p>
  <p><strong>***</strong><i>Bernal et al. (2004) no disponibiliza los audios y datos asociados.</i></p>
</div>
