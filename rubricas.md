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
<h2>P1 · Diagnóstico y Micro-Propuesta — Corte 1 (30%) · Sesión 2</h2>
<p>El peso entre paréntesis en cada criterio corresponde a su participación dentro de esta entrega. Ver detalle en <a href="{{ '/proyecto.html' | relative_url }}">Proyecto de aula</a>.</p>
<div class="weight-bar">
  <div class="w1" style="width:25%;">25%</div>
  <div class="w2" style="width:35%;">35%</div>
  <div class="w3" style="width:25%;">25%</div>
  <div class="w4" style="width:15%;">15%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Protocolo ético</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Diagnóstico sociocultural</span>
  <span><span class="dot" style="background:var(--amber);"></span>Co-diseño</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Fundamentación teórica</span>
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
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Protocolo de acercamiento ético</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay evidencia de consentimiento; se aborda a la comunidad sin explicar el ejercicio académico.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona que pidió permiso, pero sin describir cómo ni con qué metodología.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Describe el consentimiento y el primer contacto de forma genérica, sin adaptarlo a la comunidad específica.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El protocolo está adaptado a la comunidad concreta y articula consentimiento informado con una metodología participativa clara.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El protocolo se construye junto con la comunidad (no solo se les informa) y anticipa cómo se retribuirá su participación al cierre.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Diagnóstico sociocultural</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">El problema se describe de forma biomédica/causal, sin ninguna lectura sociocultural.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona la epidemiología crítica como concepto, sin aplicarla al caso.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Aplica la epidemiología crítica de forma parcial: identifica determinantes, pero como lista aislada.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El diagnóstico articula la determinación social del problema (Breilh) con lo que la comunidad identificó como prioritario.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El diagnóstico comprende el problema como proceso de determinación social —articulando las dimensiones general (estructuras de poder e historia), particular (modos de vida del colectivo) y singular (cuerpos y biografías)— sin reducirlo a una cadena de causas y efectos.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Co-diseño de la intervención</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">La intervención es propuesta unilateralmente por el estudiante, sin participación de la comunidad.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona participación, pero la propuesta sigue siendo definida por el estudiante.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">La comunidad participa validando una propuesta ya elaborada.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La priorización y el diseño de la intervención se construyen conjuntamente con la comunidad desde el inicio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El co-diseño integra saberes académicos y locales en igualdad de condiciones, y es viable con los recursos reales de la comunidad.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="15">
<td class="irc-crit-cell">
<span class="irc-name">Fundamentación teórica</span><span class="irc-weight">15%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay referencia teórica o es incorrecta.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Nombra a Walsh, Basail o Breilh sin desarrollar sus ideas.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Explica correctamente uno de los tres referentes, aplicado de forma general.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="4" data-score="4.0">
<span class="irc-opt-desc">Articula coherentemente dos o más referentes (Walsh, Basail, Breilh) con el caso propio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e0-c3" data-level="5" data-score="5.0">
<span class="irc-opt-desc">Usa el marco decolonial para cuestionar críticamente su propio lugar como interviniente, no solo para justificar la intervención.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
</tbody>
</table>
</div>
<div class="irc-result" id="irubric-result-0">Sin calificar aún</div>

<div class="rubric-activity">
<h2>P2 · Semáforo Intercultural — Corte 2 (30%) · Sesión 3</h2>
<p>Se trabaja en clase con la <a href="{{ '/herramientas/semaforo.html' | relative_url }}">herramienta interactiva del Semáforo</a>. No es trabajo de campo: es análisis crítico de experiencias, propias y de referencia.</p>
<div class="weight-bar">
  <div class="w1" style="width:25%;">25%</div>
  <div class="w2" style="width:35%;">35%</div>
  <div class="w3" style="width:25%;">25%</div>
  <div class="w4" style="width:15%;">15%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Identificación de experiencias</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Clasificación crítica</span>
  <span><span class="dot" style="background:var(--amber);"></span>Análisis reflexivo</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Refinamiento de propuesta</span>
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
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Identificación de experiencias</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No identifica experiencias o son irrelevantes al problema propio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Identifica 1 experiencia, sin contexto suficiente.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Identifica 3 experiencias, pero con descripciones superficiales de contexto y metodología.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">Las 3 experiencias están bien contextualizadas y su metodología está claramente caracterizada.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La selección incluye experiencias diversas (local, nacional, internacional) que iluminan distintas dimensiones del problema propio.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Clasificación crítica</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No usa el semáforo o lo aplica sin criterio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Clasifica las experiencias, pero sin justificación.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Justifica la clasificación con descripciones, sin analizar relaciones de poder.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La clasificación se justifica analizando explícitamente quién cede o retiene poder en cada experiencia.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El análisis revela matices dentro de cada experiencia — ninguna es puramente roja o verde — y lo argumenta con evidencia.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="25">
<td class="irc-crit-cell">
<span class="irc-name">Análisis reflexivo</span><span class="irc-weight">25%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay reflexión, solo la clasificación.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Menciona qué evitar, mejorar o integrar de forma genérica.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Identifica elementos concretos a evitar, mejorar e integrar, pero de forma aislada entre categorías.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El análisis conecta los elementos rojos, amarillos y verdes con decisiones concretas para la propia intervención.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El análisis transforma la mirada del propio proyecto: el estudiante reconoce riesgos de cooptación en su propuesta inicial.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="15">
<td class="irc-crit-cell">
<span class="irc-name">Refinamiento de la propuesta</span><span class="irc-weight">15%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c3" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay refinamiento; la propuesta queda igual.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c3" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona un ajuste, sin relación clara con el análisis del semáforo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c3" data-level="3" data-score="3.0">
<span class="irc-opt-desc">La propuesta se ajusta en algún aspecto puntual a partir del semáforo.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c3" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El refinamiento es coherente y trazable: se ve qué aprendizaje del semáforo generó qué cambio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e1-c3" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El refinamiento mueve la propuesta hacia el polo crítico/verde, cediendo más protagonismo real a la comunidad.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
</tbody>
</table>
</div>
<div class="irc-result" id="irubric-result-1">Sin calificar aún</div>

<div class="rubric-activity">
<h2>P3 · Entrega final del proceso intercultural — Corte 3 (40%) · Sesión 4</h2>
<p>Cierra el proyecto de aula. <strong>No se evalúa si la intervención "tuvo éxito"</strong>, sino si el estudiante logra un análisis crítico honesto sobre su carácter funcional o transformador.</p>
<div class="weight-bar">
  <div class="w1" style="width:35%;">35%</div>
  <div class="w2" style="width:30%;">30%</div>
  <div class="w3" style="width:20%;">20%</div>
  <div class="w4" style="width:15%;">15%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Ejecución de la intervención</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Documentación integral</span>
  <span><span class="dot" style="background:var(--amber);"></span>Evaluación participativa</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Análisis crítico decolonial</span>
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
<tr class="irc" data-weight="35">
<td class="irc-crit-cell">
<span class="irc-name">Ejecución de la micro-intervención</span><span class="irc-weight">35%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No se ejecutó la intervención, o se hizo sin la comunidad.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se ejecutó, pero difiere sustancialmente del diseño co-creado.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Se ejecutó fielmente al diseño, con participación de la comunidad en al menos un momento.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La ejecución respeta los protocolos comunitarios y mantiene participación activa durante todo el proceso.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c0" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La ejecución integra saberes tradicionales como parte constitutiva de la acción, no solo como consulta previa.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="30">
<td class="irc-crit-cell">
<span class="irc-name">Documentación integral</span><span class="irc-weight">30%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay documentación, o es mínima.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Hay registro fotográfico, sin documento ni testimonios.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="3" data-score="3.0">
<span class="irc-opt-desc">El documento describe la experiencia con evidencia fotográfica básica.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="4" data-score="4.0">
<span class="irc-opt-desc">La documentación es integral: documento completo, registro sistemático y testimonios contextualizados.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c1" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La documentación permite por sí misma comprender — y eventualmente replicar — el proceso con otra comunidad.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="20">
<td class="irc-crit-cell">
<span class="irc-name">Evaluación participativa</span><span class="irc-weight">20%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No se recoge retroalimentación de la comunidad.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona que hubo retroalimentación, sin detalle.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Se recoge retroalimentación puntual, sin analizar impactos ni cambios.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="4" data-score="4.0">
<span class="irc-opt-desc">Se analiza sistemáticamente qué cambió y qué aprendieron ambas partes — estudiante y comunidad.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c2" data-level="5" data-score="5.0">
<span class="irc-opt-desc">La evaluación participativa influye en cómo el estudiante interpreta y cierra su propio proceso de aprendizaje.</span>
</label>
</td>
<td class="irc-row-score">—</td>
</tr>
<tr class="irc" data-weight="15">
<td class="irc-crit-cell">
<span class="irc-name">Análisis crítico decolonial</span><span class="irc-weight">15%</span>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c3" data-level="1" data-score="1.0">
<span class="irc-opt-desc">No hay análisis crítico; se describe la intervención como un éxito sin cuestionamiento.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c3" data-level="2" data-score="2.0">
<span class="irc-opt-desc">Se menciona si "funcionó" o no, sin marco decolonial.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c3" data-level="3" data-score="3.0">
<span class="irc-opt-desc">Se aplica el marco decolonial de forma general, sin conectarlo con el caso propio.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c3" data-level="4" data-score="4.0">
<span class="irc-opt-desc">El debate está fundamentado con Walsh y Basail y se aplica específicamente al caso propio, identificando tensiones reales.</span>
</label>
</td>
<td class="irc-opt">
<label>
<input type="radio" name="intercultural-e2-c3" data-level="5" data-score="5.0">
<span class="irc-opt-desc">El análisis reconoce con honestidad si la intervención fue más funcional que crítica, y qué se necesitaría para transformarla en una acción que ceda poder real.</span>
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
  <dt>Enfoque decolonial:</dt> <dd>cuestionamiento de estructuras de poder en salud.</dd>
  <dt>Diálogo de saberes:</dt> <dd>integración equilibrada de conocimientos académicos y tradicionales.</dd>
  <dt>Participación genuina:</dt> <dd>protagonismo real de la comunidad en todo el proceso.</dd>
  <dt>Reflexividad:</dt> <dd>capacidad de autocrítica y aprendizaje continuo.</dd>
  <dt>Ética intercultural:</dt> <dd>respeto, reciprocidad y responsabilidad en la relación con la comunidad.</dd>
</dl>
</div>
