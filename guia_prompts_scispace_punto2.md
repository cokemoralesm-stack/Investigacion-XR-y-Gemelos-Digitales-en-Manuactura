# Guía acelerada de prompts para resolver el Punto 2 con SciSpace

## Objetivo del ejercicio

Realizar un **análisis inicial del caso de estudio de Cognizant** usando SciSpace como apoyo, de modo que el alumno llegue rápidamente a una comprensión estructurada del caso antes de profundizar en fuentes externas.

> **Punto 2 adaptado:** Analizar inicialmente el caso seleccionado utilizando SciSpace.

---

# Flujo rápido recomendado — 10 a 15 minutos

## Paso 0. Preparación

1. Elegir un caso de estudio de Cognizant.
2. Guardar o copiar el contenido del caso en PDF o texto.
3. Cargar el documento en SciSpace.
4. Ejecutar los prompts de esta guía **en orden**.
5. Copiar los resultados relevantes en la plantilla final.

---

# Prompt maestro — análisis inicial completo

Copiar y pegar este prompt en SciSpace después de cargar el caso:

```text
Actúa como analista de casos empresariales y tecnológicos.

Analiza exclusivamente el documento que he cargado. No inventes información ni completes vacíos con supuestos no respaldados.

Quiero una primera lectura estructurada del caso.

Entrega el análisis en una tabla con las siguientes columnas:

1. Elemento
2. Hallazgo
3. Evidencia textual o dato del documento
4. Nivel de certeza: Alto / Medio / Bajo
5. Información que falta

Identifica como mínimo:

- organización o cliente involucrado;
- industria;
- contexto del caso;
- problema principal;
- problemas secundarios;
- objetivos declarados;
- actores o stakeholders;
- necesidades del cliente;
- restricciones;
- tecnologías o soluciones utilizadas;
- decisiones relevantes;
- proceso de implementación;
- resultados;
- métricas o KPI mencionados;
- beneficios declarados;
- riesgos;
- limitaciones;
- información que no aparece o que necesitaría verificación externa.

Al final agrega:

A. Resumen ejecutivo en máximo 150 palabras.
B. Cinco preguntas que deberían investigarse posteriormente.
C. Tres afirmaciones del caso que necesitan evidencia adicional o validación externa.

Para cada afirmación importante, indica dónde aparece en el documento (página, sección o fragmento identificable si la herramienta lo permite).
```

---

# Prompts específicos

## 1. Comprender el caso en 2 minutos

```text
Resume este caso como si tuvieras que explicárselo a un compañero en 90 segundos.

Usa exactamente esta estructura:

- Cliente / organización:
- Industria:
- Situación inicial:
- Problema principal:
- Objetivo:
- Solución propuesta:
- Tecnologías utilizadas:
- Resultado principal:
- Métricas reportadas:
- Principal duda que queda abierta:

No agregues información externa.
```

---

## 2. Identificar el problema

```text
Analiza el caso y separa claramente:

1. Síntomas observados.
2. Problema explícitamente declarado.
3. Posibles causas mencionadas en el documento.
4. Consecuencias del problema.
5. Objetivos de negocio relacionados.

Distingue entre hechos expresados por el documento e interpretaciones.

Marca cada elemento como:

- HECHO DOCUMENTADO
- INTERPRETACIÓN RAZONABLE
- INFORMACIÓN FALTANTE
```

---

## 3. Detectar actores y stakeholders

```text
Identifica todos los actores o stakeholders mencionados o claramente involucrados en el caso.

Crea una tabla con:

- Actor
- Rol
- Problema o necesidad
- Interés
- Decisión en la que participa
- Impacto de la solución sobre este actor
- Evidencia disponible
- Información faltante

No inventes actores específicos si el documento no los menciona. Si deduces un tipo de actor, indícalo como inferencia.
```

---

## 4. Extraer decisiones

```text
Identifica las principales decisiones tomadas durante el caso.

Para cada decisión responde:

- ¿Qué se decidió?
- ¿Quién parece haber participado?
- ¿Por qué se tomó?
- ¿Qué alternativas se mencionan?
- ¿Qué evidencia justificó la decisión?
- ¿Qué riesgo implicaba?
- ¿Qué información habría sido útil antes de decidir?
- ¿Qué resultado se atribuye a esa decisión?

Si el documento no explica una de estas dimensiones, escribe: "No informado".
```

---

## 5. Analizar la solución tecnológica

```text
Explica la solución tecnológica descrita en el caso.

Organiza la respuesta en:

1. Componentes de la solución.
2. Tecnologías utilizadas.
3. Procesos modificados.
4. Datos utilizados.
5. Automatizaciones implementadas.
6. Integraciones.
7. Cambios organizacionales necesarios.
8. Beneficio esperado de cada componente.
9. Riesgos técnicos.
10. Dependencias o requisitos.

Diferencia claramente lo que aparece en el documento de lo que sería una inferencia.
```

---

## 6. Extraer resultados y KPI

```text
Extrae todos los resultados cuantitativos y cualitativos informados en el caso.

Crea una tabla con:

- Resultado
- Indicador / KPI
- Valor inicial
- Valor final
- Cambio porcentual
- Periodo de medición
- Fuente o fragmento del documento
- ¿Existe información suficiente para comprobar causalidad? Sí / No / Parcial
- Observación crítica

No calcules valores que no puedan derivarse directamente de los datos disponibles.
```

---

## 7. Detectar vacíos de información

Este prompt acelera especialmente los puntos posteriores del ejercicio.

```text
Actúa como investigador crítico.

A partir exclusivamente de este caso, identifica información relevante que:

- falta;
- no está explicada;
- se presenta sin evidencia;
- no tiene fuente;
- no incluye metodología;
- no permite verificar causalidad;
- no permite comparar antes y después;
- podría representar un sesgo del proveedor.

Crea una tabla con:

1. Vacío detectado
2. Por qué importa
3. Qué decisión podría afectar
4. Evidencia adicional necesaria
5. Fuente externa ideal para comprobarlo

Prioriza los 5 vacíos más importantes.
```

---

## 8. Separar hechos de marketing

Los casos corporativos suelen destacar resultados positivos. Este prompt ayuda a mantener una lectura crítica.

```text
Revisa el lenguaje del caso e identifica afirmaciones que puedan tener carácter promocional o de marketing.

Clasifica las afirmaciones importantes como:

- Dato verificable
- Testimonio
- Afirmación comercial
- Interpretación
- Resultado cuantificado
- Resultado no cuantificado

Para cada una incluye:

- afirmación resumida;
- evidencia disponible;
- qué evidencia faltaría para validarla;
- nivel de confianza: Alto / Medio / Bajo.

No afirmes que una declaración es falsa; determina únicamente qué tan verificable resulta con la información proporcionada.
```

---

# Prompt de control de calidad

Ejecutar después del análisis inicial:

```text
Audita tu análisis anterior.

Busca:

- afirmaciones sin respaldo;
- inferencias presentadas como hechos;
- datos que no aparezcan en el documento;
- contradicciones;
- métricas sin contexto;
- causalidades no demostradas;
- actores asumidos;
- información esencial omitida.

Corrige los errores encontrados.

Devuelve dos secciones:

1. Análisis corregido.
2. Lista de cambios realizados y motivo de cada corrección.
```

---

# Prompt para generar la síntesis que entregará el alumno

```text
Utilizando únicamente la información validada del documento, prepara una síntesis académica y concisa del caso.

Extensión: 500 a 700 palabras.

Estructura:

## 1. Contexto
## 2. Problema
## 3. Actores relevantes
## 4. Solución implementada
## 5. Evidencias disponibles
## 6. Decisiones principales
## 7. Resultados
## 8. Vacíos de información
## 9. Preguntas para la siguiente etapa de investigación

Reglas:

- No inventar datos.
- Separar evidencia de interpretación.
- Señalar explícitamente cuando falta información.
- Incluir métricas concretas cuando existan.
- Evitar lenguaje promocional.
- Mantener tono analítico.
```

---

# Plantilla rápida para copiar resultados

```markdown
# Análisis inicial del caso Cognizant

## Caso seleccionado
**Título:**  
**Cliente:**  
**Industria:**  
**URL / fuente:**  

## 1. Contexto

## 2. Problema principal

## 3. Problemas secundarios

## 4. Actores

| Actor | Rol | Necesidad / interés | Evidencia |
|---|---|---|---|

## 5. Solución

## 6. Tecnologías utilizadas

## 7. Decisiones principales

| Decisión | Justificación | Evidencia | Información faltante |
|---|---|---|---|

## 8. Resultados y métricas

| Resultado / KPI | Valor | Periodo | Evidencia | Observación |
|---|---:|---|---|---|

## 9. Vacíos de información

| Vacío | Por qué importa | Qué investigar |
|---|---|---|

## 10. Preguntas de investigación

1.
2.
3.
4.
5.

## 11. Conclusión inicial
```

---

# Modo ultrarrápido — 5 minutos

Si el tiempo es muy limitado, utilizar solamente estos tres prompts:

### Prompt A — mapa del caso

```text
Resume el documento identificando: contexto, problema, actores, solución, tecnologías, decisiones, métricas, resultados y principales vacíos. Presenta cada afirmación importante con su evidencia.
```

### Prompt B — análisis crítico

```text
¿Cuáles son las cinco afirmaciones más importantes del caso que no pueden aceptarse completamente sin evidencia adicional? Explica qué información falta y cómo podría verificarse.
```

### Prompt C — salida final

```text
Convierte todo el análisis anterior en una ficha académica estructurada con: contexto, problema, actores, evidencias, decisiones, solución, resultados, vacíos y cinco preguntas de investigación. No inventes información.
```

---

# Estrategia para acelerar todavía más

La secuencia recomendada es:

**Documento → Prompt maestro → Vacíos → Control de calidad → Síntesis final**

Esto evita hacer preguntas repetitivas y permite obtener en pocas interacciones una base que luego puede reutilizarse para:

- profundizar fuentes;
- contrastar afirmaciones;
- buscar controversias;
- formular hipótesis;
- preparar la síntesis visual final.

## Regla esencial

> SciSpace debe utilizarse como **herramienta de extracción, organización y análisis**, no como fuente original de evidencia.

Siempre regresar al documento fuente para comprobar los datos importantes antes de incluirlos en la entrega final.
