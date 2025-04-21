---
layout: page
title: "Boana punctata"
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
  <h2><i>Boana punctata</i></h2>
  <h4>(Schneider, 1799)</h4>
  <img src="{{ site.baseurl }}/images/especie_Boana_punctata.png" style="width:15cm;">
</div>

<!-- Tabs section -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Espectro')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'fig')">Figura</button>
  <button class="tablinks" onclick="openTab(event, 'tab')">Datos</button>
</div>

<!-- Seccion Espectrograma -->
<div id="Espectro" class="tabcontent" style="text-align: center;">
  <video width="100%" height="auto" controls>
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Boana_punctata.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Boana_punctata.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tab" class="tabcontent">
  <p><strong>Publicados en Figshare</strong></p>
  <p>Chaves Portilla, Giovanni (2024). <em>Boana punctata</em>. figshare. Media. 
    <a href="https://doi.org/10.6084/m9.figshare.27642198.v1"> https://doi.org/10.6084/m9.figshare.27642198.v1</a>
  </p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
Sin artículos publicados para Colombia.
