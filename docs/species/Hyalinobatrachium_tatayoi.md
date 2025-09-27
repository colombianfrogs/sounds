---
layout: page
title: "Hyalinobatrachium tatayoi"
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
  <h2><i>Hyalinobatrachium tatayoi</i></h2>
  <h4>Castroviejo-Fisher, Ayarzagüena, and Vilà, 2007</h4>
  <img src="{{ site.baseurl }}/images/especie_Hyalinobatrachium_tatayoi.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Hyalinobatrachium_tatayoi.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Hyalinobatrachium_tatayoi.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-20272/IAvH-CSA-20272.wav" target="_blank">IAVH-CSA-20272</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34223/IAvH-CSA-34223.wav" target="_blank">IAVH-CSA-34223</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34224/IAvH-CSA-34224.wav" target="_blank">IAVH-CSA-34224</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34225/IAvH-CSA-34225.wav" target="_blank">IAVH-CSA-34225</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34226/IAvH-CSA-34226.wav" target="_blank">IAVH-CSA-34226</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34227/IAvH-CSA-34227.wav" target="_blank">IAVH-CSA-34227</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34228/IAvH-CSA-34228.wav" target="_blank">IAVH-CSA-34228</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34229/IAvH-CSA-34229.wav" target="_blank">IAVH-CSA-34229</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34230/IAvH-CSA-34230.wav" target="_blank">IAVH-CSA-34230</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34231/IAvH-CSA-34231.wav" target="_blank">IAVH-CSA-34231</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34232/IAvH-CSA-34232.wav" target="_blank">IAVH-CSA-34232</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34362/IAvH-CSA-34362.wav" target="_blank">IAVH-CSA-34362</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34367/IAvH-CSA-34367.wav" target="_blank">IAVH-CSA-34367</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34368/IAvH-CSA-34368.wav" target="_blank">IAVH-CSA-34368</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34380/IAvH-CSA-34380.wav" target="_blank">IAVH-CSA-34380</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34381/IAvH-CSA-34381.wav" target="_blank">IAVH-CSA-34381</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34382/IAvH-CSA-34382.wav" target="_blank">IAVH-CSA-34382</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34385/IAvH-CSA-34385.wav" target="_blank">IAVH-CSA-34385</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34387/IAvH-CSA-34387.wav" target="_blank">IAVH-CSA-34387</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34869/IAvH-CSA-34869.wav" target="_blank">IAVH-CSA-34869</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37363/IAvH-CSA-37363.wav" target="_blank">IAvH-CSA-37363</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37364/IAvH-CSA-37364.wav" target="_blank">IAvH-CSA-37364</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37365/IAvH-CSA-37365.wav" target="_blank">IAvH-CSA-37365</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37366/IAvH-CSA-37366.wav" target="_blank">IAvH-CSA-37366</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37367/IAvH-CSA-37367.wav" target="_blank">IAvH-CSA-37367</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37368/IAvH-CSA-37368.wav" target="_blank">IAvH-CSA-37368</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37369/IAvH-CSA-37369.wav" target="_blank">IAvH-CSA-37369</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37370/IAvH-CSA-37370.wav" target="_blank">IAvH-CSA-37370</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37371/IAvH-CSA-37371.wav" target="_blank">IAvH-CSA-37371</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37372/IAvH-CSA-37372.wav" target="_blank">IAvH-CSA-37372</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37373/IAvH-CSA-37373.wav" target="_blank">IAvH-CSA-37373</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37374/IAvH-CSA-37374.wav" target="_blank">IAvH-CSA-37374</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37375/IAvH-CSA-37375.wav" target="_blank">IAvH-CSA-37375</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37376/IAvH-CSA-37376.wav" target="_blank">IAvH-CSA-37376</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37377/IAvH-CSA-37377.wav" target="_blank">IAvH-CSA-37377</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37378/IAvH-CSA-37378.wav" target="_blank">IAvH-CSA-37378</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37379/IAvH-CSA-37379.wav" target="_blank">IAvH-CSA-37379</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37380/IAvH-CSA-37380.wav" target="_blank">IAvH-CSA-37380</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37381/IAvH-CSA-37381.wav" target="_blank">IAvH-CSA-37381</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37382/IAvH-CSA-37382.wav" target="_blank">IAvH-CSA-37382</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37383/IAvH-CSA-37383.wav" target="_blank">IAvH-CSA-37383</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37384/IAvH-CSA-37384.wav" target="_blank">IAvH-CSA-37384</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37385/IAvH-CSA-37385.wav" target="_blank">IAvH-CSA-37385</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37386/IAvH-CSA-37386.wav" target="_blank">IAvH-CSA-37386</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37387/IAvH-CSA-37387.wav" target="_blank">IAvH-CSA-37387</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37388/IAvH-CSA-37388.wav" target="_blank">IAvH-CSA-37388</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37389/IAvH-CSA-37389.wav" target="_blank">IAvH-CSA-37389</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37390/IAvH-CSA-37390.wav" target="_blank">IAvH-CSA-37390</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37391/IAvH-CSA-37391.wav" target="_blank">IAvH-CSA-37391</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37392/IAvH-CSA-37392.wav" target="_blank">IAvH-CSA-37392</a></p>
  
  <p><strong>Disponibles en Figshare</strong></p>
  <p>Chaves-Portilla, G. (2024). Hyalinobatrachium tatayoi. Figshare. Media.  
    <a href="https://doi.org/10.6084/m9.figshare.27640569.v2" target="_blank">https://doi.org/10.6084/m9.figshare.27640569.v2</a>
  </p>
  
  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=65547" target="_blank">Hyalinobatrachium tatayoi</a>
  </p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>***</strong><i>No existen artículos con sonidos de poblaciones colombianas</i></p>
</div>
