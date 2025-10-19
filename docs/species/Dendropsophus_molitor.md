---
layout: page
title: "Dendropsophus molitor"
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
  <h2><i>Dendropsophus molitor</i></h2>
  <h4>(Schmidt, 1857)</h4>
  <img src="{{ site.baseurl }}/images/especie_Dendropsophus_molitor.png" style="width:15cm;">
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
    <source src="{{ site.baseurl }}/Espectrograms/dyna_Dendropsophus_molitor.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
</div>

<!-- Seccion Figura -->
<div id="fig" class="tabcontent" style="text-align: center;">
  <img src="{{ site.baseurl }}/images/spec_Dendropsophus_molitor.png" style="width:15cm;">
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
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-690/IAvH-CSA-690.wav" target="_blank">IAvH-CSA-690</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-9325/IAvH-CSA-9325.wav" target="_blank">IAvH-CSA-9325</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-11023/IAvH-CSA-11023.wav" target="_blank">IAvH-CSA-11023</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-11074/IAvH-CSA-11074.wav" target="_blank">IAvH-CSA-11074</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-11081/IAvH-CSA-11081.wav" target="_blank">IAvH-CSA-11081</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-14962/IAvH-CSA-14962.wav" target="_blank">IAvH-CSA-14962</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-14966/IAvH-CSA-14966.wav" target="_blank">IAvH-CSA-14966</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18197/IAvH-CSA-18197.wav" target="_blank">IAvH-CSA-18197</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18259/IAvH-CSA-18259.wav" target="_blank">IAvH-CSA-18259</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18442/IAvH-CSA-18442.wav" target="_blank">IAvH-CSA-18442</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-18452/IAvH-CSA-18452.wav" target="_blank">IAvH-CSA-18452</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-20140/IAvH-CSA-20140.wav" target="_blank">IAvH-CSA-20140</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36665/IAvH-CSA-36665.wav" target="_blank">IAvH-CSA-36665</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36666/IAvH-CSA-36666.wav" target="_blank">IAvH-CSA-36666</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36667/IAvH-CSA-36667.wav" target="_blank">IAvH-CSA-36667</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36774/IAvH-CSA-36774.wav" target="_blank">IAvH-CSA-36774</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36779/IAvH-CSA-36779.wav" target="_blank">IAvH-CSA-36779</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36780/IAvH-CSA-36780.wav" target="_blank">IAvH-CSA-36780</a></p>
  <p><a href="http://colecciones.humboldt.org.co/rec/sonidos/IAvH-CSA-36781/IAvH-CSA-36781.wav" target="_blank">IAvH-CSA-36781</a></p>

  <p><strong>Disponibles en iNaturalist</strong></p>
  <p><a href="https://www.inaturalist.org/observations?place_id=7196&sounds&taxon_id=1595931" target="_blank">Dendropsophus molitor</a></p>

</div>

<!-- Seccion Publicaciones -->
<div id="pubs" class="tabcontent">
  <p><strong>Lüddecke, H., Amézquita, A., Bernal, X., Guzmán, F.</strong> 2000. Partitioning of vocal activity in a Neotropical highland-frog community. <i>Studies on Neotropical Fauna and Environment</i> 35: 185-194. 
  <a href="https://doi.org/10.1076/snfe.35.3.185.8855" target="_blank">https://doi.org/10.1076/snfe.35.3.185.8855</a></p> 
  
  <p><strong>Lüddecke, H., Sánchez, O.R.</strong> 2002. Are tropical highland frog calls cold-adapted? The case of the Andean frog <i>Hyla labialis</i>. <i>Biotropica</i> 34: 281-288.  <a href="https://doi.org/10.1111/j.1744-7429.2002.tb00539.x" target="_blank">https://doi.org/10.1111/j.1744-7429.2002.tb00539.x
  
  
  
  <p><strong>Guarnizo, C.E., Escallón, C., Cannatella, D., Amézquita, A.</strong> 2012. Congruence between acoustic traits and genealogical history reveals a new species of Dendropsophus (Anura: Hylidae) in the high Andes of Colombia. Herpetologica 68: 523-540. DOI:10.1655/HERPETOLOGICA-D-10-00038. 
  <a href="DOI:10.1076/snfe.35.3.185.8855;  https://doi.org/10.1111/j.1744-7429.2002.tb00539.x; DOI:10.1655/HERPETOLOGICA-D-10-00038" target="_blank">DOI:10.1076/snfe.35.3.185.8855;  https://doi.org/10.1111/j.1744-7429.2002.tb00539.x; DOI:10.1655/HERPETOLOGICA-D-10-00038</a></p>
  <p><strong>***</strong><i>El artículo donde se publicó el canto de advertencia no disponibiliza los audios o datos asociados.</i></p>
</div>
