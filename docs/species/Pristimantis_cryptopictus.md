---
layout: page
title: "Pristimantis cryptopictus"
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
  <h2><i>Pristimantis cryptopictus</i></h2>
  <h4>Patiño-Ocampo, Duarte-Marín, and Rivera-Correa, 2022</h4>
  <img src="{{ site.baseurl }}/images/especie_Pristimantis_cryptopictus.png" style="width:15cm;">
</div>

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'EspectroLefr')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'figLefr')">Figura</button>
  <button class="tablinks" onclick="openTab(event, 'tabLefr')">Datos</button>
</div>

<!-- Seccion Espectrograma -->
<div id="EspectroLefr" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Pristimantis_cryptopictus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="figLefr" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Pristimantis_cryptopictus.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tabLefr" class="tabcontent">
  <p>Figshare <a href="https://doi.org/10.6084/m9.figshare.27798729.v2">https://doi.org/10.6084/m9.figshare.27798729.v2</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
<strong>Patiño-Ocampo E., S. Duarte-Marín y M. Rivera-Correa.</strong> 2022. Genética, bioacústica y morfología revelan una nueva especie oculta en <i>Pristimantis dorsopictus</i> (Anura: Strabomantidae). <i>Revista Latinoamericana de Herpetología</i> 5: 60--90. <a href="https://doi.org/10.22201/fc.25942158e.2022.1.305 ">https://doi.org/10.22201/fc.25942158e.2022.1.305</a>
