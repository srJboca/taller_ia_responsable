# GUÍA DE BOLSILLO EJECUTIVA — GOBIERNO Y RESPONSABILIDAD EN IA
**Autor:** John J Bocachica (`jbocachica@iwco.co` | `+57 310 689 0766`)

> *"Delegar una decisión a un algoritmo jamás transfiere la responsabilidad legal, financiera ni reputacional del directivo."*

---

## 1. EL SEMÁFORO EJECUTIVO DE RIESGO (Clasificación en 60 Segundos)

| Nivel | Alcance del Caso de Uso | Supervisión Humana | Regla de Aprobación |
| :--- | :--- | :--- | :--- |
| **NIVEL 1 · BAJO** *(Verde)* | Productividad interna, resúmenes, borradores sin impacto externo. | **Revisión de usuario** *(Human-as-editor)* | Aprobación ágil por el líder del área. |
| **NIVEL 2 · MEDIO** *(Amarillo)* | Interacción externa asistida, recomendadores o atención al cliente con topes. | **Human-on-the-loop** *(Monitoreo activo + alertas)* | Piloto controlado + bases cerradas (RAG) + *Circuit Breaker*. |
| **NIVEL 3 · CRÍTICO** *(Rojo)* | Decisiones sobre personas, crédito, precios dinámicos o pagos autónomos. | **Human-in-the-loop** *(Firma humana obligatoria)* | Auditoría previa de datos + Comité Directivo + *Risk Owner* único. |

---

## 2. LAS 5 PREGUNTAS OBLIGATORIAS ANTES DE FIRMAR PRESUPUESTO

1. **DATOS Y SESGOS:** ¿Con qué histórico se entrenó el modelo y qué auditoría garantiza que no discrimina clientes o empleados?
2. **EXPLICABILIDAD:** Si un cliente, juez o regulador nos exige explicar por qué el sistema tomó una decisión, ¿podemos justificarlo sin responder *"es una caja negra del proveedor"*?
3. **PRIVACIDAD (SAFE SANDBOX):** ¿Está garantizado contractual y técnicamente que nuestros datos confidenciales no entrenan modelos públicos de terceros?
4. **PLAN B Y APELACIÓN:** ¿Existe un mecanismo de revisión humana en menos de 48 horas para el afectado y un botón de apagado inmediato (*Kill Switch*)?
5. **DUEÑO DEL RIESGO (*RISK OWNER*):** ¿Qué cargo ejecutivo único (con nombre propio, no un comité ni el área de TI) responde con su gestión si el sistema falla?

---

## 3. LIBRERÍA DE PROMPTS DE AUDITORÍA PARA SU COMITÉ DIRECTIVO
*(Recuerde la Regla de Oro: anonimice siempre nombres de empresa, clientes y cifras exactas antes de consultar).*

### A. Prompt "Abogado del Diablo" (Para evaluar cualquier caso de negocio nuevo)
```text
Actúa como Director de Riesgos Corporativos (CRO) y Auditor Legal experto en IA. Analiza este proyecto de IA que nos piden aprobar: [PEGAR RESUMEN ANONIMIZADO]. Dime: (1) Los 3 mayores puntos ciegos legales, reputacionales o financieros ocultos; (2) Qué podría salir catastóficamente mal en 6 meses; y (3) Las 3 preguntas más incómodas que debo hacerle al área solicitante antes de aprobar presupuesto.
```

### B. Prompt de Diseño de Candados (Para convertir un caso Nivel 3 en aprobable)
```text
Actúa como Arquitecto Jefe de Gobernanza de IA. Rediseña el flujo operativo de este caso para hacerlo aprobable sin destruir su rentabilidad. Define: (1) 3 Líneas Rojas que la IA nunca podrá cruzar; (2) El punto exacto de intervención humana y los disparadores automáticos de escalamiento; y (3) El protocolo de apelación para el usuario afectado.
```

---

## 4. MI HOJA DE RUTA DE 15 DÍAS (COMPROMISO DE LIDERAZGO)

* `[ ]` **Días 1–3 (Contención):** Emitir lineamiento ejecutivo prohibiendo cargar información confidencial en herramientas de IA públicas (*Shadow AI*).
* `[ ]` **Días 4–10 (Inventario):** Mapear los proyectos de IA activos o en compra en mi área y clasificarlos en Nivel 1, 2 o 3.
* `[ ]` **Días 11–15 (Gobierno):** Exigir las *5 Preguntas del Directivo* y la designación de un *Risk Owner* único en el próximo Comité.

**Mi acción concreta para ejecutar este lunes:** _________________________________________________________
