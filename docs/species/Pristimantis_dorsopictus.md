---
layout: page
title: "Pristimantis dorsopictus"
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
  <h2><i>Pristimantis dorsopictus</i></h2>
  <h4>(Rivero y Serna, 1988)</h4>
  <img src="{{ site.baseurl }}/images/especie_Pristimantis_dorsopictus.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Pristimantis_dorsopictus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Pristimantis_dorsopictus.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18808/IAvH-CSA-18808.wav" target="_blank">IAvH-CSA-18808</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18809/IAvH-CSA-18809.wav" target="_blank">IAvH-CSA-18809</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18810/IAvH-CSA-18810.wav" target="_blank">IAvH-CSA-18810</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18811/IAvH-CSA-18811.wav" target="_blank">IAvH-CSA-18811</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18813/IAvH-CSA-18813.wav" target="_blank">IAvH-CSA-18813</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18812/IAvH-CSA-18812.wav" target="_blank">IAvH-CSA-18812</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18814/IAvH-CSA-18814.wav" target="_blank">IAvH-CSA-18814</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18815/IAvH-CSA-18815.wav" target="_blank">IAvH-CSA-18815</a></p>

  

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Autor_aqui</strong>Patiño-Ocampo E., S. Duarte-Marín y M. Rivera-Correa. 2022. Genética, bioacústica y morfología revelan una nueva especie oculta en Pristimantis dorsopictus (Anura: Strabomantidae). Revista Latinoamericana de Herpetología 5: 60–90. https://doi.org/10.22201/fc.25942158e.2022.1.305. 
  <a href="https://doi.org/10.22201/fc.25942158e.2022.1.305" target="_blank">https://doi.org/10.22201/fc.25942158e.2022.1.305</a></p>
  <p><strong>***</strong><i></i></p>
</div>
