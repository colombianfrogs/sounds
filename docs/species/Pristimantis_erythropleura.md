---
layout: page
title: "Pristimantis erythropleura"
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
  <h2><i>Pristimantis erythropleura</i></h2>
  <h4>(Boulenger, 1896)</h4>
  <img src="{{ site.baseurl }}/images/especie_Pristimantis_erythropleura.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Pristimantis_erythropleura.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="figLefr" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Pristimantis_erythropleura.png" style="width:15cm;">
</div>

<!-- Seccion Datos -->
<div id="tabLefr" class="tabcontent">
  <p>Figshare <a href="https://figshare.com/articles/media/Pristimantis_erythropleura_mp3/25321690/2">https://figshare.com/articles/media/Pristimantis_erythropleura_mp3/25321690/2</a>.</p>
</div>

Publicaciones que incorporan sonidos de esta especie:
<br><br>
<strong>Duarte-Marín CITA Arango-Ospina.</strong> 2019. The advertisement call of <i>Pristimantis erythropleura</i> (Boulenger, 1896) (Craugastoridae) from a population in the central Andes of Colombia. <i>The Herpetological Bulletin</i> 148: 33--34. <a href="https://www.thebhs.org/publications/the-herpetological-bulletin/issue-number-148-summer-2019/1947-08-the-advertisement-call-of-i-pristimantis-erythropleura-i-boulenger-1896-craugastoridae-from-a-population-in-the-central-andes-of-colombia/file">link</a>
