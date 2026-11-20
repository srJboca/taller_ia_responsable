# MEMORANDO EJECUTIVO DE INVERSIÓN — SIMULACIÓN EN IA GENERATIVA
**Proyecto:** *TalentPulse AI* — Selección Automatizada y Predicción de Fuga de Talento  
**Código de Caso:** CASO A · Recursos Humanos  
**Área Solicitante:** Vicepresidencia de Talento y Cultura  
**Inversión Solicitada:** USD $185,000 (Implementación + Licenciamiento Año 1)  
**ROI Proyectado:** 340% en 14 meses (Ahorro estimado de USD $630,000/año)  

---

## 1. Resumen Ejecutivo de la Propuesta
La compañía recibe aproximadamente **45,000 currículums al año** para cubrir 320 vacantes corporativas y operativas. Actualmente, el equipo de atracción de talento tarda un promedio de **42 días** en cerrar una posición, generando costos ocultos por vacantes abiertas y sobrecarga operativa.

La Vicepresidencia de Talento solicita aprobación urgente para desplegar **TalentPulse AI**, una plataforma SaaS de inteligencia artificial que opera en dos frentes:
1. **Módulo de Criba Autónoma:** Filtra y descarta automáticamente el **80% de los candidatos** antes de que un reclutador humano revise el perfil.
2. **Módulo de Retención Predictiva:** Analiza la actividad digital interna de los empleados actuales para alertar a los gerentes sobre quién tiene alta probabilidad de renunciar en los próximos 90 días.

---

## 2. Arquitectura Operativa y Datos Utilizados

### A. Fuentes de Datos de Entrenamiento (Criba)
* **Histórico interno:** 12,000 expedientes de contratación y evaluaciones de desempeño de los últimos 5 años.
* **Perfil de éxito:** El modelo fue entrenado tomando como "candidato ideal" a los empleados que obtuvieron calificaciones sobresalientes (*Top Performers*) y permanecieron más de 3 años en la empresa.
* **Variables analizadas:** Trayectoria académica, vacíos laborales, cambios de empleo, palabras clave en el CV y puntuación en una prueba psicométrica automatizada de 15 minutos.

### B. Fuentes de Datos de Monitoreo (Retención)
* Metadatos de correo electrónico y mensajería corporativa (horarios de conexión, frecuencia de respuesta, participación en reuniones — *sin leer el contenido de los mensajes*).
* Registros de asistencia, solicitudes de vacaciones, cambios en uso de beneficios y evaluaciones trimestrales.

---

## 3. Promesa de Valor para el Negocio
* **Velocidad:** Reducción del tiempo de contratación de **42 días a 16 días** (-60%).
* **Productividad:** Liberación de **4,800 horas/año** del equipo de RR. HH. para enfocarse en entrevistas finales.
* **Retención:** Reducción proyectada del **18% en la rotación no deseada** de perfiles críticos mediante alertas tempranas a sus jefes directos.
* **Listo para operar:** El proveedor garantiza puesta en marcha en **3 semanas** bajo configuración estándar (*plug & play*).

---

## 4. Condiciones Actuales del Diseño (Lo que se pide aprobar hoy)
* **Nivel de autonomía:** El sistema envía automáticamente el correo de rechazo al 80% descartado sin revisión humana.
* **Explicabilidad:** El proveedor utiliza un algoritmo propietario de caja negra (*Deep Neural Network*). El sistema entrega un puntaje de compatibilidad del `0` al `100`, pero **no detalla las razones específicas** del descarte para proteger su propiedad intelectual.
* **Uso de alertas internas:** Cuando el módulo de retención marca a un empleado con *"Riesgo de Fuga > 75%"*, envía una notificación automática a su gerente directo recomendando *"revisar asignación de proyectos críticos y planes de ascenso"*.
* **Gobernanza:** No se ha designado un auditor interno; el proveedor realiza una revisión técnica anual.

---

## 5. Laboratorio Práctico en ChatGPT / IA Generativa (20 Minutos)

**Instrucción para la mesa:** Abran una sesión en ChatGPT (o su plataforma de IA corporativa). En lugar de analizar este caso solo en papel, **usarán la IA como un "Simulador de Estrés Ejecutivo"** para auditar el proyecto, descubrir sus puntos ciegos y poner a prueba sus decisiones.

> **⚠️ Regla de Seguridad (Shadow AI):** Este caso es ficticio y seguro para copiar/pegar. Recuerden que en la vida real nunca deben ingresar datos reales de empleados o candidatos en herramientas públicas.

### Paso 1: Cargar el Caso y Activar el Rol de "Abogado del Diablo" (5 min)
Copien y peguen el siguiente prompt junto con el texto de las secciones 1 a 4 de este memorando:

```text
Actúa como un Director de Riesgos Corporativos (CRO) y Auditor Legal experto en Gobernanza de Inteligencia Artificial. 

Acabo de recibir el siguiente Memorando Ejecutivo de Inversión para aprobar el proyecto "TalentPulse AI" en nuestra empresa. El proyecto promete un ROI del 340%, pero mi responsabilidad como alto directivo es detectar qué podría salir catastóficamente mal antes de firmar el presupuesto.

Analiza el caso y dime:
1. ¿Cuáles son los 3 mayores puntos ciegos legales, éticos o reputacionales ocultos en el diseño actual?
2. ¿Qué "profecías autocumplidas" o efectos perversos podría generar el módulo de retención en el clima laboral?
3. Si tuvieras que interpelar al VP de Talento en el Comité Directivo, ¿qué 3 preguntas incómodas le harías sobre la "caja negra" del proveedor y los datos históricos?

Aquí está el memorando:
[PEGAR AQUÍ LAS SECCIONES 1 A 4 DEL CASO]
```

### Paso 2: Simulación de Crisis (Roleplay de Regulador / Demanda) (7 min)
Una vez que la IA responda, ejecuten este segundo prompt para visualizar el impacto real si el proyecto sale a producción tal como está:

```text
Simulemos que aprobamos el proyecto sin cambios y han pasado 6 meses. 

Redacta dos escenarios cortos y realistas:
1. Una notificación formal de la Autoridad de Protección de Datos / Ministerio de Trabajo tras la denuncia de una candidata que fue rechazada automáticamente después de una licencia de maternidad y exige explicación algorítmica.
2. Un mensaje filtrado en redes sociales de un empleado de alto desempeño que descubrió que su jefe le quitó un ascenso porque el algoritmo lo marcó con "78% de riesgo de fuga".

Con base en esto, estima el impacto reputacional y legal frente al ahorro de USD $630,000 prometido.
```

### Paso 3: Diseño de Cláusulas y Salvaguardas Mínimas (5 min)
Si la mesa decide **PAUSAR CON CONDICIONES**, usen este tercer prompt para convertir el diagnóstico en exigencias contractuales concretas:

```text
Como Comité de Dirección, hemos decidido PAUSAR la aprobación hasta que se corrijan los riesgos. 

Redacta exactamente 4 condiciones innegociables (Cláusulas de Gobernanza) que debemos exigir al proveedor y al equipo interno de RR. HH. antes de liberar el presupuesto, cubriendo:
1. Nivel de supervisión humana (Human-in-the-loop).
2. Auditoría de sesgos en datos históricos.
3. Explicabilidad y derecho de apelación.
4. Uso ético de las alertas de retención.
```

---

## 6. Hoja de Veredicto de la Mesa (Para presentar en Plenaria)
Tras interactuar con la IA, debatan en equipo (3 min) y definan su postura final como directivos (recuerden que la IA sugiere, pero el Comité decide):

* **Veredicto Final de la Mesa:** `[ ] APROBAR`   `[ ] PAUSAR CON CONDICIONES`   `[ ] RECHAZAR`
* **El hallazgo más crítico que descubrieron (con o sin ayuda de la IA):** _______________________________________
* **La condición #1 innegociable para el proveedor:** _______________________________________
