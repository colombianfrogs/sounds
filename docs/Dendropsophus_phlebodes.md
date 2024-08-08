---
title: "Dendropsophus phlebodes"
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

## Leucostethus fraterdanieli

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionDeph')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectroDeph')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'tabDeph')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'audDeph')">Audios</button>
</div>

<div id="DescripcionDeph" class="tabcontent">
  <h3>Descripción</h3>
  <img src="images/Dendropsophus_phlebodes.png" alt=Dendropsophus phlebodes style="width:10cm;">

  <p>Si utiliza los datos, cítese como:</p>

  <p><strong>Marín, C.M., C. Molina-Zuluaga, A. Restrepo, E.Cano & J.M. Daza.</strong> 2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia with comments on the phylogenetic position of <i>Colostethus fraterdanieli</i>. <i>Zootaxa</i> 4461: 359--380. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a></p>
</div>

<div id="EspectroDeph" class="tabcontent">
  <h3>Espectrograma</h3>
  <video width="100%" height="auto" controls>
  <source src="Espectrograms/Dendropsophus_phlebodes.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<div id="tabDeph" class="tabcontent">
  <h3>Tablas</h3>
  <p>Descarga tabla de medidas <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
  <p>Descarga tabla selección RAVEN <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

<div id="audDeph" class="tabcontent">
  <h3>Audios</h3>
  <div class="audio-container">
    <audio controls>
      <source src="Dendropsophus_phlebodes.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
  <p>Más audios disponibles <a href="https://bit.ly/3LUkN5s">aquí</a>.</p>
</div>

