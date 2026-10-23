# Curso IA para Autoridades de Consumo · Cuadernos de Colab

**Plan B de las prácticas del curso.** Si algo falla en tu ordenador, puedes seguir las
prácticas de cada bloque desde el navegador con Google Colab, en el mismo orden que en clase.

| Bloque | Cuaderno |
|---|---|
| 1 · Qué es programar con IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque1/bloque1_practicas.ipynb) |
| 2 · De datos dispersos a estadísticas fiables | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque2/bloque2_practicas.ipynb) |
| 3 · Cómo obtener información de una web con ayuda de la IA | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque3/bloque3_practicas.ipynb) |
| 4 · Elementos de prueba | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/consumer-spain/curso-ia-colab/blob/main/bloque4/bloque4_practicas.ipynb) |
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
| Práctica Geoportal (prompt, script de la IA, ejecutar, corregir) | **Adaptada**: `%%writefile` y `!python`; la API se consulta desde servidores de Google y puede fallar → recuperación con `--respaldo` |
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
| Comprobación inicial (`COMPROBAR_BLOQUE4.bat`) | **Adaptada**: celda de Preparación (avisa de que falta `tkinter`, lo esperable en Colab, y de si la TSA responde) |
| Pregunta, método de seis pasos, puestas en común | **Igual** |
| Books · ejecutar y abrir el Excel (`EJECUTAR_BOOKS.bat`, Excel) | **Adaptada**: celda con el mismo respaldo si la web no responde; el Excel se ve con pandas |
| Mini-reto fila 7 · ¿qué guardaríais? | **Igual** |
| RECOGER · ficha del libro 7 (`RECOGER_LIBRO_7.bat`) | **Adaptada**: celda, con respaldo |
| CONTEXTUALIZAR · Propiedades → Detalles de Windows | **No exportable**: se usa la herramienta del curso |
| CONTEXTUALIZAR · metadatos (`1_VER_METADATOS.bat`) | **Adaptada**: celda; la imagen se ve con `display` |
| CONTEXTUALIZAR · `/exif` | **Igual** (en tu navegador; los archivos se descargan desde una celda) |
| CONTEXTUALIZAR · `/ip` | **Igual, solo en tu navegador**. Una celda de contraste muestra que desde Colab la IP sería la de un centro de datos de Google |
| FIJAR · ver extensiones en el Explorador | **No exportable**: en Colab se ven siempre |
| FIJAR · predice y comprueba, un solo carácter (copiar, F2, Bloc de notas, `2_COMPARAR_HASHES.bat`) | **Adaptada**: celdas que copian y modifican; la predicción la haces tú antes |
| FIJAR · `/hash` | **Igual** (en tu navegador) |
| VINCULAR AL TIEMPO · petición real, cinco preguntas, qué comprobaría un verificador | **Igual** / **Adaptada** (`ver_peticion.py` en una celda) |
| VINCULAR AL TIEMPO · mismo sello, dos archivos (`3_VERIFICAR_SELLO.bat`, `/verificador`) | **Adaptada**: celda; `/verificador` igual en tu navegador |
| DOCUMENTAR · original / copia / derivado, manifiesto, localiza campos (Bloc de notas) | **Adaptada**: `!cat` del manifiesto de muestra |
| VERIFICAR · dos paquetes técnicamente correctos | **Igual** |
| Taller del sellador · núcleo, criterios, prompt, decisiones | **Igual** |
| Taller del sellador · la ventana (`tkinter`) | **Adaptada**: formulario de Colab + celda que hace de botón; `ejecutar_sellado()` con `print`/`input()`. La TSA puede no responder desde Google: hay paquete de contingencia |
| Taller del sellador · `COMPROBAR_PAQUETE.bat` y prueba negativa (Paint) | **Adaptada**: celdas (el punto se pinta con Pillow) |
| CONSUMOKU · descarga del ZIP, manifiesto, imágenes, hojas de cálculo | **Adaptada**: el ZIP se sube a Colab; Excel con pandas, imágenes con `display` |
| CONSUMOKU · verificación de sellos y formulario de fallo | **Igual** (celda o `/verificador`; el formulario, en la web) |
| Resolución y cierre | **Igual** (se hace en común) |

Lo que se obtiene desde Colab sale de servidores de Google, no de un equipo institucional: **no tiene valor probatorio**.

Repositorio temporal: se eliminará al terminar el curso.
