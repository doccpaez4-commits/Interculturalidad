---
layout: default
title: Contenidos
---

<h1>Ruta de aprendizaje: la micro-intervención piloto</h1>
<p class="lede">4 sesiones presenciales + 2 fases de trabajo de campo · {{ site.data.curso.horario_general }} · {{ site.data.curso.salon }}</p>

<div class="callout">
  Toda la asignatura gira en torno a un único hilo conductor: co-diseñar, ejecutar y analizar críticamente una <strong>micro-intervención piloto</strong> con una comunidad, familia o colectivo real. Cada sesión presencial entrega un insumo del microcurrículo; cada fase intersesión es trabajo de campo que alimenta la siguiente entrega.
</div>

{% assign s = site.data.curso.sesiones %}

<div class="timeline-strip">
  <a href="#s1"><span class="tl-icon">1</span><span class="tl-label">Preparación</span></a>
  <a href="#s2"><span class="tl-icon">2</span><span class="tl-label">Diagnóstico<br>y co-diseño</span></a>
  <a href="#campo1" class="field"><span class="tl-icon">🌱</span><span class="tl-label">Campo I</span></a>
  <a href="#s3"><span class="tl-icon">3</span><span class="tl-label">Semáforo<br>intercultural</span></a>
  <a href="#campo2" class="field"><span class="tl-icon">🌱</span><span class="tl-label">Campo II</span></a>
  <a href="#s4"><span class="tl-icon">4</span><span class="tl-label">Entrega final<br>y debate</span></a>
</div>

<div class="route-track">

<div class="route-step" id="s1" data-step="1">
  <div class="unit-card">
    <span class="step-tag">Sesión 1 · {{ s[0].fecha }}</span>
    <h3>🎓 Preparación</h3>
    <p><strong>Temas del microcurrículo:</strong> procesos de salud-enfermedad y cuidado desde la cultura · pluralismo médico · fundamentos teóricos interculturales.</p>
    <p><strong>Objetivo:</strong> fundamentar teóricamente el pluralismo médico y preparar el acercamiento ético a la comunidad, con el legado de Héctor Abad Gómez como referente de salud pública situada.</p>
    <div class="update-block" style="background:#eef6ff; border-color:#bfdcff; border-left-color:#2563eb; margin-top:14px;">
      <h3 style="color:#1d4ed8;">🎯 Tarea previa a la sesión 2</h3>
      <ol style="margin:0; padding-left:20px;">
        <li>Elegir la comunidad, familia o colectivo con quien se trabajará todo el curso.</li>
        <li>Elaborar el <strong>Protocolo de Acercamiento Ético-Intercultural</strong> (consentimiento, forma de contacto, compromisos de retribución).</li>
        <li>Realizar el primer contacto e identificar, junto con la comunidad, 3 problemas prioritarios de salud.</li>
      </ol>
    </div>
  </div>
</div>

<div class="route-step" id="s2" data-step="2">
  <div class="unit-card">
    <span class="step-tag">Sesión 2 · {{ s[1].fecha }}</span>
    <h3>🔍 Diagnóstico y co-diseño</h3>
    <p><strong>Temas del microcurrículo:</strong> ¿por qué la salud intercultural en salud pública? · diversidad cultural, multiculturalidad e interculturalidad · epidemiología crítica (Breilh).</p>
    <p><strong>Objetivo:</strong> aplicar la epidemiología crítica para leer el problema elegido desde la determinación social —sus dimensiones general, particular y singular, no una cadena de causas— y co-diseñar, con la comunidad, una intervención viable.</p>
    <div class="update-block" style="margin-top:14px;">
      <h3>🎯 Entrega 1 — P1: Diagnóstico y Micro-Propuesta (30%)</h3>
      <p style="margin-bottom:0;">Documento con el diagnóstico sociocultural crítico, el problema priorizado junto con la comunidad, y la micro-propuesta de intervención co-diseñada. Ver <a href="{{ '/proyecto.html' | relative_url }}">Proyecto de aula</a> y <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — P1</a>.</p>
    </div>
  </div>
</div>

<div class="route-step field" id="campo1" data-step="🌱">
  <div class="field-card">
    <span class="step-tag">Entre sesión 2 y 3 · trabajo de campo</span>
    <h3>Fase de aplicación I</h3>
    <p>Ejecución de la micro-intervención piloto diseñada, en el territorio o con el colectivo elegido: implementación real, documentación de evidencia (fotos, videos, testimonios) y registro de listas de asistencia. Este trabajo alimenta directamente el Semáforo Intercultural de la sesión 3.</p>
  </div>
</div>

<div class="route-step" id="s3" data-step="3">
  <div class="unit-card">
    <span class="step-tag">Sesión 3 · {{ s[2].fecha }}</span>
    <h3>🚦 Avances y semáforo intercultural</h3>
    <p><strong>Temas del microcurrículo:</strong> avances en la salud intercultural en salud pública · experiencias en América Latina · experiencias en Colombia y el mundo.</p>
    <p><strong>Objetivo:</strong> analizar críticamente experiencias interculturales comparadas, usando el semáforo intercultural, para refinar el piloto propio antes de su cierre.</p>
    <div class="update-block" style="margin-top:14px;">
      <h3>🎯 Entrega 2 — P2: Semáforo Intercultural, trabajo en clase (30%)</h3>
      <p style="margin-bottom:0;">Análisis de 3 experiencias interculturales (propia o de referencia) con clasificación crítica 🔴🟡🟢 y refinamiento de la micro-propuesta. Se trabaja en clase con la <a href="{{ '/herramientas/semaforo.html' | relative_url }}">herramienta interactiva del Semáforo</a>. Ver <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — P2</a>.</p>
    </div>
  </div>
</div>

<div class="route-step field" id="campo2" data-step="🌱">
  <div class="field-card">
    <span class="step-tag">Entre sesión 3 y 4 · trabajo de campo</span>
    <h3>Fase de aplicación II</h3>
    <p>Continuación y cierre de la micro-intervención a la luz del refinamiento hecho con el semáforo: se documenta evidencia adicional y se recopila retroalimentación directa de la comunidad, insumo central para la entrega final.</p>
  </div>
</div>

<div class="route-step" id="s4" data-step="4">
  <div class="unit-card">
    <span class="step-tag">Sesión 4 · {{ s[3].fecha }}</span>
    <h3>🎤 Entrega final y debate crítico</h3>
    <p><strong>Temas del microcurrículo:</strong> retos contemporáneos de la salud intercultural en salud pública · dificultades y desafíos · debates contemporáneos.</p>
    <p><strong>Objetivo:</strong> presentar la recopilación completa del proceso y debatir críticamente la experiencia — no si la intervención "funcionó", sino si logró transformar relaciones de poder o solo adaptó la biomedicina sin cederlo.</p>
    <div class="update-block" style="margin-top:14px;">
      <h3>🎯 Entrega 3 — P3: Entrega final del proceso intercultural (40%)</h3>
      <p style="margin-bottom:0;">Recopilación completa del trabajo de micro-intervención: ejecución, documentación integral, evaluación participativa con la comunidad y análisis crítico decolonial, cerrado con un debate en clase: <em>¿intervención funcional o crítica?</em> Ver <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — P3</a>.</p>
    </div>
  </div>
</div>

</div>
