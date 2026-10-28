---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E3"
dia: 3
responsable_registro: "Megatron"
estado: "PENDIENTE"
fecha: "28/10/2026"
revision_docente: "PENDIENTE"
---

# E3 · Día 3 — MEDIR Y APRENDER | Kaizen 1: ensayo, hipótesis y mejora

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E3.md`.

## 0 · Contexto de investigación de hoy

**Fecha/equipo/misión:** [28/10/2026] · **Dōjō exacto:** [...] · **Versión de partida:** [commit/etiqueta V1] · **Protocolo E2:** [enlace].

## 1 · Ruta del Día 3 (180 min)

| Actividad | Minutos | Evidencia a registrar |
|---|---:|---|
| Analizar un fallo real / demostración | 0–15 | [fallo observado; Se desarmo un sensor Ir] |
| Diseño del experimento | 15–40 | [hipótesis: Los sensores eran algo antiguos, riesgo: Falso monitoreo para el movimiento del robot] |
| Diagnóstico del prototipo V1 | 40–80 | [causa: Antiguedad y prueba discriminante: Concetamos los sensores para probarlo] |
| Kaizen 1: cambio técnico | 80–125 | [Prueba de los sensores] |
| Reensayo equivalente | 125–160 | [datos crudos V1 vs K1] |
| Documentar, debatir, reflejar | 160–180 | [Sensores funcionales ] |

## 2 · Problema, hipótesis y trazabilidad

| Campo | Completar |
|---|---|
| Fallo / oportunidad de mejora observada (con evidencia) | [Area de oportunidad: Mejora en acomodo de pins ] |
| Dónde se presenta y cuántas veces | [Se nos presentó el problema cuando estábamos listos para conectar los sensores IR, en total fueron 2 veces con este fallo] |
| Diagnóstico: causas alternativas que se consideraron | [Compramos pines más grandes para que fuera más sencillo acomodar los cables, se nos complico hacerlos entrar en la placa] |
| Hipótesis contrastable: **si cambio X, espero que Y ocurra porque Z** | [Si cambiamos los conectores, espero que sea mas facil hacer cambios de sensores] |
| Variable independiente que se modifica | [Los concetores] |
| Métrica de resultado con unidad y criterio de mejora | [...] |
| Variables que se mantendrán iguales | [Los pines] |
| Ensayos requeridos y forma de muestreo | [5 o n justificado] |
| Riesgo de sesgo/confusión y cómo se mitigará | [A la hora de programas puede haber confusion] |
| Parada de seguridad / condición de aborto | [Que la programacion de los valores adecuados] |

## 3 · Colaboración y cambio técnico Kaizen 1

| Alias y alcance | Kata asociado (código o propio) | Qué cambió exactamente | Por qué | Código/CAD/commit y responsable de revisión | Validación de interfaz |
|---|---|---|---|---|---|
| [Abril] | [...] | [Se mantuvo con la misma tarea] | [Ya estaba establecida inicialmente y esa era su funcion principal] | [...] | [...]
[Santino] | [...] | [Se mantuvo acomodando las piezas de la electronica para hacerlo funcionar bien] | [Se necesitaba revisar por segunda vez, gracias al problema de los pines y sensores] | [...] | [...]
[Valentina] | [...] | [Se modifico porque hacia falta apoyo para la soldadura de los componente] | [Se necesitaba ayuda] | [...] | [...]|

**Identificador de versión K1:** [...]. **Otras modificaciones involuntarias o perturbaciones:** [...].

## 4 · Ensayos comparables

**Enlace a datos crudos CSV:** [`../../datos/ensayos.csv`](../../datos/ensayos.csv) · **Protocolo:** [`../../pruebas/protocolo.md`](../../pruebas/protocolo.md).

| Prueba emparejada o bloque | Condición/escenario idéntico | V1, valor + unidad | K1, valor + unidad | Cambio / resultado | Incidencia o desviación |
|---:|---|---|---|---|---|
| 1 | [Cambio de tamaño de los pines] | [Mayor tamaño] | [...] | [Menor espacio en la placa] | [Desviacion y cambio en la forma del acomodo de los sensores QTR] |
| 2 | [...] | [...] | [...] | [...] | [...] |
| 3 | [...] | [...] | [...] | [...] | [...] |
| 4 | [...] | [...] | [...] | [...] | [...] |
| 5 | [...] | [...] | [...] | [...] | [...] |

**N válido V1 / K1:** [... / ...]. **Resumen, variabilidad y tasa de éxito:** [...]. **Incertidumbres/limitaciones:** [...].

## 5 · Interpretación y decisión

- **¿La evidencia respalda, contradice o no permite decidir la hipótesis?** [No, la hipotesis es clara, al cambiar los pines de tamaño hay menor espacio en la placa]
- **Si no hubo mejora, qué aprendimos:** [Aprendimos que siempre hay alternativas para mejorar el acomodo o elcodigo segun sea necesario]
- **¿Qué riesgo o compromiso generó el cambio?** [El riesgo de que el cable se desoldara]
- **Decisión:** [conservar K1 / revertir / revisar / recolectar más datos], con razón: [...]
- **Siguiente pregunta para Kaizen 2:** [Todo funciona correctamente en conjunto]

## 6 · Puerta de salida E3

- [ ] V1 y K1 tienen identificadores o referencias inequívocas.
- [X] La hipótesis está conectada con una medida y un problema diagnosticado.
- [X] Se documentó una modificación técnica y su responsable.
- [X] Ensayos y resultados mantienen condiciones comparables o exponen diferencias explícitamente.
- [X] La conclusión es honesta, incluso si el resultado es negativo.
- [X] Cada estudiante registró su [E3 personal](../../participantes/_plantilla/dias/E3.md).

**Gate E3:** [APROBADO / CONDICIONADO]. **Revisor:** [...]. **Enlace a PR/commit:** [...].
