# Curso IA para Autoridades de Consumo · Cuadernos de Colab

**Plan B de las prácticas del curso.** Si algo falla en tu ordenador, puedes seguir las
prácticas de cada bloque desde el navegador con Google Colab, en el mismo orden que en clase.

| Bloque | Cuaderno |
|---|---|
| 1 · Qué es programar con IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque1/bloque1_practicas.ipynb) |
| 2 · De datos dispersos a estadísticas fiables | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque2/bloque2_practicas.ipynb) |
| 3 · Cómo obtener información de una web con ayuda de la IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque3/bloque3_practicas.ipynb) |
| 4 · Elementos de prueba | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque4/bloque4_practicas.ipynb) |
| 5 · Del script al sistema | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque5/bloque5_practicas.ipynb) |

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
                                (en el Bloque 4 se llama BLOQUE4_ALUMNADO.zip, como en clase)
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

Sincronizado con la presentación V18 (materiales V16): cuatro retos (documentación · modelo de 2 CCAA · normalización ·
campaña estatal) y dos bolas extra opcionales (1 · muestra sintética, tras RESTRICCIONES; 2 · auditor independiente, al final). Cada reto tiene `01_ENTRADAS`, una carpeta de trabajo y una carpeta *resuelto*;
el cuaderno cierra cada reto con su sección «Si te bloqueas».

| Práctica | En Colab |
|---|---|
| Instalación de requisitos (`pip install -r requirements.txt`) | **Adaptada**: celda de Preparación (descarga el ZIP, instala lo que falte, termina en «TODO LISTO») |
| Reto 1 · mirar el Excel y la carpeta | **Adaptada**: `ver_excel` y `!find` en lugar de Excel y Explorador |
| Reto 1 · criterios, prompt, 20 min y validación 21 / 3 / 1 / 2 | **Adaptada**: el código de la IA se pega en una celda `%%writefile` y se ejecuta con `!python` |
| Reto 1 · ampliación con interfaz (`tkinter`) | **No exportable**: no se abren ventanas en Colab; alternativa por línea de comandos |
| Encargo estatal · 8 piezas, mensajes 1–5 a la IA, reglas (8/10 frente a 10/40) | **Igual** |
| ★ Bola extra 1 · muestra sintética (prompt, script, comprobar tu muestra, resolución con la de referencia) | **Adaptada**: `%%writefile`, `!python` y `ver_excel` |
| Reto 2 · el modelo manual y sus 4 gráficas | **Adaptada**: `ver_excel`; las gráficas se listan y se descargan para verlas |
| Reto 2 · combinar 2 CCAA, comparar con el resultado conocido, cambio controlado, núcleo del modelo | **Adaptada**: las tablas se ven con `ver_excel`; la comparación la hace el alumno; el cambio controlado pide `--madrid` y `--salida` |
| Adjuntar archivos a la IA (mensajes 4 y 5) | **Adaptada**: se descargan desde Colab y se suben al chat de la IA |
| Reto 3 · archivos y variaciones (Aragón, Asturias, Galicia, Murcia, Comunitat Valenciana) | **Adaptada**: Madrid y el pendiente, uno bajo otro, con números de fila y letras de columna |
| Reto 3 · normalizador y resultado del comprobador de referencia (5 OK) | **Adaptada** / **Igual**; ampliación: el comprobador de referencia sobre tus normalizados |
| Reto 4 · trabajo autónomo (20 min) y «Ya tenemos un informe estatal» | **Adaptada**: `%%writefile` y `!python`; sin libro propio se ve la forma de un libro completo de ejemplo |
| Reto 4 · ¿está todo?, `CONTROL_CARGA`, diagnóstico de tipos (12 frente a '12'), corrección limitada | **Adaptada**: la versión limitada (`01_CONSOLIDAR_BASE.py`) la genera el alumno con una celda (en clase la tiene preparada el docente); sin libro propio se revisa esa versión |
| Reto 4 · cierre (Excel final, resumen por bloques, 4 gráficas, entregables) | **Adaptada**: la solución de referencia la ejecuta el alumno; gráficas por descarga |
| Cinco preguntas antes de confiar y mapa 8/8 (cierre) | **Igual** |
| ★ Bola extra 2 · auditor independiente, prueba negativa (informe A), controles integrados, cambio controlado con Aragón | **Adaptada**: `%%writefile` y `!python`; el informe A viene en el material |

Este bloque no usa páginas web ni capturas con valor probatorio.

## Bloque 3 · qué cambia en Colab

En este bloque hay dos sitios de trabajo: **tu navegador** (webs, F12, Inspector, Network: igual que en clase) y
**el cuaderno** (lo que en clase hace Python en tu equipo). El ZIP contiene la carpeta `01_ALUMNADO` del material de clase.

| Práctica | En Colab |
|---|---|
| Antes de empezar (descomprimir, comprobar `LAB_WEB`, `INSTALAR_DEPENDENCIAS.bat`) | **Adaptada**: celda de Preparación (ejecuta `verificar_entorno_bloque3.py`) |
| Definir · concretar el encargo (casos A, B, C) | **Igual** |
| Dar contexto · primer mensaje a la IA (`01_PROMPT_PRIMER_CONTEXTO`) | **Igual** |
| Geoportal · buscar y descargar el fichero de precios | **Igual** (en tu navegador) |
| Geoportal · abrir el fichero en Excel y comprobarlo | **Adaptada**: se sube a Colab y se mira con `ver_excel` |
| Abre la API en tu navegador y cambia la fecha | **Igual** (en tu navegador) |
| Práctica Geoportal (prompt, script de la IA, ejecutar, corregir) | **Adaptada**: `%%writefile` y `!python`. Desde Colab la API oficial corta la conexión (comprobado): `usar_replica()` sirve, con la misma ruta, sus respuestas reales guardadas (provincia 28, 12–14/10/2026) y se pide a la IA que cambie solo la dirección base; recuperación con `--respaldo` |
| Comprobar · ¿lo daríais por bueno?, comprobaciones, falta una fecha | **Adaptada**: una celda prepara el resultado a revisar; se mira con `ver_excel` |
| Laboratorio · arrancar (`INICIAR_LAB.bat`, `localhost:8765`) | **Adaptada**: una celda sirve la tienda desde Colab y da un enlace (no es `localhost`) |
| Laboratorio · captura, Ctrl + S, DevTools, cambiar el precio, Inspector, Network | **Igual** (en tu navegador, sobre la tienda servida por Colab) |
| Caso Mercadona · misión en tienda.mercadona.es | **Igual** (en tu navegador) |
| Caso Mercadona · plan B `MERCADONA_CONGELADO` | **Adaptada**: la página guardada se abre con el enlace del laboratorio; capturas, fragmento y respuesta se ven en celdas |
| Caso Mercadona · ¿ahora sí funciona? | **Adaptada**: se compara la tarjeta con la respuesta guardada |
| Demostración · vivienda (navegador automatizado) | **No exportable**: es una demostración del docente; se sigue la explicación |
| Mapa de vías · mini-práctica de los seis casos | **Igual** |
| Bola extra BOE | **Adaptada**: `%%writefile` y `!python`; respaldo real si la API no responde desde Colab |

Lo que se obtiene desde Colab sale de servidores de Google, no de un equipo institucional: **no tiene valor probatorio**.

## Bloque 4 · qué cambia en Colab

Hay dos sitios de trabajo: **tu navegador** (las herramientas web del curso: `/exif`, `/hash`, `/ip`, `/verificador`: igual que en clase)
y **el cuaderno** (lo que en clase hace Python en tu equipo). Los archivos para la web se descargan desde el cuaderno con una celda.

| Práctica | En Colab |
|---|---|
| Comprobación inicial (`COMPROBAR_BLOQUE4.bat`) | **Adaptada**: celda de Preparación (comprueba paquetes, material y si la TSA responde) |
| Pregunta, puesta en común y ruta de seis pasos | **Igual** |
| Books · ejecutar y abrir el Excel (`EJECUTAR_BOOKS.bat`, Excel) | **Adaptada**: celda con el mismo respaldo si la web no responde; el Excel se ve con pandas |
| Mini-reto fila 7 · ¿qué guardaríais? | **Igual** |
| RECOGER · ficha del libro 7 (`RECOGER_LIBRO_7.bat`) | **Adaptada**: celda, con respaldo |
| CONTEXTUALIZAR · Propiedades → Detalles de Windows | **No exportable**: se usa la herramienta del curso |
| CONTEXTUALIZAR · metadatos (`1_VER_METADATOS.bat`) | **Adaptada**: celda; la imagen se ve con `display` |
| CONTEXTUALIZAR · `/exif`, `/ip` | **Igual, en tu navegador** (los archivos se descargan desde una celda). Desde Colab la IP sería la de un centro de datos de Google |
| FIJAR · predice y comprueba, un solo carácter (`2_COMPARAR_HASHES.bat`) | **Adaptada**: celdas que copian y modifican; la predicción la haces tú antes |
| FIJAR · `/hash` | **Igual** (en tu navegador) |
| VINCULAR AL TIEMPO · petición real (`ver_peticion.py`), SÍ/NO | **Adaptada** / **Igual** |
| VINCULAR AL TIEMPO · verifica el sello del paquete Orion B (`3_VERIFICAR_SELLO.bat`, `/verificador`) | **Adaptada**: celda; `/verificador` igual en tu navegador |
| DOCUMENTAR · original / copia / derivado, abrir el manifiesto del paquete B | **Adaptada**: celdas (`comparar_hashes`, `!cat` del manifiesto) |
| VERIFICAR · dos paquetes A/B, `COMPROBAR_PAQUETE`, prueba negativa | **Adaptada**: celdas; la modificación se hace sobre una copia (`neg_B`) |
| CONSUMOKU · manifiesto, imágenes, hojas de cálculo | **Adaptada**: el material ya viene dentro del ZIP de la preparación (`BLOQUE4/04_CONSUMOKU`); no hay que subir nada. Excel con pandas, imágenes con `display` |
| CONSUMOKU · verificación de sellos y formulario de fallo | **Igual** (celda o `/verificador`; el formulario, en la web) |
| BOLA EXTRA (opcional) · `SELLADOR_BASE.py`, prompt, comprobación | **Adaptada**: terminal y prompt; la ventana de la versión mejorada solo en tu ordenador. La TSA puede no responder desde Google |
| Resolución y cierre | **Igual** (se hace en común) |

Lo que se obtiene desde Colab sale de servidores de Google, no de un equipo institucional: **no tiene valor probatorio**.

## Bloque 5 · qué cambia en Colab

Las prácticas con IA (prompts), Healthchecks.io, Telegram y las APIs de IA se hacen **en tu navegador o en tu móvil**, como en clase. El cuaderno cubre lo que en clase hace Python o Windows en tu equipo.

| Práctica | En Colab |
|---|---|
| Comprobación y preparación del entorno (`COMPROBAR_BLOQUE5.bat`, `PREPARAR_ENTORNO_BLOQUE5.bat`) | **Adaptada**: celda de Preparación (instala Playwright y Chromium; tarda cerca de un minuto la primera vez; se puede repetir) |
| ¿Cabe en un Excel? (91 días sí, 92 no) | **Igual** (formulario con números) |
| Base relacional de ejemplo (DB Browser for SQLite) | **Adaptada**: `sqlite3` y pandas, solo lectura (`ver_tabla`, `consulta`) |
| Prompts para diseñar la base y pedir la consulta; revisar el resultado (+0,20 € café, +0,02 € leche) | **Igual** (la consulta de la IA se pega en una celda `%%writefile`) |
| Programador de tareas (`CURSO_IA_DEMO`, `notepad.exe`) y lanzador `.bat` | **No exportable**: Colab no es Windows. Una celda programa una tarea equivalente dentro de la sesión (la idea es la misma, la herramienta no) |
| Log, Healthchecks.io, alertas por Telegram, análisis con IA | **Igual** (en tu navegador o móvil; no se ejecutan desde el cuaderno) |
| Reto final Mercadona | **Adaptada**: `%%writefile` + `!python` con Playwright en modo sin ventana. Mercadona responde desde Google; empieza por 2–3 categorías |
| Contraste manual y checklist | **Igual** (con la web actual en tu navegador) |

Lo que se obtiene desde Colab sale de servidores de Google, no de un equipo institucional: **no tiene valor probatorio**.

Repositorio temporal: se eliminará al terminar el curso.
