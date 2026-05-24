# Resumen: Teoría Pura de la Estadística

[![Zenodo](https://about.zenodo.org/static/img/logos/zenodo-gradient-square.svg)](https://zenodo.org/records/18077617)
[![Licencia: CC BY-NC-ND 4.0](https://img.shields.io/badge/Licencia-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Estado: Borrador activo](https://img.shields.io/badge/Estado-Borrador%20activo-yellow.svg)]()
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18077617-blue.svg)](https://doi.org/10.5281/zenodo.18077617)

> **[Elementos para una teoría pura de la estadística](https://zenodo.org/records/18077617)** · *Zenodo · 2025* — Borrador de un resumen de una eventual teoría sobre los fundamentos de la estadística como disciplina autónoma.

Este repositorio contiene un resumen estructurado y en desarrollo de la propuesta de **Matías Augusto Valenzuela Nuche** para refundar las bases conceptuales y matemáticas de la estadística bajo la **Teoría Pura de la Estadística (TPE)**. Su objetivo es delimitar la estadística como una **ciencia formal pura** (rama de las matemáticas), distinguiéndola de sus prácticas profesionales e interdisciplinarias de carácter eminentemente tecnológico (como la ingeniería de datos o la «ciencia de datos»).

> [!NOTE]
> Este repositorio distribuye la versión compilada en formato PDF y HTML del resumen de la TPE, junto con sus diagramas y assets representativos. Los archivos fuente de LaTeX (`.tex`) son de uso interno del autor y no se comparten públicamente en este espacio.

---

## Tabla de contenidos

- [¿A quién va dirigido?](#a-quién-va-dirigido)
- [Acceso al documento](#acceso-al-documento)
- [Archivos del repositorio](#archivos-del-repositorio)
- [Alcance del resumen](#alcance-del-resumen)
- [Diagramas incluidos](#diagramas-incluidos)
- [Estado del proyecto](#estado-del-proyecto)
- [Cómo citar este trabajo](#cómo-citar-este-trabajo)

---

## ¿A quién va dirigido?

Este resumen está orientado a lectores con formación en matemáticas, estadística o filosofía de la ciencia que deseen comprender la arquitectura conceptual de la TPE antes de abordar el documento completo alojado en Zenodo. No es un tutorial de estadística aplicada; es un mapa teórico de sus fundamentos.

---

## Acceso al documento

El resumen está disponible en dos formatos dentro de este repositorio:

| Formato | Archivo | Descripción |
|---|---|---|
| PDF | [`Resumen.pdf`](./Resumen.pdf) | Versión tipográfica principal, compilada desde LaTeX. Recomendada para lectura y citación. |
| HTML | [`TPE.html`](./TPE.html) | Versión web del documento. Permite lectura en el navegador sin necesidad de software adicional. |

El documento original completo (fuente primaria) se encuentra en Zenodo:

**→ [https://doi.org/10.5281/zenodo.18077617](https://doi.org/10.5281/zenodo.18077617)**

---

## Archivos del repositorio

```
TPE-pequenno-resumen/
├── Resumen.pdf                          # Documento principal (PDF compilado desde LaTeX)
├── TPE.html                             # Versión HTML del resumen
│
├── Población regular.png                # Diagrama: representación de una población estadística regular
├── TPE_ejemplo_1.png                    # Diagrama: ejemplo ilustrativo de la TPE
├── población_probabilística_clásica.png # Diagrama: estructura de la Población Probabilística Clásica (PPC)
├── teorema_2.png                        # Diagrama: representación del Teorema 2 (Irreductibilidad Operacional del Índice)
│
├── CITATION.cff                         # Metadatos de citación en formato CFF (habilita el botón «Cite this repository» de GitHub)
├── LICENSE                              # Licencia CC BY-NC-ND 4.0
└── .gitignore
```

> [!TIP]
> Si solo quieres leer el resumen sin descargar nada, abre [`TPE.html`](./TPE.html) directamente en tu navegador haciendo clic en el archivo desde GitHub y luego en «Raw», o clonando el repositorio.

---

## Alcance del resumen

El lector encontrará en este repositorio una síntesis rigurosa y en construcción de los siguientes pilares de la TPE:

### 1. Análisis lingüístico-pragmático de la disciplina

Desenredo conceptual apoyándose en las filosofías del lenguaje de Wittgenstein y Ryle, aplicadas mediante el marco de los «Modos de Conocimiento» de Emilio Ribes Iñesta. Incluye una crítica exhaustiva al término multívoco y empíricamente cargado de *dato*, demostrando que la estadística nunca se interesa por un dato aislado, sino por propiedades agregadas de grupos de cosas.

### 2. Concepto matemático de población estadística (PE)

Formalización axiomática de la población estadística como un arreglo $\{x_{ij}\}$ doblemente indexado por un índice dativo $I$ (registro/individuo) y un índice dimensional $J$ (variable), donde cada dimensión está regida por una *Especie de Estructura* bourbakista que define y restringe sus operaciones válidas.

### 3. Identidad entre frecuencia y probabilidad

Demostración de la representación canónica que vincula de forma determinista la distribución de frecuencias relativas a una ley de probabilidad uniforme sobre el espacio de índices, utilizando espacios topológicos polacos y σ-álgebras de Borel.

### 4. Distinción estructural: estadística vs. probabilidad

Demostración del **Teorema de Irreductibilidad Operacional del Índice**, el cual establece que la probabilidad es una proyección con pérdida de información (funtor Ley $\mathcal{L}$) que destruye el índice dativo $I$, impidiendo recuperar las leyes conjuntas ante operaciones de concatenación lateral.

### 5. El enfoque descripcionista y extensiones inferenciales

Definición de la estadística descriptiva como el núcleo canónico y deductivo de la disciplina (*descripcionismo*). Estructuración de las tres principales escuelas de inferencia como extensiones probabilísticas formales construidas sobre la PE:

| Población | Sigla | Escuela de inferencia | Construcción formal |
|---|---|---|---|
| Probabilística Clásica | PPC | Frecuentista | Muestras aleatorias simples (MAS) con reemplazo |
| Probabilística Bayesiana | PPB | Bayesiana | Kernels de probabilidad markovianos + Teorema de Bayes generalizado |
| Probabilística Fisheriana | PPF | Paramétrica clásica | Función de verosimilitud vía Radon-Nikodym |

### 6. Estadística descriptiva extendida: bases de datos relacionales

Abstracción de bases de datos relacionales en términos estadísticos puros mediante los conceptos de *pseudo-índice dativo minimal* (llave primaria), *referenciador dativo* (llave foránea) y *grafo de poblaciones*.

### 7. Matización y crítica histórica

Análisis crítico de las definiciones clásicas e inexactas de estadística presentes en los textos de referencia de la literatura (Bartholomew, Fienberg, Monroy, Sprenger, Wild, entre otros).

---

## Diagramas incluidos

Los siguientes archivos de imagen forman parte del cuerpo del resumen y están incluidos como assets independientes para facilitar su referencia o reutilización (respetando la licencia):

| Archivo | Contenido |
|---|---|
| `Población regular.png` | Representación estructural de una población estadística regular con sus índices $I$ y $J$ |
| `TPE_ejemplo_1.png` | Ejemplo concreto que ilustra la aplicación de los conceptos formales de la TPE |
| `población_probabilística_clásica.png` | Diagrama de la Población Probabilística Clásica (PPC) y su relación con la inferencia frecuentista |
| `teorema_2.png` | Visualización del Teorema 2 (Irreductibilidad Operacional del Índice): la proyección $\mathcal{L}$ y la pérdida de estructura del índice dativo |

---

## Estado del proyecto

> [!WARNING]
> Este resumen es un **borrador activo**. Los contenidos están sujetos a revisión y ampliación. Las definiciones y teoremas presentados reflejan el estado actual del desarrollo de la TPE y pueden ser refinados en versiones futuras.

El documento en Zenodo corresponde a la versión `1.0.0-draft`, publicada en octubre de 2025. Las actualizaciones de este repositorio pueden anticipar revisiones que aún no han sido versionadas en Zenodo.

---

## Cómo citar este trabajo

Si utilizas este resumen o basas tus investigaciones en la Teoría Pura de la Estadística formulada por el autor, cita el documento original alojado en Zenodo:

### Formato APA 7

> Valenzuela Nuche, M. A. (2025). *Elementos para una teoría pura de la estadística* (Borrador). Zenodo. https://doi.org/10.5281/zenodo.18077617

### Formato BibTeX

```bibtex
@misc{valenzuela2025elementos,
  author       = {Valenzuela Nuche, Mat{\'\i}as Augusto},
  title        = {Elementos para una teor{\'\i}a pura de la estad{\'\i}stica},
  month        = {oct},
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18077617},
  url          = {https://doi.org/10.5281/zenodo.18077617}
}
```

Este repositorio también incluye un archivo [`CITATION.cff`](./CITATION.cff) en su raíz, lo que permite a GitHub habilitar el botón nativo **«Cite this repository»** en el panel lateral derecho del repositorio.

---

*Distribución bajo licencia [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). Se permite la redistribución no comercial con atribución, sin modificaciones.*
