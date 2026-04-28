# Plantilla de Propuesta de Tarea (GitHub Classroom)

## 1) Título
**Diseño de Mini Proyecto Temático con Enfoque en Documentación**

> Ejemplos de títulos para la práctica temática (elige uno o propón uno similar):
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción General
En esta actividad, diseñarás la **propuesta formal de un proyecto pequeño** orientado a resolver una necesidad concreta en terminal o entorno local.

Tu propuesta debe definir con claridad:
- qué problema quieres resolver,
- para quién está pensado,
- cómo se usaría,
- y cómo organizarías el repositorio para desarrollarlo.

### Lenguaje principal (elige uno)
- **ARM64 Assembly**
- **C**
- **Python**
- **Bash**

> **Nota importante:** Si eliges **ARM64 Assembly**, limita tu alcance a programas **muy pequeños** (por ejemplo: operaciones simples, lectura básica de argumentos, salida en terminal y validaciones mínimas).

### Enfoque de la actividad
La prioridad es la **documentación, planeación y justificación técnica** de la idea antes de escribir mucho código.

- Esta práctica está diseñada para ser **pequeña y viable** con herramientas gratuitas (incluyendo IA con límites de uso).
- **Evita**: frameworks grandes, APIs pagadas, bases de datos, nube, contenedores y dependencias complejas.

---

## 3) Entregables del Estudiante
Tu repositorio debe incluir como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

### Contenido esperado por archivo

#### `README.md`
Debe incluir:
- Título del proyecto.
- Resumen breve (5–8 líneas).
- Lenguaje principal elegido y justificación.
- Alcance (qué sí incluye y qué no incluye).
- Instrucciones mínimas para ejecutar (si ya existe prototipo).
- Estructura del repositorio (resumen).

#### `docs/propuesta.md`
Debe incluir:
- Nombre de la práctica.
- Problema u oportunidad detectada.
- Objetivo general y 2–4 objetivos específicos.
- Alcance funcional (MVP pequeño).
- Fuera de alcance.
- Requisitos técnicos mínimos (sin dependencias complejas).
- Riesgos y mitigaciones.

#### `docs/caso_de_uso.md`
Debe incluir:
- Usuario objetivo.
- Escenario de uso principal.
- Entrada esperada.
- Proceso general.
- Salida esperada.
- Ejemplo de ejecución (texto o pseudoflujo).

#### `docs/estructura_repositorio.md`
Debe incluir:
- Árbol del proyecto.
- Rol de cada carpeta/archivo.
- Convenciones de nombres (archivos, scripts, pruebas).
- Estrategia de crecimiento controlado (cómo crecer sin volverse proyecto grande).

#### `docs/plan_de_pruebas.md`
Debe incluir:
- Objetivo de pruebas.
- Casos de prueba mínimos (al menos 5).
- Entradas válidas e inválidas.
- Resultado esperado por caso.
- Criterios de aceptación.

---

## 4) Estructura Recomendada del Repositorio
Usa como base la siguiente estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> Puedes ajustar `main.<ext>` según tu lenguaje (`.s`, `.c`, `.py`, `.sh`).

---

## Instrucciones para el Estudiante
1. Elige una temática concreta y **acotada** (ejemplo: organización de apuntes, apoyo de estudio, utilidades de terminal, mini juego educativo).
2. Elige tu lenguaje principal.
3. Completa primero los documentos de `docs/`.
4. Si te alcanza el tiempo, agrega un prototipo mínimo en `src/` y script de ejecución en `scripts/`.
5. Mantén todo simple, claro y justificable técnicamente.

---

## Restricciones
- Proyecto **pequeño** (MVP realista en tiempo corto).
- Sin servicios externos de pago.
- Sin nube, sin contenedores, sin bases de datos.
- Sin dependencias pesadas.
- Enfócate en **calidad de documentación y claridad de diseño**.

---

## Criterios de Evaluación (100%)

- **Calidad de la propuesta (`docs/propuesta.md`) – 30%**
  - Problema bien definido, objetivos claros y alcance acotado.
- **Caso de uso (`docs/caso_de_uso.md`) – 20%**
  - Escenario realista, flujo comprensible y salidas coherentes.
- **Estructura del repositorio (`docs/estructura_repositorio.md`) – 20%**
  - Organización clara, consistente y mantenible.
- **Plan de pruebas (`docs/plan_de_pruebas.md`) – 20%**
  - Casos suficientes, criterios de aceptación y cobertura básica.
- **Presentación general (`README.md`) – 10%**
  - Claridad, ortografía y consistencia técnica.

---

## Sugerencias de Alcance por Lenguaje

- **ARM64 Assembly**: máximo 1 funcionalidad principal + validaciones básicas + salida por terminal.
- **C**: programa CLI sencillo con funciones separadas y pruebas manuales.
- **Python**: script modular pequeño (sin frameworks).
- **Bash**: automatización de tareas de archivos/sistema con validaciones de argumentos.

---

## Entrega en GitHub Classroom
- Sube tu propuesta completa al repositorio asignado.
- Verifica que la estructura de carpetas coincida con lo solicitado.
- Asegúrate de que los archivos Markdown sean legibles y estén completos.

**Resultado esperado:** una propuesta sólida, pequeña, bien documentada y lista para iniciar implementación incremental.
