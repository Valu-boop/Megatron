---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E2"
dia: 2
responsable_registro: "Megatron"
estado: "PENDIENTE"
fecha: "27/10/2026"
revision_docente: "PENDIENTE"
---

# E2 · Día 2 — HACER | Primera integración funcional y línea base V1

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E2.md`.

## 0 · Identificación y continuidad

| Campo | Dato :
|---|---|
|  | [27/10/2026, Megatron, Hacer un mini sumo funcional y plataforma: Github] |
| Dōjō real y mesa/zona utilizada | [Laboratorio de electronica] |
| Estado del gate E1 / cambios desde D1 | [Todos de acuerdo y contruyendo el mini segun lo planeado] |
| Kit por integrante / compromisos modificados | [Compromisos por integrante iguales, material completo por Abril y Santino, algunas piezas de Camilo] |
| Materiales recibidos y pendientes | [IDs MAT del inventario; Abril. Material pendiente: ferrul] |
| Objetivo técnico del Día 2 | [Impresión 3D de la base y armado de la electronica] |

## 1 · Ruta de las actividades de hoy (180 min)

| Bloque | Minutos | Registro requerido / evidencia |
|---|---:|---|
| Revisión de misión y compromisos | 0–15 | [Misiones iniciadas: Santino (parte mecanica)] |
| Microlección aplicada | 15–35 | [Técnica: Soldadura de cables al motor, Recurso:Un pedazo de cable soldado a un motor, Pregunta: ¿Por qué es importante asegurar bien la soldadura y aislar los cables antes de conectar la batería?  ] |
| Katas de integración | 35–105 | [Valentina: Imprimio la base del mini sumo, buscocomponentes faltantes, pelo y soldo cables.
Abril: Modifico cables que ya estaban puestos en los motores y agrego unos nuevos. 
Santino: Acomodo los componentes en sus respectivos lugares y los soldó, listos para probar en el día 3 ] |
| Ensayos iniciales / línea base | 105–145 | [ensayos pendientes, mañana en el día 3 comenzaremos las pruebas] |
| Consolidación de evidencia | 145–170 | [ archivo CAD del github con modificaciones] |
| Gate E2 | 170–180 | [Objetivo: Tener un buen armado mecanico] |

## 2 · Microlección e integración por alcances

**Tema que resolvió un problema real del equipo:** [Megatron]. **Material / referencia utilizada:** [Cambio de cables del motor y aislamiento de los mismos.].

| Alias | Alcance | Kata seleccionado / nuevo | Acción técnica ejecutada | Archivo, commit o plano | Estado (pendiente/probado/bloqueado) | Dependencia de otro integrante |
|---|---|---|---|---|---|---|
| [Abril] | [MS03] | [Kata 2] | [Soldadura a las terminales del motor ] | [`../../codigo/...`] | [probado] | [Peso del chasis (Santino).]
|[Santino] | [MS03] | [Kata 2] | [Ensamble del chasis] | [`../../codigo/...`] | [probado] | [Impresion de la base (Valentina).]
[Valentina] | [MS03] | [Kata 2] | [Impresión y diseño CAD] | [`../../codigo/...`] | [probado] | [.]

## 3 · Estado de integración V1

| Subsistema | Entrada | Salida esperada | Responsable | Prueba de integración y observación | Evidencia |
|---|---|---|---|---|---|
| Estructura/mecánica | [2 motores, 2 llantas, 4 sensores IR, 2 sensores QTR, nagavaja, ] | [Chasis completo y funcional] | [Santino] | [Piezas colocadas en su lugar, observación: Cables mal soldados] | [...] |
| Energía y accionamiento | [Bateria, cables y driver ] | [Movimiento de las llantas] | [Valentina] | [Encender el robot y probar que los motores giren hacia adelante, atrás y en giros.] | [...] |
| Sensores/percepción | [Sensores IR] | [Señal de los bordos del Dojo] | [Abril] | [Concetar lo sensores y poner el mini en el Dojo] | [...] |
| Control/software | [Codigo] | [Enviar señales al driver del motor] | [..] | [Cargar el codigo y revisar que las variables coincidan con lo programado] | [...] |
| Integración global | [Todo lo anterior en conjunto] | [Un robot autonomo] | [Valentina, Santino y Abril] | [Poner el mini el el dojo y probarlo] | [...] |

**Versión identificable:** [commit SHA/etiqueta/firmware/CAD/paquete; no usar solo “última versión”]. **Comportamiento que SÍ demuestra V1:** [...]. **Lo que aún falla:** [...].

## 4 · Protocolo y línea base del robot (datos observados)

Completar también [`pruebas/protocolo.md`](../../pruebas/protocolo.md) y registrar datos crudos en [`datos/ensayos.csv`](../../datos/ensayos.csv).

| Campo de validez experimental | Respuesta obligatoria |
|---|---|
| Pregunta y resultado que se quiere medir | [...] |
| Métrica primaria + unidad (segundos, %, cm, rad, etc.) | [...] |
| Éxito/fallo (criterio cuantitativo u observable) | [...] |
| Lugar, configuración, pista/dohyō/estaciones/marcadores | [...] |
| Configuración del robot: batería, firmware y sensores | [...] |
| Condiciones controladas: luz, rival, posición de inicio, etc. | [...] |
| Número de corridas planeadas / ejecutadas | [... / ...; justificar si menos de 5] |
| Procedimiento reproducible, responsable y seguridad/aborto | [...] |
| Datos sin procesar y video/foto corta | [enlace a CSV y evidencias externas de acceso controlado] |

| Ensayo | Condición inicial | Valor (+ unidad) | Éxito/fallo | Observación relevante / incidencia |
|---:|---|---|---|---|
| 1 | [...] | [...] | [...] | [...] |
| 2 | [...] | [...] | [...] | [...] |
| 3 | [...] | [...] | [...] | [...] |
| 4 | [...] | [...] | [...] | [...] |
| 5 | [...] | [...] | [...] | [...] |

**Línea base resumida (no fabricada):** [n válido; media/mediana si aplica; dispersión; tasa de éxito; casos descartados y razón — no borrar ensayos desfavorables].

## 5 · Decisiones al cierre, bloqueos y Kaizen de mañana

| Fallo o cuello de botella observado | Hipótesis preliminar | Prioridad | Responsable | Material / apoyo necesario |
|---|---|---|---|---|
| [...] | [...] | [...] | [...] | [...] |

- [X] Hay prototipo V1, subsistema funcional verificable o fallo reproducible con condiciones registradas.
- [ ] Existen archivos fuente o evidencia técnica enlazada, además de videos de uso controlado cuando correspondan.
- [ ] Hay protocolo reproducible y valores basales con unidad o justificación de lo que no pudo medirse.
- [ ] Cada alumno actualizó su [E2 personal](../../participantes/_plantilla/dias/E2.md) con contribución propia y límite de capacidad actual.
- [ ] Se mantuvieron límites de seguridad y protección de datos.

**Gate E2:** [APROBADO]. **Revisor:** [...] **Fecha:** [...].

**Próxima prioridad de Kaizen 1:** [...]. **Enlace al commit/PR:** [...].
