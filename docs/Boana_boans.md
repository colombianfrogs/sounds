---
title: "Boana boans"
output: html_document
---


<style>
/* CSS para las pestañas */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
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

<div style="font-family: Times; text-align: center;">
    <h1><i>Boana boans</i></h1>
    <img src="images/especie_Boana_boans.png" style="width:10cm;">
</div>
<br><br><br><br>
Los audios y tablas corresponden a la publicación:

<strong>Marín, C.M., C. Molina-Zuluaga, A. Restrepo, E.Cano & J.M. Daza.</strong> 2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia with comments on the phylogenetic position of <i>Colostethus fraterdanieli</i>. <i>Zootaxa</i> 4461: 359--380. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a>

contacto: Carlos M. Marín (), Juan M. Daza (juanm.daza@udea.edu.co)

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'EspectroBobo')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'tabBobo')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'audBobo')">Audios</button>
</div>

<div id="EspectroBobo" class="tabcontent" style="text-align: center;">
  <!-- Centering the video -->
  <video width="100%" height="auto" controls style="display: block; margin-left: auto; margin-right: auto;">
    <source src="Espectrograms/Boana_boans.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>

  <!-- Adding two line spaces between the video and the image -->
  <br><br>

  <!-- Centering the image -->
  <img src="images/espectrograma_Diasporus_anthrax.png" style="width:10cm; display: block; margin-left: auto; margin-right: auto;">
</div>


<div id="tabBobo" class="tabcontent">

  <p>Descarga tabla de medidas <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
  <p>Descarga tabla selección RAVEN <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

<div id="audBobo" class="tabcontent">
  <h3>Audios</h3>
  <div class="audio-container">
    <audio controls>
      <source src="Boana_boans.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Más audios disponibles <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

