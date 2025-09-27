---
layout: page
title: "Craugastor metriosistus"
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
  <h2><i>Craugastor metriosistus</i></h2>
  <h4>Ospina-Sarria, Angarita-Sierra, {{AUTHOR}} Pedroza-Banda, 2015</h4>
  <img src="{{ site.baseurl }}/images/especie_Craugastor_metriosistus.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Craugastor_metriosistus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Craugastor_metriosistus.png" style="width:15cm;">
</div>

#### Disponibilidad de datos

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'dat')">Datos</button>
  <button class="tablinks" onclick="openTab(event, 'pubs')">Publicaciones</button>
</div>

<!-- Seccion Datos -->
<div id="dat" class="tabcontent">
  <p><strong>Disponible en Figshare</strong></p>
  <p>Rivera-Correa, M. (2024). Craugastor metriosistus. figshare. Media. 
    <a href="https://doi.org/10.6084/m9.figshare.27798534.v3" target="_blank">https://doi.org/10.6084/m9.figshare.27798534.v3</a>
  </p>
</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Ospina-Sarria, J. J., Angarita-Sierra, T., and Pedroza-Banda, R.</strong> 2015. A new species of Craugastor (Anura: Craugastoridae) from the Magdalena River Valley, Colombia, with evaluation of the characters used to identify species of the <i>Craugastor fitzingeri</i> group. <i>South American Journal of Herpetology</i> 10: 1653–177.  
  <a href="https://doi.org/10.2994/SAJH-D-14-00014.1" target="_blank">http://doi.org/10.2994/SAJH-D-14-00014.1.</a></p>
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios y datos asociados.</i></p>
  <p><strong>***</strong><i>El audio disponible en Figshare corresponde al voucher de Sarria et al. 2015</i></p>  
</div>
