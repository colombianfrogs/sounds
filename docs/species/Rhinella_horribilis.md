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
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Rhinella horribilis. figshare. Media. https://doi.org/10.6084/m9.figshare.27640617.v2 
    <a href="https://doi.org/10.6084/m9.figshare.27640617.v3" target="_blank">https://doi.org/10.6084/m9.figshare.27640617.v3</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p>Bernal, M.H., Montealegre, D.P., Páez, C.A. (2004). Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales 28: 385-390.. 
  <a href="https://raccefyn.co/index.php/raccefyn/article/view/2135" target="_blank">{{URL}}</a></p>
  <p><strong>***</strong><i>Bernal et al. (2004) no disponibiliza los audios y datos asociados.</i></p>
</div>
