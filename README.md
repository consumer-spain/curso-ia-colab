# Curso IA para Autoridades de Consumo · Cuadernos de Colab

**Plan B de las prácticas del curso.** Si algo falla en tu ordenador, puedes seguir las
prácticas de cada bloque desde el navegador con Google Colab, en el mismo orden que en clase.

| Bloque | Cuaderno |
|---|---|
| 1 · Qué es programar con IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque1/bloque1_practicas.ipynb) |
| 2 · De datos dispersos a estadísticas fiables | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque2/bloque2_practicas.ipynb) |
| 3 · Cómo obtener información de una web con ayuda de la IA | próximamente |
| 4 · Evidencia digital | próximamente |
| 5 · Del script al sistema | próximamente |

## Cómo se usa
1. Abre el enlace del bloque.
2. Ejecuta primero la celda **Preparación**: descarga los materiales y comprueba que todo está listo.
3. Sigue las celdas en orden.
4. Colab no guarda los cambios. Para conservarlos: *Archivo → Guardar una copia en Drive*.

No subas a Colab datos reales ni información interna: todo el material del curso es de prueba.

## Estructura
```
bloqueN/
├── bloqueN_practicas.ipynb     cuaderno del bloque
└── BLOQUEN_MATERIALES.zip      el mismo ZIP de materiales que se usa en clase
```

## Bloque 1 · qué cambia en Colab

| Práctica | En Colab |
|---|---|
| Comprobación inicial (`COMPROBAR_BLOQUE1.bat`) | **Adaptada**: celda de Preparación |
| Misión 1 · Tres formas de ejecutar (`.bat`, VS Code, terminal) | **Adaptada**: se ejecuta una celda (`!python …`) |
| Misión 1 · Resultado y comprobación del TXT | **Igual** |
| Misión 1 · Terminal de Windows (`cmd`, TAB) | **No exportable**: se explica el equivalente `!` de Colab |
| Misión 2 · Crear `mi_contador.py` | **Adaptada**: el código de la IA se pega en una celda `%%writefile` |
| Misión 3 · KeyError, diagnóstico, cambio mínimo y reejecución | **Igual** (el Excel se mira con pandas o se descarga; el script se edita en el editor de Colab) |
| Misión 4 · Concretar y comparador | **Igual** (los datos se piden en un cuadro de texto) |
| Misión 5 · Versión 1 de los seis retos | **Igual** (el código se pega en una celda) |
| Misión 5 · Mejoras con ventanas, botones o «Copiar» | **No exportable**: tkinter no abre ventanas en Colab; elegir una mejora sin ventanas |

## Bloque 2 · qué cambia en Colab

| Práctica | En Colab |
|---|---|
| Instalación de requisitos (`pip install -r requirements.txt`) | **Adaptada**: celda de Preparación (descarga el ZIP, instala lo que falte, termina en «TODO LISTO») |
| Reconciliar dos fuentes · mirar el Excel y la carpeta | **Adaptada**: `ver_excel` y `!find` en lugar de Excel y Explorador |
| Reto de documentación (criterios, prompt, 20 min) y validación 21 / 3 / 1 / 2 | **Adaptada**: el código de la IA se pega en una celda `%%writefile` y se ejecuta con `!python` |
| Reto de documentación · ampliación con interfaz (`tkinter`) | **No exportable**: no se abren ventanas en Colab; alternativa por línea de comandos |
| Actividades de pensar, 8 piezas y mensajes 1–5 a la IA, reglas (8/10 frente a 10/40) | **Igual** |
| Muestra sintética (prompt, script, abrir, antes/después, lista de comprobación) | **Adaptada**: `%%writefile`, `!python` y `ver_excel` |
| Controles · combinar 2 CCAA y comparar con el resultado conocido | **Adaptada**: las dos tablas se ven con `ver_excel`; la comparación la hace el alumno |
| Controles · cambio controlado | **Adaptada**: se pide a la IA `--madrid` y `--salida`; el comando va en una celda |
| Resultado · abrir el modelo funcional y sus 4 gráficas | **Adaptada**: `ver_excel`; las gráficas se listan y se descargan para verlas |
| Adjuntar archivos a la IA (mensajes 4 y 5) | **Adaptada**: se descargan desde Colab y se suben al chat de la IA |
| Archivos y variaciones (Aragón, Asturias, Galicia, Murcia, Comunitat Valenciana) | **Adaptada**: Madrid y el pendiente, uno bajo otro, con números de fila y letras de columna |
| Normalizador y comprobador independiente | **Adaptada**: `%%writefile` y `!python` |
| Primer hito (`01_CONSOLIDAR_BASE.py`) | **Adaptada**: lo ejecuta el alumno (en clase, el docente) |
| Reto de la campaña estatal (20 min) | **Adaptada**: `%%writefile` y `!python`; gráficas por descarga |
| Auditoría · `CONTROL_CARGA`, diagnóstico de tipos (12 frente a '12'), corrección limitada | **Adaptada**: `ver_excel`, `%%writefile` y `!python` |
| Cinco capas, micro-auditoría A/B | **Igual** |
| Auditor independiente y su resultado de referencia | **Adaptada**: la referencia la ejecuta el alumno |
| Caso incorrecto del auditor (informe A) | **Adaptada**: una celda construye el informe A (en clase lo prepara el docente) |
| Ampliaciones opcionales (controles integrados, cambio controlado con Aragón) | **Adaptada** |

Este bloque no usa páginas web ni capturas con valor probatorio.

Repositorio temporal: se eliminará al terminar el curso.
