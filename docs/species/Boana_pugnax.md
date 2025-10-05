---
layout: page
title: "Boana pugnax"
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
  <h2><i>Boana pugnax</i></h2>
  <h4>(Schmidt, 1857)</h4>
  <img src="{{ site.baseurl }}/images/especie_Boana_pugnax.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Boana_pugnax.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Boana_pugnax.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18216/IAvH-CSA-18216.wav" target="_blank">IAvH-CSA-18216</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18219/IAvH-CSA-18219.wav" target="_blank">IAvH-CSA-18219</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18220/IAvH-CSA-18220.wav" target="_blank">IAvH-CSA-18220</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18223/IAvH-CSA-18223.wav" target="_blank">IAvH-CSA-18223</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18233/IAvH-CSA-18233.wav" target="_blank">IAvH-CSA-18233</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18278/IAvH-CSA-18278.wav" target="_blank">IAvH-CSA-18278</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18280/IAvH-CSA-18280.wav" target="_blank">IAvH-CSA-18280</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-20267/IAvH-CSA-20267.wav" target="_blank">IAvH-CSA-20267</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-20273/IAvH-CSA-20273.wav" target="_blank">IAvH-CSA-20273</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34867/IAvH-CSA-34867.wav" target="_blank">IAvH-CSA-34867</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-34878/IAvH-CSA-34878.wav" target="_blank">IAvH-CSA-34878</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35011/IAvH-CSA-35011.wav" target="_blank">IAvH-CSA-35011</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35018/IAvH-CSA-35018.wav" target="_blank">IAvH-CSA-35018</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35088/IAvH-CSA-35088.wav" target="_blank">IAvH-CSA-35088</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35293/IAvH-CSA-35293.wav" target="_blank">IAvH-CSA-35293</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35294/IAvH-CSA-35294.wav" target="_blank">IAvH-CSA-35294</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35295/IAvH-CSA-35295.wav" target="_blank">IAvH-CSA-35295</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35463/IAvH-CSA-35463.wav" target="_blank">IAvH-CSA-35463</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-35467/IAvH-CSA-35467.wav" target="_blank">IAvH-CSA-35467</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36244/IAvH-CSA-36244.wav" target="_blank">IAvH-CSA-36244</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36270/IAvH-CSA-36270.wav" target="_blank">IAvH-CSA-36270</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36288/IAvH-CSA-36288.wav" target="_blank">IAvH-CSA-36288</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36292/IAvH-CSA-36292.wav" target="_blank">IAvH-CSA-36292</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36295/IAvH-CSA-36295.wav" target="_blank">IAvH-CSA-36295</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36296/IAvH-CSA-36296.wav" target="_blank">IAvH-CSA-36296</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36297/IAvH-CSA-36297.wav" target="_blank">IAvH-CSA-36297</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36299/IAvH-CSA-36299.wav" target="_blank">IAvH-CSA-36299</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36300/IAvH-CSA-36300.wav" target="_blank">IAvH-CSA-36300</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36310/IAvH-CSA-36310.wav" target="_blank">IAvH-CSA-36310</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37306/IAvH-CSA-37306.wav" target="_blank">IAvH-CSA-37306</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37307/IAvH-CSA-37307.wav" target="_blank">IAvH-CSA-37307</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37309/IAvH-CSA-37309.wav" target="_blank">IAvH-CSA-37309</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37332/IAvH-CSA-37332.wav" target="_blank">IAvH-CSA-37332</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37334/IAvH-CSA-37334.wav" target="_blank">IAvH-CSA-37334</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-37348/IAvH-CSA-37348.wav" target="_blank">IAvH-CSA-37348</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=555142" target="_blank">Boana pugnax</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">

  <p><strong>***</strong><i>No existen publicaciones con sonidos de poblaciones colombianas.</i></p>
</div>
