---
layout: page
title: "Dendropsophus microcephalus"
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
  <h2><i>Dendropsophus microcephalus</i></h2>
  <h4>(Cope, 1886)</h4>
  <img src="{{ site.baseurl }}/images/especie_Dendropsophus_microcephalus.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Dendropsophus_microcephalus.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Dendropsophus_microcephalus.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18208/IAvH-CSA-18208.wav" target="_blank">IAvH-CSA-18208</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18209/IAvH-CSA-18209.wav" target="_blank">IAvH-CSA-18209</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18210/IAvH-CSA-18210.wav" target="_blank">IAvH-CSA-18210</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18211/IAvH-CSA-18211.wav" target="_blank">IAvH-CSA-18211</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18212/IAvH-CSA-18212.wav" target="_blank">IAvH-CSA-18212</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18213/IAvH-CSA-18213.wav" target="_blank">IAvH-CSA-18213</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18230/IAvH-CSA-18230.wav" target="_blank">IAvH-CSA-18230</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18232/IAvH-CSA-18232.wav" target="_blank">IAvH-CSA-18232</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18234/IAvH-CSA-18234.wav" target="_blank">IAvH-CSA-18234</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18279/IAvH-CSA-18279.wav" target="_blank">IAvH-CSA-18279</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34465/IAvH-CSA-34465.wav" target="_blank">IAvH-CSA-34465</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34471/IAvH-CSA-34471.wav" target="_blank">IAvH-CSA-34471</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34871/IAvH-CSA-34871.wav" target="_blank">IAvH-CSA-34871</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35008/IAvH-CSA-35008.wav" target="_blank">IAvH-CSA-35008</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35010/IAvH-CSA-35010.wav" target="_blank">IAvH-CSA-35010</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35019/IAvH-CSA-35019.wav" target="_blank">IAvH-CSA-35019</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35292/IAvH-CSA-35292.wav" target="_blank">IAvH-CSA-35292</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35296/IAvH-CSA-35296.wav" target="_blank">IAvH-CSA-35296</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35297/IAvH-CSA-35297.wav" target="_blank">IAvH-CSA-35297</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35465/IAvH-CSA-35465.wav" target="_blank">IAvH-CSA-35465</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35471/IAvH-CSA-35471.wav" target="_blank">IAvH-CSA-35471</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36229/IAvH-CSA-36229.wav" target="_blank">IAvH-CSA-36229</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36243/IAvH-CSA-36243.wav" target="_blank">IAvH-CSA-36243</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36265/IAvH-CSA-36265.wav" target="_blank">IAvH-CSA-36265</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36267/IAvH-CSA-36267.wav" target="_blank">IAvH-CSA-36267</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36268/IAvH-CSA-36268.wav" target="_blank">IAvH-CSA-36268</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36271/IAvH-CSA-36271.wav" target="_blank">IAvH-CSA-36271</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36272/IAvH-CSA-36272.wav" target="_blank">IAvH-CSA-36272</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36284/IAvH-CSA-36284.wav" target="_blank">IAvH-CSA-36284</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36285/IAvH-CSA-36285.wav" target="_blank">IAvH-CSA-36285</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36287/IAvH-CSA-36287.wav" target="_blank">IAvH-CSA-36287</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36291/IAvH-CSA-36291.wav" target="_blank">IAvH-CSA-36291</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36303/IAvH-CSA-36303.wav" target="_blank">IAvH-CSA-36303</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36304/IAvH-CSA-36304.wav" target="_blank">IAvH-CSA-36304</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37304/IAvH-CSA-37304.wav" target="_blank">IAvH-CSA-37304</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37311/IAvH-CSA-37311.wav" target="_blank">IAvH-CSA-37311</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37333/IAvH-CSA-37333.wav" target="_blank">IAvH-CSA-37333</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37335/IAvH-CSA-37335.wav" target="_blank">IAvH-CSA-37335</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37338/IAvH-CSA-37338.wav" target="_blank">IAvH-CSA-37338</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37344/IAvH-CSA-37344.wav" target="_blank">IAvH-CSA-37344</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37349/IAvH-CSA-37349.wav" target="_blank">IAvH-CSA-37349</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37350/IAvH-CSA-37350.wav" target="_blank">IAvH-CSA-37350</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34266/IAvH-CSA-34266.wav" target="_blank">IAvH-CSA-34266</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34267/IAvH-CSA-34267.wav" target="_blank">IAvH-CSA-34267</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=65373" target="_blank">Dendropsophus microcephalus</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Bernal, M.H., Montealegre, D.P., Páez, C.A.</strong> 2004. Estudio de la vocalización de trece especies de anuros del municipio de Ibagué, Colombia. <i>Revista de la Academia Colombiana de Ciencias Exactas, Físicas y Naturales</i> 28: 385-390. 
  <a href="https://raccefyn.co/index.php/raccefyn/article/view/2135" target="_blank">https://raccefyn.co/index.php/raccefyn/article/view/2135</a></p>
  <p><strong>***</strong><i>Bernal et al. (2004) no disponibiliza los audios y datos asociados.</i></p>
</div>
