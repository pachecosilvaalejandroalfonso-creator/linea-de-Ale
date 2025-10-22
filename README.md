
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Línea de tiempo interactiva — La Conquista (1518–1521)</title>
<style>
body {
  font-family: 'Poppins', sans-serif;
  background: radial-gradient(circle at top, #03102b, #000512);
  color: #f3f5f9;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}
header {
  text-align: center;
  padding: 36px 20px 10px;
}
h1 {
  font-size: 2.2rem;
  color: #6fd6ff;
  text-shadow: 0 0 12px #00bfff, 0 0 22px #0077ff;
  letter-spacing: 1px;
}
.timeline {
  position: relative;
  display: flex;
  gap: 36px;
  overflow-x: auto;
  scroll-behavior: smooth;
  padding: 48px 36px 80px;
}
.timeline::before {
  content: '';
  position: absolute;
  top: 50%;
  left: 0;
  width: 100%;
  height: 4px;
  background: linear-gradient(90deg, #00bfff, #008cff, #00bfff);
  box-shadow: 0 0 20px #00bfff;
  border-radius: 2px;
}
.event {
  position: relative;
  min-width: 360px;
  max-width: 420px;
  background: linear-gradient(180deg, #071a34, #0b2744);
  border: 1px solid rgba(0,191,255,0.16);
  border-radius: 14px;
  box-shadow: 0 6px 24px rgba(0,191,255,0.06);
  padding: 16px;
  transition: transform 0.35s ease, box-shadow 0.35s ease;
  opacity: 0;
  transform: translateY(18px);
}
.event.visible { opacity: 1; transform: translateY(0); }
.event:hover { transform: translateY(-8px) scale(1.02); box-shadow: 0 14px 40px rgba(0,191,255,0.12); }
.event::before {
  content: '';
  position: absolute;
  top: calc(50% - 8px);
  left: -22px;
  width: 16px;
  height: 16px;
  background: #00bfff;
  border-radius: 50%;
  box-shadow: 0 0 12px #00bfff;
}
.meta { color: #88d8ff; font-weight: 700; margin-bottom: 6px; }
.title { font-weight: 800; color: #fff; font-size: 1.05rem; margin: 6px 0 10px; }
.imgwrap { width: 100%; height: 190px; border-radius: 10px; overflow: hidden; margin-bottom: 12px; border: 1px solid rgba(0,191,255,0.12); background: linear-gradient(180deg,#031826,#07233a); display:flex;align-items:center;justify-content:center }
.img-caption { font-size: 0.8rem; color: #aee6ff; margin-top:6px; text-align:center }
.desc { font-size: 0.95rem; color: #d6eeff; line-height: 1.5; }
footer { text-align: center; padding: 28px; color: #6fd6ff; font-size: 0.9rem; }
.small { font-size: 0.86rem; color: #98d9ff }
button.center { display:block; margin:12px auto 0; padding:8px 12px; background:#00bfff; color:#021028; border-radius:8px; border:none; font-weight:700 }
/* responsive */
@media (max-width:820px){ .timeline{padding:28px 20px} .event{min-width:300px} }
</style>
</head>
<body>
<header>
  <h1>Línea de tiempo interactiva — La Conquista (1518–1521)</h1>
  <div class="small">Versión con contexto extenso para cada acontecimiento. Colores: azul neón.</div>
</header>

<div class="timeline" id="timeline">

<!-- EVENTOS: cada tarjeta contiene un SVG ilustrativo embebido (para evitar dependencias externas) y texto extenso -->

<article class="event">
  <div class="meta">1517</div>
  <div class="title">Expedición de Francisco Hernández de Córdoba</div>
  <div class="imgwrap">
    <!-- SVG ilustrativo simple -->
    <svg width="100%" height="100%" viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="sea" x1="0" x2="0" y1="0" y2="1">
          <stop offset="0" stop-color="#08314a"/>
          <stop offset="1" stop-color="#021324"/>
        </linearGradient>
      </defs>
      <rect width="100%" height="100%" fill="url(#sea)" />
      <g transform="translate(40,200)">
        <path d="M0 40 Q80 -40 160 40 T320 40" fill="none" stroke="#5fd0ff" stroke-width="8" opacity="0.12"/>
        <g transform="translate(20,-60)">
          <rect x="0" y="40" width="180" height="60" rx="8" fill="#7fb9ff" opacity="0.18"/>
          <polygon points="40,40 80,0 120,40" fill="#bfe9ff" opacity="0.25"/>
        </g>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#aee6ff" font-size="20" font-family="Poppins, sans-serif">Ilustración (estilizada): llegada a Yucatán</text>
    </svg>
  </div>
  <div class="desc">La expedición de Francisco Hernández de Córdoba (1517) fue una de las primeras en tocar las costas de Yucatán. Los encuentros con los mayas fueron hostiles: los conquistadores sufrieron heridas y bajas importantes. Aunque no consiguieron una colonización inmediata, sus relatos sobre poblaciones organizadas y ciudades influyeron en la planificación de expediciones posteriores y despertaron el interés de la Corona y de conquistadores como Cortés.</div>
</article>

<article class="event">
  <div class="meta">1518</div>
  <div class="title">Exploración de Juan de Grijalva</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021425"/>
      <circle cx="120" cy="80" r="24" fill="#82e4ff" opacity="0.12"/>
      <g transform="translate(60,160)">
        <rect x="0" y="20" width="240" height="60" rx="10" fill="#7fb9ff" opacity="0.14"/>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20" font-family="Poppins, sans-serif">Ilustración (estilizada): reconocimiento de costas</text>
    </svg>
  </div>
  <div class="desc">Juan de Grijalva bordea las costas del Golfo de México, recopilando información geográfica y de población. Sus cartas y noticias hablaron de la impresionante organización del valle central (Tenochtitlan) y la existencia de riquezas. Esto llegó a oídos de otros capitanes y motivó nuevas expediciones con objetivos de exploración y lucro.</div>
</article>

<article class="event">
  <div class="meta">18 feb 1519</div>
  <div class="title">Zarpe de Hernán Cortés desde Cuba</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#03192b"/>
      <g fill="#7fd9ff" opacity="0.16">
        <rect x="120" y="140" width="360" height="60" rx="8"/>
        <polygon points="220,140 300,90 380,140"/>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): partida de la flota</text>
    </svg>
  </div>
  <div class="desc">Hernán Cortés parte de Cuba con once naves y más de 500 hombres, autorizado parcialmente por el gobernador Diego Velázquez. Sus intenciones combinaban la búsqueda de riqueza, prestigio personal y la extensión del dominio español. Desde el inicio hubo tensiones políticas: Velázquez no confiaba plenamente en Cortés.</div>
</article>

<article class="event">
  <div class="meta">Feb–Mar 1519</div>
  <div class="title">Llegada a Cozumel y rescate de Jerónimo de Aguilar</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#02162a"/>
      <g transform="translate(40,140)" fill="#9fe6ff" opacity="0.14">
        <rect x="0" y="0" width="300" height="60" rx="10"/>
        <circle cx="340" cy="30" r="24"/>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): contacto con mayas</text>
    </svg>
  </div>
  <div class="desc">En Cozumel Cortés establece contacto con los mayas y encuentra a Jerónimo de Aguilar, un náufrago español que hablaba maya. Aguilar se convierte en traductor inicial entre españoles y pueblos mayas, facilitando relaciones y el avance hacia la costa continental.</div>
</article>

<article class="event">
  <div class="meta">15 mar 1519</div>
  <div class="title">Malintzin (La Malinche) como intérprete</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#041528"/>
      <g fill="#7fe0ff" opacity="0.16">
        <ellipse cx="220" cy="120" rx="140" ry="40"/>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): intérprete</text>
    </svg>
  </div>
  <div class="desc">Después de la batalla de Tabasco, a los españoles se les entregan mujeres indígenas como regalos. Una de ellas, Malintzin, domina el náhuatl y el maya (por su educación previa) y actúa como intérprete, consejera y mediadora. Su papel fue clave para la comunicación, la diplomacia y las negociaciones entre Cortés y diversas sociedades mesoamericanas.</div>
</article>

<article class="event">
  <div class="meta">Abr 1519</div>
  <div class="title">Fundación de La Villa Rica de la Vera Cruz y hundimiento de naves</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#031426"/>
      <g fill="#7fd7ff" opacity="0.14">
        <rect x="60" y="120" width="260" height="60" rx="8"/>
      </g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): Veracruz</text>
    </svg>
  </div>
  <div class="desc">Cortés funda Veracruz para formalizar su expedición ante la Corona y crear una base autónoma frente a las órdenes de Diego Velázquez. Para asegurar la decisión de continuar, desmantela o hunde sus naves (según las crónicas), impidiendo el retorno fácil a Cuba y obligando a la tropa a comprometerse con la empresa.</div>
</article>

<article class="event">
  <div class="meta">May–Jul 1519</div>
  <div class="title">Exploraciones y alianzas en el altiplano</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021b31"/>
      <g fill="#9fe6ff" opacity="0.12"><rect x="40" y="120" width="320" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): encuentros</text>
    </svg>
  </div>
  <div class="desc">Cortés avanza por Jalapa, Tepeaca y otros puntos del altiplano. En el camino se producen combates y, simultáneamente, alianzas con pueblos sometidos por los mexicas (como los tlaxcaltecas). Estas alianzas son decisivas: aportan tropas, conocimiento del terreno y legitimidad local.</div>
</article>

<article class="event">
  <div class="meta">Oct 1519</div>
  <div class="title">Matanza de Cholula</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#041525"/>
      <g fill="#7fe0ff" opacity="0.14"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): Cholula</text>
    </svg>
  </div>
  <div class="desc">En Cholula, tras informes de una posible conspiración, los españoles realizan un ataque masivo contra la población. Las cifras varían según las fuentes, pero la matanza produjo cientos o miles de víctimas y sirvió para intimidar a otras ciudades, además de aumentar el rencor entre mexicas y españoles.</div>
</article>

<article class="event">
  <div class="meta">8 Nov 1519</div>
  <div class="title">Entrada a Tenochtitlan y alojamiento con Moctezuma</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#022033"/>
      <g fill="#9fe6ff" opacity="0.14"><rect x="80" y="120" width="280" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): Tenochtitlan</text>
    </svg>
  </div>
  <div class="desc">La llegada a la capital mexica dejó asombrados a los españoles por su urbanismo y arquitectura. Moctezuma recibe a Cortés con obsequios y hospitalidad, aunque la relación se vuelve tensa: Cortés decide mantener a Moctezuma como rehén para controlar la ciudad y garantizar la cooperación de los mexicas.</div>
</article>

<article class="event">
  <div class="meta">Mayo 1520</div>
  <div class="title">Alvarado y la masacre en el Templo Mayor</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021428"/>
      <g fill="#aee6ff" opacity="0.12"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): Templo Mayor</text>
    </svg>
  </div>
  <div class="desc">Mientras Cortés marcha para enfrentar a Pánfilo de Narváez (quien venía a arrestarlo), queda Pedro de Alvarado a cargo. Alvarado ordena un ataque durante una ceremonia religiosa en el Templo Mayor, causando gran indignación entre los mexicas y provocando la ruptura del frágil orden en la ciudad.</div>
</article>

<article class="event">
  <div class="meta">30 jun 1520</div>
  <div class="title">La Noche Triste</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#011323"/>
      <g fill="#80e0ff" opacity="0.14"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): La Noche Triste</text>
    </svg>
  </div>
  <div class="desc">Tras la rebelión, los españoles intentan escapar de Tenochtitlan cargando con el oro, pero son descubiertos por las fuerzas mexicas en la madrugada. Se produce una retirada caótica con muchas muertes y pérdidas. Este episodio es un punto crítico: muestra la resistencia mexica y la vulnerabilidad española.</div>
</article>

<article class="event">
  <div class="meta">Jul 1520</div>
  <div class="title">Muerte de Moctezuma y elección de Cuitláhuac</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021427"/>
      <g fill="#9fe6ff" opacity="0.12"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): Tlatoani</text>
    </svg>
  </div>
  <div class="desc">Moctezuma muere en circunstancias discutidas (según algunos fue asesinado por los mexicas al considerarlo colaborador; según otros, murió herido). Le sucede Cuitláhuac, quien lidera la resistencia; sin embargo, la llegada de la viruela debilita gravemente a la población y al liderazgo mexica.</div>
</article>

<article class="event">
  <div class="meta">Invierno 1520–Primavera 1521</div>
  <div class="title">Reagrupamiento español, viruela y tácticas</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021226"/>
      <g fill="#aee6ff" opacity="0.1"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): reorganización</text>
    </svg>
  </div>
  <div class="desc">Los sobrevivientes españoles se reorganizan en Tlaxcala y reciben refuerzos y recursos. Paralelamente, la viruela, una enfermedad europea, se propaga entre las poblaciones indígenas, causando una alta mortalidad que altera el equilibrio demográfico y militar. Cortés aprovecha esta debilidad y planifica el sitio final.</div>
</article>

<article class="event">
  <div class="meta">Primavera 1521</div>
  <div class="title">Construcción de bergantines y control del lago</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#021a2e"/>
      <g fill="#80e0ff" opacity="0.12"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): bergantines</text>
    </svg>
  </div>
  <div class="desc">Cortés manda construir bergantines en Tlaxcala y otros puertos; estas embarcaciones le permiten dominar el lago de Texcoco, bloquear suministros y bombardear posiciones. Es una muestra de adaptación militar: combinar aliados a pie con control naval local.</div>
</article>

<article class="event">
  <div class="meta">Mayo–Agosto 1521</div>
  <div class="title">Sitio prolongado de Tenochtitlan</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#02142a"/>
      <g fill="#9fe6ff" opacity="0.11"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): asedio</text>
    </svg>
  </div>
  <div class="desc">Durante meses la ciudad resiste el asedio: los españoles y sus aliados cortan el agua, el acceso a comida y atacan sistemáticamente barrios. El hambre, las enfermedades y la falta de agua debilitan la población; la defensa se vuelve insostenible y la moral cae.</div>
</article>

<article class="event">
  <div class="meta">13 ago 1521</div>
  <div class="title">Caída de Tenochtitlan y captura de Cuauhtémoc</div>
  <div class="imgwrap">
    <svg viewBox="0 0 800 400" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
      <rect width="100%" height="100%" fill="#011326"/>
      <g fill="#7fe0ff" opacity="0.12"><rect x="60" y="120" width="260" height="60" rx="8"/></g>
      <text x="50%" y="86%" text-anchor="middle" fill="#9fe6ff" font-size="20">Ilustración (estilizada): caída</text>
    </svg>
  </div>
  <div class="desc">Tras un sitio devastador, Tenochtitlan cae. Cuauhtémoc, el tlatoani final, es capturado y el sistema de gobierno mexica colapsa. Comienza la imposición colonial, la reorganización del territorio como Nueva España y un largo proceso de mestizaje, resistencia y transformación cultural.</div>
</article>

</div>

<footer></footer>

<script>
// hacer visibles las tarjetas al entrar en el viewport y permitir navegación con flechas
const events = Array.from(document.querySelectorAll('.event'));
const observer = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('visible'); } });
},{threshold:0.15});
events.forEach(ev=>observer.observe(ev));
// navegación con flechas
let idx = 0; window.addEventListener('keydown', e=>{
  if(e.key === 'ArrowRight'){ idx = Math.min(events.length-1, idx+1); events[idx].scrollIntoView({behavior:'smooth', inline:'center'}); }
  if(e.key === 'ArrowLeft'){ idx = Math.max(0, idx-1); events[idx].scrollIntoView({behavior:'smooth', inline:'center'}); }
});
</script>
</body>
</html>
