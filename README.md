# Curso IA para Autoridades de Consumo · Cuadernos de Colab

**Plan B de las prácticas del curso.** Si algo falla en tu ordenador, puedes seguir las
prácticas de cada bloque desde el navegador con Google Colab, en el mismo orden que en clase.

| Bloque | Cuaderno |
|---|---|
| 1 · Qué es programar con IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque1/bloque1_practicas.ipynb) |
| 2 · De datos dispersos a estadísticas fiables | próximamente |
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

Repositorio temporal: se eliminará al terminar el curso.
