---
layout: default
title: Rúbricas SOLO
---

<h1>Rúbricas de evaluación — estilo SOLO</h1>
<p class="lede">Structure of Observed Learning Outcomes — una rúbrica por entrega del proyecto de aula</p>

<div class="card">
<p>El modelo <strong>SOLO</strong> describe cinco niveles de complejidad creciente en el aprendizaje:</p>
<div class="solo-scale">
  <div><span>1</span>Preestructural</div>
  <div><span>2</span>Uniestructural</div>
  <div><span>3</span>Multiestructural</div>
  <div><span>4</span>Relacional</div>
  <div><span>5</span>Abstracto ampliado</div>
</div>
</div>

<div class="grading-panel" data-site-key="intercultural">
  <div class="gp-row">
    <label class="gp-label" for="gp-name">👤 Estudiante / grupo</label>
    <input type="text" id="gp-name" class="gp-input" placeholder="Nombre del estudiante o grupo">
  </div>
  <div class="gp-scores">
    <div class="gp-score-item"><span class="gp-score-label">Entrega 1 (30%)</span><span class="gp-score-value" id="gp-score-0">—</span></div>
    <div class="gp-score-item"><span class="gp-score-label">Entrega 2 (30%)</span><span class="gp-score-value" id="gp-score-1">—</span></div>
    <div class="gp-score-item"><span class="gp-score-label">Entrega 3 (40%)</span><span class="gp-score-value" id="gp-score-2">—</span></div>
    <div class="gp-score-item gp-final"><span class="gp-score-label">Nota final</span><span class="gp-score-value" id="gp-final">—</span></div>
  </div>
  <div class="gp-actions">
    <button type="button" id="gp-save" class="gp-btn gp-btn-primary">💾 Guardar y calificar siguiente</button>
    <button type="button" id="gp-reset" class="gp-btn">↺ Limpiar selección</button>
  </div>
</div>
<div class="gp-toast" id="gp-toast"></div>

<div class="rubric-activity">
<h2>P1 · Protocolo Ético y Diagnóstico Participativo — Corte 1 (30%) · Sesión 2</h2>
<p>El peso entre paréntesis en cada criterio corresponde a su participación dentro de esta entrega. Ver detalle en <a href="{{ '/proyecto.html' | relative_url }}#p1">Proyecto de aula</a>.</p>
<div class="weight-bar">
  <div class="w1" style="width:15%;">15%</div>
  <div class="w2" style="width:25%;">25%</div>
  <div class="w3" style="width:35%;">35%</div>
  <div class="w4" style="width:25%;">25%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Caracterización del colectivo</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Protocolo ético e intercultural</span>
  <span><span class="dot" style="background:var(--amber);"></span>Diagnóstico participativo</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Co-diseño de la propuesta</span>
</div>
</div>

<div class="rubric-wrap">
<table class="rubric irubric" data-entrega="0" data-weight="30">
<thead><tr>
<th>Criterio</th>
<th>1 · Preestructural</th>
<th>2 · Uniestructural</th>
<th>3 · Multiestructural</th>
<th>4 · Relacional</th>
<th>5 · Abstracto ampliado</th>
<th class="irc-score-col">Nota</th>
</tr></thead>
<tbody>
<tr class="irc" data-weight="15">
<td class="irc-crit-cell">
<span class="irc-name">Caracterización del colectivo</span><span class="irc-weight">15%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No se identifica el colectivo, o la elección no está justificada ni contextualizada.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Nombra al colectivo, sin describir su contexto territorial, social o cultural.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Describe el contexto territorial, social y cultural de forma general, con justificación breve de la elección.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La caracterización sitúa al colectivo en su contexto real (territorio, dinámicas sociales y culturales concretas) y justifica con evidencia por qué se eligió.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La caracterización muestra conocimiento situado del colectivo, construido con fuentes propias del territorio (no solo bibliografía general), y anticipa cómo ese contexto condicionará el resto del proyecto.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Protocolo ético e intercultural</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay evidencia de consentimiento ni de estrategia de contacto; se aborda al colectivo sin explicar el ejercicio académico.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona que pidió permiso o hizo contacto, sin describir el proceso de consentimiento/asentimiento.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Describe una estrategia de contacto y un proceso de consentimiento genéricos, sin adaptarlos al lenguaje y dinámica del colectivo concreto.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El protocolo está adaptado al colectivo real: describe la construcción de confianza, el consentimiento/asentimiento en su propio lenguaje, y acuerdos claros sobre uso ético de la información.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El protocolo se construye junto con el colectivo (no solo se les informa), incluye acuerdos explícitos de reciprocidad y respeto a su autonomía, con evidencia real del encuentro de acercamiento.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Diagnóstico participativo y diálogo de saberes</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">El problema se describe sin ninguna herramienta participativa ni evidencia de que el colectivo lo haya priorizado.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Nombra herramientas participativas (cartografía social, círculos de palabra, entrevistas abiertas) sin evidencia de haberlas aplicado.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Aplica al menos una herramienta participativa con evidencia real (registro, notas, productos), sin explicitar los criterios comunitarios de priorización.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El diagnóstico integra evidencia real de la(s) herramienta(s) participativas aplicadas y explicita los criterios que el propio colectivo usó para priorizar el problema (en salud o en pérdida de saberes culturales).</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El diagnóstico articula el problema priorizado con una lectura crítica de su determinación social (dimensiones general, particular y singular), mostrando diálogo de saberes genuino — no una consulta que solo valida lo que el estudiante ya pensaba.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Co-diseño de la micro-propuesta</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="1" data-score="1.0">
<span class="irc-opt-desc">La intervención es propuesta unilateralmente por el estudiante, sin participación del colectivo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona participación, pero la propuesta sigue siendo definida por el estudiante; no hay roles compartidos.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="3" data-score="3.0">
<span class="irc-opt-desc">El colectivo participa validando una propuesta ya elaborada; se listan tareas, pero sin roles claros.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El planteamiento preliminar es viable en 2 a 3 semanas y define roles y tareas compartidas reales entre estudiantes e integrantes del colectivo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El co-diseño integra saberes académicos y locales en igualdad de condiciones, es viable con los recursos reales del colectivo, y deja evidencia (acta, registro) del acuerdo compartido sobre roles.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
</tbody>
</table>
</div>
<div class="irc-result" id="irubric-result-0">Sin calificar aún</div>

<div class="rubric-activity">
<h2>P2 · Laboratorio de Avances y Reajuste Colaborativo — Corte 2 (30%) · Sesión 3</h2>
<p>Se entrega la Matriz de Avance Colaborativo y se socializa en un taller reflexivo en clase. No es trabajo de campo puro: es análisis crítico de la experiencia directa vivida entre sesiones, con evidencia real de lo ocurrido. Pueden apoyarse, de forma opcional, en la <a href="{{ '/herramientas/semaforo.html' | relative_url }}">herramienta interactiva del Semáforo</a> para el mapeo de tensiones y relaciones de poder.</p>
<div class="weight-bar">
  <div class="w1" style="width:30%;">30%</div>
  <div class="w2" style="width:40%;">40%</div>
  <div class="w3" style="width:30%;">30%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Reporte de campo y evidencias</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Mapeo de tensiones y relaciones de poder</span>
  <span><span class="dot" style="background:var(--amber);"></span>Plan de reajuste y cierre</span>
</div>
</div>

<div class="rubric-wrap">
<table class="rubric irubric" data-entrega="1" data-weight="30">
<thead><tr>
<th>Criterio</th>
<th>1 · Preestructural</th>
<th>2 · Uniestructural</th>
<th>3 · Multiestructural</th>
<th>4 · Relacional</th>
<th>5 · Abstracto ampliado</th>
<th class="irc-score-col">Nota</th>
</tr></thead>
<tbody>
<tr class="irc" data-weight="30">
<td class="irc-crit-cell">
<span class="irc-name">Reporte de campo y evidencias</span><span class="irc-weight">30%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay registro de encuentros ni evidencias del trabajo de campo, o no son verificables.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona haber tenido contacto con el colectivo, sin registro ni evidencia concreta (fotos, notas, listas).</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Presenta registro básico de los encuentros (fechas, participantes), con evidencia fotográfica o documental mínima.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El reporte documenta con evidencia real (fotos, notas de campo, testimonios) cada encuentro y describe con precisión el nivel de involucramiento y apropiación del colectivo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El reporte permite verificar, con evidencia trazable y contextualizada, cómo evolucionó la apropiación del colectivo social encuentro a encuentro — no solo que "hubo participación".</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="40">
<td class="irc-crit-cell">
<span class="irc-name">Mapeo de tensiones y relaciones de poder</span><span class="irc-weight">40%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay análisis de poder; se describe el proceso como armónico y sin fricciones.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona que hubo tensiones o resistencias, sin analizarlas.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Identifica resistencias institucionales, comunitarias o epistémicas, pero de forma descriptiva y aislada.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">Analiza críticamente las asimetrías entre el saber técnico/salud pública y los saberes locales, conectándolas con las resistencias identificadas en campo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El mapeo revela relaciones de poder no evidentes al inicio del proyecto y muestra cómo estas redefinen el propio rol del estudiante como interviniente.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="30">
<td class="irc-crit-cell">
<span class="irc-name">Plan de reajuste y cierre</span><span class="irc-weight">30%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay reajuste; la propuesta continúa igual, sin relación con los hallazgos de campo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona un ajuste genérico, sin vincularlo con el mapeo de tensiones.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">El plan ajusta algún aspecto puntual de la intervención a partir de lo hallado en campo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El reajuste es trazable: cada modificación responde a un hallazgo concreto acordado con el colectivo, e incluye una estrategia definida de devolución simbólica para la sesión 4.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El plan de cierre demuestra autocrítica real: reconoce límites o errores propios del co-diseño inicial y cede al colectivo un papel activo en decidir cómo se hará la devolución.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
</tbody>
</table>
</div>
<div class="irc-result" id="irubric-result-1">Sin calificar aún</div>

<div class="rubric-activity">
<h2>P3 · Muestra de la Micro-Intervención y Debate Crítico — Corte 3 (40%) · Sesión 4</h2>
<p>Cierra el proyecto de aula. <strong>No se evalúa si la intervención "tuvo éxito"</strong>, sino si el estudiante logra un análisis crítico honesto sobre su carácter funcional o transformador, sustentado con evidencia real de la devolución comunitaria.</p>
<div class="weight-bar">
  <div class="w1" style="width:30%;">30%</div>
  <div class="w2" style="width:35%;">35%</div>
  <div class="w3" style="width:35%;">35%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Muestra tangible del producto</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Devolución y valoración comunitaria</span>
  <span><span class="dot" style="background:var(--amber);"></span>Fundamentación teórica y debate crítico</span>
</div>
</div>

<div class="rubric-wrap">
<table class="rubric irubric" data-entrega="2" data-weight="40">
<thead><tr>
<th>Criterio</th>
<th>1 · Preestructural</th>
<th>2 · Uniestructural</th>
<th>3 · Multiestructural</th>
<th>4 · Relacional</th>
<th>5 · Abstracto ampliado</th>
<th class="irc-score-col">Nota</th>
</tr></thead>
<tbody>
<tr class="irc" data-weight="30">
<td class="irc-crit-cell">
<span class="irc-name">Muestra tangible del producto</span><span class="irc-weight">30%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay producto tangible, o no corresponde a lo co-diseñado con el colectivo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se presenta el producto, pero sin relación clara con el proceso de co-diseño documentado en P1 y P2.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">El producto (cartilla, material audiovisual, mapa, protocolo, síntesis de taller, etc.) corresponde al diseño co-creado y se exhibe o reproduce en la sesión.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El producto refleja con calidad el proceso de co-diseño y el diálogo de saberes, y su formato es culturalmente pertinente para el colectivo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El producto es una pieza que el propio colectivo reconoce como suya y puede seguir usando después del curso — evidencia tangible de un aprendizaje mutuo, no solo de una tarea entregada.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Devolución y valoración comunitaria</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay evidencia de devolución de resultados al colectivo, ni testimonios.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona que hubo devolución, sin evidencia (fotos, registro, testimonios) que lo respalde.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Presenta evidencia básica del espacio de devolución (registro fotográfico o narrativo), con algún testimonio puntual.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La devolución está documentada con evidencia real y verificable, e incluye testimonios y retroalimentación directa de varios participantes sobre el proceso.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La valoración comunitaria muestra, con evidencia trazable desde P1 y P2, cómo cambió la relación entre estudiante y colectivo — y qué reconoce la propia comunidad como resultado del proceso.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Fundamentación teórica y debate crítico</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay análisis teórico, o la intervención se presenta como un éxito sin cuestionamiento alguno.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Nombra los conceptos de interculturalidad funcional y crítica (Walsh, Basail) sin aplicarlos al caso propio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Aplica de forma general uno de los dos análisis (funcional o crítico) al caso, sin profundizar en evidencia concreta de campo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">Argumenta con evidencia de campo si la intervención adaptó saberes locales sin modificar jerarquías (funcional) o si cuestionó/transformó relaciones de poder e inequidades epistémicas (crítica), fundamentado en Walsh y Basail.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El debate reconoce con honestidad los matices entre ambos polos — ninguna intervención real es puramente funcional o crítica — y señala qué se necesitaría para acercar la propia experiencia al polo crítico.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
</tbody>
</table>
</div>
<div class="irc-result" id="irubric-result-2">Sin calificar aún</div>

<div class="gp-savedlist-wrap">
<h2>📋 Calificaciones guardadas en este navegador</h2>
<p class="muted" style="font-size:13px; margin-top:-6px;">Se guardan localmente en este navegador (no se suben a ningún servidor). Usa "Copiar todo" para pegarlas en Excel u otra planilla.</p>
<div class="gp-savedlist-actions">
  <button type="button" id="gp-copy" class="gp-btn">📋 Copiar todo (para Excel)</button>
  <button type="button" id="gp-clearall" class="gp-btn gp-btn-danger">🗑 Borrar todas</button>
</div>
<div class="gp-table-wrap">
<table class="gp-table">
<thead><tr><th>Estudiante</th><th>Entrega 1 (30%)</th><th>Entrega 2 (30%)</th><th>Entrega 3 (40%)</th><th>Nota final</th><th></th></tr></thead>
<tbody id="gp-table-body"></tbody>
</table>
</div>
</div>

<div class="criteria-block">
<h3>🧭 Criterios transversales — presentes en las tres entregas</h3>
<dl>
  <dt>Evidencia real:</dt> <dd>todo lo afirmado (encuentros, consentimiento, avances, devolución) debe respaldarse con evidencia verificable, no solo narrada.</dd>
  <dt>Enfoque decolonial:</dt> <dd>cuestionamiento de estructuras de poder en salud.</dd>
  <dt>Diálogo de saberes:</dt> <dd>integración equilibrada de conocimientos académicos y tradicionales.</dd>
  <dt>Participación genuina:</dt> <dd>protagonismo real del colectivo en todo el proceso.</dd>
  <dt>Reflexividad:</dt> <dd>capacidad de autocrítica y aprendizaje continuo.</dd>
  <dt>Ética intercultural:</dt> <dd>respeto, reciprocidad y responsabilidad en la relación con el colectivo.</dd>
</dl>
</div>
