# Guía Final de Formato y Estilo
## "Las Guerras Neurales: Código Fracturado" - Estándares Definitivos de Markdown

*Guía integral de formato incluyendo etiquetas de escena, convenciones de diálogo, separadores de sección, ganchos, énfasis de términos clave, y reglas de diseño con ejemplos anotados y razonamiento.*

---

## **Estructura de Capítulos y Encabezados**

### **Títulos de Capítulos**
**Formato**: `# [Número]: [TÍTULO TEMÁTICO]`

**Ejemplos:**
- `# 1: UMBRAL`
- `# 3: FRACTURA`  
- `# EPÍLOGO`

**Razonamiento**: Títulos temáticos de una palabra crean impacto emocional y cohesión temática. Los números mantienen claridad estructural mientras los temas sugieren jornada psicológica.

### **Separadores de Sección dentro de Capítulos**
**Formato**: `---` (tres rayas largas)

**Uso**: Separa transiciones de escena principales, saltos de tiempo, o cambios de perspectiva dentro del mismo capítulo.

**Ejemplo**:
```markdown
Mileo rastrea una con la punta del dedo, no sintiendo nada sino el frío irradiando a través del vidrio.

---

[Memoria]

*Un niño pequeño se para en puntas de pie, alcanzando un frasco de lápices de colores.*
```

**Razonamiento**: Separación visual limpia mantiene legibilidad mientras permite flujo narrativo suave entre escenas relacionadas.

---

## **Etiquetas de Escena y Marcadores Atmosféricos**

### **Formato de Etiquetas de Escena**
**Formato**: `[Etiqueta][Etiquetas Adicionales]`

**Colocación**: Inmediatamente siguiendo encabezado de capítulo o separador de sección

**Categorías de Etiquetas Centrales:**
- **[Reflexión]**: Exploración interna de personaje, escenas contemplativas
- **[Acción]**: Secuencias kinéticas, confrontación física, urgencia
- **[Calle]**: Configuraciones de resistencia/suburbios, atmósfera subterránea
- **[Memoria]**: Secuencias de flashback, experiencias recuperadas
- **[Cósmico]**: Perspectiva del Arquitecto, conciencia vasta, elementos de otro mundo

**Aplicaciones de Ejemplo:**
```markdown
[Reflexión]
La lluvia traza líneas por la ventana—cada gota demasiado perfecta...

[Acción][Calle]
El hedor golpea a Kora primero—sudor acre, aceite de máquina...

[Cósmico][Percepción]
Dentro del espacio interdimensional donde la realidad física se intersecta...
```

**Razonamiento**: Las etiquetas proporcionan orientación atmosférica inmediata para lectores mientras mantienen organización del manuscrito. Múltiples etiquetas permiten complejidad de escena en capas.

### **Jerarquía de Etiquetas y Combinaciones**
**Etiquetas Primarias** (Atmósfera): [Reflexión], [Acción], [Calle], [Memoria], [Cósmico]
**Etiquetas Secundarias** (Especificidad): [Percepción], [Descubrimiento], [Investigación], [Confrontación]

**Reglas de Combinación:**
- Máximo dos etiquetas por escena
- Etiqueta primaria siempre primera
- Etiquetas separadas sin espacios: `[Acción][Calle]`

---

## **Formato de Diálogo**

### **Atribución de Diálogo Estándar**
**Formato**: Prefijo de raya larga con atribución e integración de acción

**Patrón Estándar:**
```markdown
—Buenos días, Mileo —entona el sistema ambiental del apartamento, su voz modulada a armónicos que sincronizan con su interfaz neural.
```

**Convenciones Clave:**
- **Raya larga** (—) no guión (-) para diálogo
- **Minúscula** después del diálogo a menos que nombre propio
- **Beats de acción** integrados con atribución para ritmo

### **Diálogo Interrumpido**
**Formato**: Raya larga en punto de interrupción

**Ejemplos:**
```markdown
—Gra... —La palabra se ejecuta desde su aparato vocal antes de que pueda inhibir el protocolo de respuesta.

—Cálculos de probabilidad mostrando factores de riesgo aumentados —murmura... —Modelos matemáticos de convergencia de patrulla indican—
—Matemáticas después —lo corta Sierra
```

**Razonamiento**: Muestra secuestro tecnológico del habla, respuestas de estrés, y dinámicas de personaje a través de patrones de interrupción.

### **Diálogo Interno vs. Diálogo Hablado**
**Pensamientos Internos**: *Cursivas* con o sin atribución
**Comunicación Subvocal**: Raya larga estándar con atribución técnica

**Ejemplos:**
```markdown
*Algo está mal con la lluvia.*

—¿Objetivo? —subvocaliza, mandíbula apenas moviéndose, las palabras atrapadas entre sus dientes.
```

### **Diálogo de Sistema/IA**
**Formato**: Raya larga estándar con atribución técnica de sistema

**Ejemplos:**
```markdown
—Tus biométricos indican leve ineficiencia de sueño —le recuerda el sistema ambiental. —¿Te gustaría que ajuste tu protocolo de regulación circadiana?
```

**Razonamiento**: Mantiene consistencia mientras permite que lenguaje técnico sugiera fuente no humana.

---

## **Énfasis y Tipografía**

### **Énfasis de Términos Clave**
**Términos Técnicos**: Formato normal, contexto proporciona énfasis
**Pensamientos de Conciencia**: *Cursivas*
**Designaciones de Sistema**: Formato normal con capitalización
**Énfasis Emocional**: *Cursivas* con moderación

**Ejemplos:**
- Especialista en Cumplimiento Neural (rol técnico)
- *Integridad de interfaz comprometida* (pensamiento auténtico abriéndose paso)
- El Arquitecto (designación de sistema)
- *equivocado* (énfasis emocional)

**Razonamiento**: El uso excesivo de formato disminuye impacto. Contexto y elección de palabras crean énfasis más efectivamente que tipografía.

### **Precisión Científica/Técnica**
**Formato**: Medidas exactas y porcentajes mantienen credibilidad científica

**Ejemplos:**
- "precisamente separadas por siete milímetros"
- "0.0027% de tasa de ocurrencia entre Especialistas"
- "exactamente 157 hojas por rama visible"

**Razonamiento**: La precisión numérica sugiere control sistemático mientras crea inquietud a través de perfección inhumana.

### **Descripción Sensorial y Corporal**
**Enfoque**: Detalles táctiles, olfativos y kinestésicos sobre visuales
**Técnica**: Sensaciones específicas en lugar de descripciones generales

**Ejemplos:**
- "sabor cobrizo de su propia resistencia"
- "vibraciones transmitiendo a través de hueso en frecuencias demasiado primitivas"
- "el agarre del arma se acomoda en su palma con familiaridad cálida"

**Razonamiento**: Detalles sensoriales no visuales crean inmersión corporal y contraste con entorno digital/optimizado.

---

## **Convenciones de Acción y Movimiento**

### **Secuencias de Combate**
**Principios**:
- Brevedad de oración durante acción intensa
- Detalles específicos de equipamiento y técnica
- Consecuencias físicas inmediatas

**Ejemplo:**
```markdown
Su mano baja a su arma de pulso con precisión fluida. El agarre se acomoda en su palma. Sesenta y dos latidos por minuto—ritmo de combate activándose.
```

### **Tecnología de Resistencia**
**Énfasis**: Naturaleza improvisada, mecánica, primitiva vs. tecnología de optimización elegante

**Ejemplos:**
- "botones *reales* que chasquean con precisión satisfactoria"
- "tecnología tan antigua que predatea el estado de vigilancia"
- "maquinaria compleja erizada con sondas delgadas como cabellos"

---

## **Vocabulario de Mundo y Consistencia**

### **Términos de NeuroSys (No Traducir)**
- NeuroSys (nombre corporativo)
- NeuroSec (división de seguridad)
- Neo-Citania (nombre geográfico)

### **Conceptos Técnicos (Traducir con Consistencia)**
- The Link → El Enlace
- The Architect → El Arquitecto
- Neural Compliance Specialist → Especialista en Cumplimiento Neural
- Cascade Sensitivity → Sensibilidad de Cascada
- Pattern Deviation → Desviación de Patrón

### **Convenciones de Tiempo y Medida**
- Mantener sistema métrico
- Precisión temporal específica ("4.3 segundos", "exactamente 1.2 segundos")
- Distancias exactas ("1.2 metros", "0.75 metros de distancia prescrita")

---

## **Mantenimiento de Voz Narrativa en Español**

### **Registro Formal vs. Coloquial**
**Mileo**: Registro elevado, terminología técnica, sintaxis compleja
**Kora**: Lenguaje directo, profanidad ocasional, construcciones naturales
**Sierra**: Comando militar, eficiencia verbal, precisión táctica

### **Fluidez vs. Literalidad**
- Priorizar lectura natural en español
- Mantener impacto emocional sobre traducción literal
- Preservar ritmo y cadencia de oraciones originales

### **Notas Culturales**
- Usar español neutro internacional
- Evitar regionalismos específicos
- Incluir notas explicativas para términos inventados en primer uso

---

*Esta guía asegura consistencia de formato y estilo a través de toda la traducción del proyecto, manteniendo integridad narrativa mientras adapta convenciones al español literario profesional.*