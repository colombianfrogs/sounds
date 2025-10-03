---
layout: page
title: "Leptodactylus fragilis"
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
  <h2><i>Leptodactylus fragilis</i></h2>
  <h4>(Brocchi, 1877)</h4>
  <img src="{{ site.baseurl }}/images/especie_Leptodactylus_fragilis.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Leptodactylus_fragilis.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Leptodactylus_fragilis.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34274/IAvH-CSA-34274.wav" target="_blank">IAvH-CSA-34274</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35290/IAvH-CSA-35290.wav" target="_blank">IAvH-CSA-35290</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35464/IAvH-CSA-35464.wav" target="_blank">IAvH-CSA-35464</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36235/IAvH-CSA-36235.wav" target="_blank">IAvH-CSA-36235</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36246/IAvH-CSA-36246.wav" target="_blank">IAvH-CSA-36246</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36248/IAvH-CSA-36248.wav" target="_blank">IAvH-CSA-36248</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36249/IAvH-CSA-36249.wav" target="_blank">IAvH-CSA-36249</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36251/IAvH-CSA-36251.wav" target="_blank">IAvH-CSA-36251</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36286/IAvH-CSA-36286.wav" target="_blank">IAvH-CSA-36286</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36293/IAvH-CSA-36293.wav" target="_blank">IAvH-CSA-36293</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36298/IAvH-CSA-36298.wav" target="_blank">IAvH-CSA-36298</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36314/IAvH-CSA-36314.wav" target="_blank">IAvH-CSA-36314</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37305/IAvH-CSA-37305.wav" target="_blank">IAvH-CSA-37305</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37312/IAvH-CSA-37312.wav" target="_blank">IAvH-CSA-37312</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37314/IAvH-CSA-37314.wav" target="_blank">IAvH-CSA-37314</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37317/IAvH-CSA-37317.wav" target="_blank">IAvH-CSA-37317</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37321/IAvH-CSA-37321.wav" target="_blank">IAvH-CSA-37321</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37326/IAvH-CSA-37326.wav" target="_blank">IAvH-CSA-37326</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37327/IAvH-CSA-37327.wav" target="_blank">IAvH-CSA-37327</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37328/IAvH-CSA-37328.wav" target="_blank">IAvH-CSA-37328</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37329/IAvH-CSA-37329.wav" target="_blank">IAvH-CSA-37329</a></p>
 
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Leptodactylus fragilis. Figshare. Media.  
    <a href="https://doi.org/10.6084/m9.figshare.27642204.v1" target="_blank">https://doi.org/10.6084/m9.figshare.27642204.v1</a>
  </p>
  
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=22976" target="_blank">Leptodactylus fragilis</a></p>
  
  
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Bernal, M.H., Montealegre, D.P., Páez, C.A.</strong> 2004. Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. <i>Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales</i> 28: 385-390. 
  <a href="https://raccefyn.co/index.php/raccefyn/article/view/2135" target="_blank">https://raccefyn.co/index.php/raccefyn/article/view/2135</a></p>
  <p><strong>***</strong><i>Bernal et al. (2004) no disponibiliza los audios y datos asociados.</i></p>
</div>
