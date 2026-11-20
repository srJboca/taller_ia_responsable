# CUADERNO DE TRABAJO EJECUTIVO — LABORATORIO PRÁCTICO (SESIÓN 2)

**Taller:** La Responsabilidad en el Uso de Casos de Uso de IA  
**Facilitador:** John J Bocachica (`jbocachica@iwco.co` | `+57 310 689 0766`)  
**Duración del Laboratorio:** 25 Minutos + 15 Minutos de Debate Ejecutivo en Plenaria  
**Objetivo:** Transformar un caso de uso de IA con riesgos altos o críticos en una iniciativa gobernable, auditable y aprobable por un Comité Directivo.

---

## ⚠️ REGLA DE ORO ANTES DE EMPEZAR (SAFE SANDBOX)

Durante todo este laboratorio utilizarán una herramienta de IA Generativa (ChatGPT, Claude, Gemini o Copilot) como **copiloto de gobernanza**.

* **PROHIBIDO:** Ingresar nombres reales de su empresa, clientes, empleados, proveedores, sistemas internos propietarios o cifras financieras confidenciales.
* **OBLIGATORIO:** Si trabajan con un caso real de su organización, reemplacen los nombres por descripciones sectoriales (ej. *"Aseguradora mediana"*, *"Retail de consumo masivo"*) y las cifras por porcentajes o rangos aproximados.

---

## FASE 0: PREPARACIÓN DEL CASO BASE (Antes de iniciar el cronómetro)

Elijan en su mesa **un solo caso** para rediseñar hoy:

* **Opción A (Recomendada):** Un caso real anonimizado de la empresa de alguno de los integrantes de la mesa (ya sanitizado con el *Prompt #1* y clasificado en el Semáforo con el *Prompt #2*).
* **Opción B (Respaldo):** Retomen el *Business Case* que auditaron en la Sesión 1 (*Caso A: TalentPulse AI*, *Caso B: PriceSense AI* o *Caso C: ResolveBot Pro*).

> **Anoten aquí el título del caso elegido por la mesa:** _________________________________________________

---

## PASO 1: CO-CREACIÓN DE CANDADOS Y LÍNEAS ROJAS CON IA (10 Minutos)

**Instrucción:** En el mismo hilo de conversación donde cargaron la ficha técnica de su caso (o pegando la descripción del caso debajo del prompt), copien y ejecuten el **Prompt #3**:

```text
Actúa como Arquitecto Jefe de Gobernanza de IA y Director de Riesgos Corporativos.

Nuestro objetivo es rediseñar el flujo operativo del caso de uso que venimos analizando para que sea aprobable por nuestro Comité Directivo, sin destruir la agilidad ni la rentabilidad comercial del negocio.

Define con precisión ejecutiva:
1. Tres (3) Líneas Rojas innegociables que la IA nunca podrá cruzar (incluyendo datos o variables prohibidas, y acciones irreversibles que no puede ejecutar por sí sola).
2. El punto exacto de intervención humana (especificando si aplica Human-in-the-loop o Human-on-the-loop) y los 3 disparadores automáticos que obligan a escalar un caso a un supervisor humano.
3. El mecanismo formal de explicabilidad y apelación para que un cliente o empleado afectado por una decisión del algoritmo pueda solicitar revisión humana en menos de 48 horas.
```

### Checklist de revisión rápida en mesa (2 min):
* ¿Las 3 líneas rojas bloquean realmente el peor escenario de crisis que detectamos en la Sesión 1?
* ¿Queda claro qué pasa si la IA se equivoca un viernes a medianoche (botón de emergencia / *kill switch*)?

---

## PASO 2: VALIDACIÓN DE CRITERIO HUMANO Y ASIGNACIÓN DE DUEÑO (10 Minutos)

**Instrucción:** **Cierren o aparten las pantallas durante 10 minutos.** La IA ya propuso controles técnicos; ahora ustedes deben aplicar **criterio político, financiero y operativo** como altos directivos.

Debatan en la mesa y completen estas 3 definiciones (no delegables a la IA):

### 1. Prueba de Viabilidad Comercial (¿Sigue siendo buen negocio?)
* Si implementamos la supervisión humana que sugirió la IA, ¿el proyecto sigue generando retorno (ROI) y velocidad, o creamos un cuello de botella burocrático?
* *Ajuste acordado por la mesa:* ________________________________________________________________________

### 2. Designación del *Risk Owner* Único (Rendición de Cuentas)
* Prohibido asignar el riesgo a *"Comité de IA"*, *"Tecnología"* o *"el Proveedor"*. Debe ser un cargo ejecutivo único que responda con su gestión si el sistema falla.
* **Cargo Ejecutivo Designado como Risk Owner:** _________________________________________________________

### 3. Protocolo de Apagado (*Circuit Breaker*)
* ¿Qué métrica o alerta dispara el apagado inmediato del sistema y quién tiene la autoridad de presionar ese botón sin pedir permiso?
* **Umbral de apagado y responsable:** __________________________________________________________________

---

## PASO 3: SÍNTESIS EJECUTIVA PARA EL DEBATE EN PLENARIA (5 Minutos)

**Instrucción:** Vuelvan a su sesión de IA y ejecuten el **Prompt #4** incorporando el *Risk Owner* y los ajustes humanos que acordaron en el Paso 2:

```text
Sintetiza nuestro caso rediseñado en exactamente 3 puntos ejecutivos para compartir en un debate abierto con otros altos directivos (máximo 100 palabras en total, tono directo y sin jerga técnica):

1. El candado más crítico: Qué línea roja innegociable impusimos para evitar el peor riesgo del caso.
2. El equilibrio negocio-control: Cómo garantizamos supervisión humana activa sin frenar la rentabilidad ni la agilidad.
3. Rendición de cuentas: Quién es el Risk Owner único (incorporar explícitamente: [ESCRIBIR AQUÍ EL CARGO EJECUTIVO ACORDADO]) y qué lo obliga a apagar el sistema.
```

---

## FASE FINAL: DEBATE EJECUTIVO EN PLENARIA (15 Minutos)

Elijan a un **Portavoz** de la mesa. No haremos una presentación formal; abriremos un **debate directo entre pares** en plenaria alrededor de tres preguntas clave:

1. **¿Dónde estuvo el mayor choque entre rentabilidad y control?** *(¿Qué tuvieron que recortarle a la propuesta de la IA para que fuera viable en sus empresas?)*
2. **¿Quién asumió realmente el riesgo?** *(¿Hubo consenso en la mesa sobre qué cargo ejecutivo debe ser el Risk Owner, o intentaron delegarlo a Tecnología/Proveedor?)*
3. **¿Qué punto ciego sigue abierto?** *(Intercambio cruzado: ¿qué vulnerabilidad ven las otras mesas en los candados propuestos?)*

### Hoja de Registro de Conclusiones de la Mesa:
* **Caso rediseñado:** _________________________________________________________________________________
* **El aprendizaje o dilema más fuerte del debate en mesa:** _______________________________________________
* **Estado final del proyecto tras el rediseño:** `[ ] LISTO PARA PILOTO CONTROLADO`   `[ ] REQUIERE MAYOR AUDITORÍA DE DATOS`
