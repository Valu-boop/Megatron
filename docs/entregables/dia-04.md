---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E4"
dia: 4
responsable_registro: "equipo"
estado: "Megatron"
fecha: "29/10/2026"
revision_docente: "PENDIENTE"
---

# E4 · Día 4 — ITERAR | Kaizen 2, robustez y preparación de demostración

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E4.md`.

## 0 · Contexto

**Fecha y dōjō:** [29/10/2026] · **Equipo/misión:** [...] · **Versiones trazables:** V1 [id], K1 [id] y K2 [id pendiente].

## 1 · Ruta de actividades del Día 4 (180 min)

| Actividad | Minutos | Registro requerido |
|---|---:|---|
| Revisión por pares y retroalimentación | 0–20 | [observaciones de equipo: Mala soladura de los pines y arrancador] |
| Diseño/ejecución Kaizen 2 | 20–70 | [Hipótesis: El arrancador debe tener una posición establecida, Modificación: Se desoldó y se volvió a considerar su posición en l atrajeta.] |
| Comparación V1–K1–K2 | 70–115 | [Varios cambios de posicionamiento] |
| Ensayo de robustez | 115–145 | [Aun no hay prubas] |
| Preparación de demo | 145–165 | [Responsables: Abril y Valentina, Contingencia: Mal acomodo de pines y arrancador] |
| Gate de preparación | 165–180 | [decisión: No soldar directamente el arrancador a la placa y pendientes: Conseguir un pin hembra para soldar el pin y poder mover el arrancador (despues en competencias se necesita mover)] |

## 2 · Revisión por pares

| Persona o equipo observador (alias) | Evidencia revisada | Observación útil / pregunta | Respuesta técnica y decisión | Cambio aceptado o descartado |
|---|---|---|---|---|
| [Todos] | [Las concesiones del motor y sensores no ] | [No embonan bien del lado positivo ni negativo] | [Desoldar, acomodarlos y volver a soldar] | [Aceptado: Utilizar los mismo pines, Rechazado: Usar otros mas pequeños] |

**Acuerdo de colaboración:** [Abril y Valentina desoldaron los componentes, Santino decidió el orden del nuevo acomodo y se volvieron a soldar.].

## 3 · Segundo ciclo Kaizen (K2)

| Campo experimental | Completar |
|---|---|
| Limitación o nueva oportunidad detectada en K1 | [Escuchar comentarios de compañeros de otros mini sumo, nos ayudo a tener otras ideas de acomodo de componentes] |
| Hipótesis K2 y fundamento | [El acomodo mas estético no siempre es el mas fincional] |
| Variable modificada y controles | [Se modifico la soldadura directa del arrancador por una soldadura directa en un pin hembra a la placa y sobre ese el arrancador] |
| Requisitos de seguridad antes del cambio | [Revisar si es funcional nuestra propuesta] |
| Personas responsables y alcances implicados | [Valentina, Abril] |
| Cambio exacto de código/CAD/configuración | [Configuración en los componentes] |
| Enlace a commit, PR y versión K2 | [...] |
| Métrica, unidad y criterio para declarar éxito | [Que sea completamente funcional el arrancador y que pueda ser intercambiable] |

## 4 · Comparación de evolución

| Ensayo/condición equivalente | V1 (valor + unidad) | K1 (valor + unidad) | K2 (valor + unidad) | Incidencias o validez |
|---:|---|---|---|---|
| 1 | [...] | [...] | [...] | [...] |
| 2 | [...] | [...] | [...] | [...] |
| 3 | [...] | [...] | [...] | [...] |
| 4 | [...] | [...] | [...] | [...] |
| 5 | [...] | [...] | [...] | [...] |

**Registros fuente:** [`datos/ensayos.csv`](../../datos/ensayos.csv) y protocolo [enlace].

**Síntesis (método, n, media/mediana, dispersión y éxito cuando proceda):** [...].

**¿Qué mejora, qué empeora y qué no podemos concluir?** [Aun no hacemos pruebas medibles].

## 5 · Ensayo de robustez o variación de condiciones

| Cambio controlado de entorno (luz, suelo, batería, posición, rival, obstáculo o carga) | Riesgo y límite seguro | Predicción | Resultado / unidad / éxitos | ¿Se mantiene el objetivo? | Evidencia |
|---|---|---|---|---|---|
| [Posicion de los componentes] | [Riesgo: Que no funcione] | [El nuevo acomodo funciona perfecto y todo encaja bien en laplaca] | [pendiente] | [Si] | [...] |

**Límites de inferencia:** [Cuántas pruebas; si el cambio de entorno impide comparar directamente V1–K2; qué repetir].

## 6 · Ensayo general de demostración

| Segmento | Qué se demostrará en 20–60 s | Integrante responsable | Versión/código usado | Material requerido | Plan B ante fallo |
|---|---|---|---|---|---|
| Inicio / contexto | [Mal acomodo de lo pines, no entran] | [Que entren bien] | [Valentina] | [Sin codigo] | [Comprar mas pines] |
| Prueba principal | [Embonarlos sin presion] | [Abril] | [Sin codigo] | [Usar pines nuevos] | [...] |
| Evidencia de mejora | [Fotos] | [...] | [...] | [...] | [...] |
| Defensa de fronteras | [...] | [...] | [...] | [...] | [...] |

**¿Robolympics es el evento externo posterior?** [Por confirmar]. Si es posterior, D5 documenta una **demostración/calificación interna**; no registrar participación externa como realizada.

## 7 · Gate E4

- [X] Existe un ciclo K2 explícito, con hipótesis, modificación y datos.
- [ ] Se conservan V1, K1, K2 y, en su caso, reversiones para reproducibilidad.
- [X] Se efectuó una prueba de robustez documentada o se justificó por qué no era segura/factible.
- [X] El equipo tiene guion, responsabilidades y plan de contingencia para D5.
- [X] Cada participante actualizó [E4 personal](../../participantes/_plantilla/dias/E4.md).

**Estado de preparación:** [LISTO / CON RESTRICCIONES / NO LISTO]. **Pendientes y responsables:** [...]. **Revisor:** [...].
