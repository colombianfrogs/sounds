---
layout: page
title: "Leucostethus fraterdanieli"
output: html_document
---


<style>
/* CSS para las pestañas */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #7dd87d;
}
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
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
/* CSS para audios */
.audio-container {
  display: flex;
  flex-direction: column;
}
.audio-container audio {
  margin-bottom: 10px;
}

/* Ocultar el título en la página */
body h1 {
  display: none;
}
</style>


<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>

<!-- Presentacion de la especie y los datos -->

<div style="font-family: Times; text-align: center;">
    <h2><i>Leucostethus fraterdanieli</i></h2>
    <img src="{{ site.baseurl }}/images/especie_Leucostethus_fraterdanieli.png" style="width:15cm;">
</div>

<br><br>

<!-- Definicion de secciones -->

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'EspectroLefr')">Espectro dinámico</button>
  <button class="tablinks" onclick="openTab(event, 'tabLefr')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'audLefr')">Datos</button>
</div>

<!-- Seccion espectrograma -->

<div id="EspectroLefr" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls style="display: block; margin-left: auto; margin-right: auto;">
    <source src="{{ site.baseurl }}/Espectrograms/Leucostethus_fraterdanieli.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
  <br><br>
  <img src="{{ site.baseurl }}/images/espectrograma_Diasporus_anthrax.png" style="width:10cm; display: block; margin-left: auto; margin-right: auto;">
</div>

<!-- Seccion de tablas -->

<div id="tabLefr" class="tabcontent">
  <p>Descarga tabla de medidas <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
  <p>Descarga tabla selección RAVEN <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

<!-- Seccion de audios -->

<div id="audLefr" class="tabcontent">
  <div class="audio-container">
    <audio controls>
      <source src="{{ site.baseurl }}/Audios/Boana_boans.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Audios disponibles <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

