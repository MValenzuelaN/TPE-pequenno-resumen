# Resumen: Teoría Pura de la Estadística

<a href="https://zenodo.org/records/18077617">
  <img align="left" width="42" src="https://about.zenodo.org/static/img/logos/zenodo-gradient-square.svg" alt="Zenodo" />
</a>

**[Elementos para una teoría pura de la estadística](https://zenodo.org/records/18077617)**
*Zenodo · 2025* — Borrador de un resumen de una eventual teoría sobre los fundamentos de la estadística como disciplina autónoma.

<br/>

Este repositorio contiene un resumen estructurado y en desarrollo de la propuesta de Matías Augusto Valenzuela Nuche para refundar las bases conceptuales y matemáticas de la estadística bajo la **Teoría Pura de la Estadística (TPE)**. Su objetivo es delimitar la estadística como una ciencia formal pura (rama de las matemáticas), distinguiéndola de sus prácticas profesionales e interdisciplinarias de carácter eminentemente tecnológico (como la ingeniería de datos o la "ciencia de datos").

> [!NOTE]
> Este repositorio distribuye la versión compilada en formato PDF del resumen de la Teoría Pura de la Estadística, junto con sus diagramas y assets representativos. Los archivos fuente de LaTeX (`.tex`) son de uso interno para el autor y no se comparten públicamente en este espacio.

---

## Alcance del Resumen

El lector encontrará en este repositorio una síntesis rigurosa y en construcción de los siguientes pilares de la TPE, estructurados en el archivo principal:

1. **Análisis Lingüístico-Pragmático de la Disciplina**:
   - Desenredo conceptual apoyándose en las filosofías del lenguaje de Wittgenstein y Ryle, aplicadas mediante el marco de los "Modos de Conocimiento" de Emilio Ribes Iñesta.
   - Crítica exhaustiva al término multívoco y empíricamente cargado de *dato*, demostrando que la estadística nunca se interesa por un dato aislado, sino por propiedades agregadas de grupos de cosas.

2. **Concepto Matemático de Población Estadística (PE)**:
   - Formalización axiomática de la población estadística como un arreglo $\{x_{ij}\}$ doblemente indexado por un índice dativo $I$ (registro/individuo) y un índice dimensional $J$ (variable), donde cada dimensión está regida por una *Especie de Estructura* bourbakista que define y restringe sus operaciones válidas.

3. **Identidad entre Frecuencia y Probabilidad**:
   - Demostración de la representación canónica que vincula de forma determinista la distribución de frecuencias relativas a una ley de probabilidad uniforme sobre el espacio de índices utilizando espacios topológicos Polacos y $\sigma$-álgebras de Borel.

4. **Distinción Estructural (Estadística vs. Probabilidad)**:
   - Demostración del Teorema de *Irreductibilidad Operacional del Índice*, el cual establece que la probabilidad es una proyección con pérdida de información (funtor Ley $\mathcal{L}$) que destruye el índice dativo $I$, impidiendo recuperar las leyes conjuntas ante operaciones de concatenación lateral.

5. **El Enfoque Descripcionista y Extensiones Inferenciales**:
   - Definición de la estadística descriptiva como el núcleo canónico y deductivo de la disciplina (*descripcionismo*).
   - Estructuración de las tres principales escuelas de inferencia como extensiones probabilísticas formales construidas sobre la PE:
     - **Población Probabilística Clásica (PPC)**: Para la inferencia frecuentista y la constructividad de muestras aleatorias simples (MAS) con reemplazo.
     - **Población Probabilística Bayesiana (PPB)**: Para la inferencia bayesiana mediante kernels de probabilidad Markovianos y teorema de Bayes generalizado.
     - **Población Probabilística Fisheriana (PPF)**: Para la inferencia paramétrica clásica y la justificación formal de la función de verosimilitud vía Radon-Nikodym.

6. **Estadística Descriptiva Extendida (Bases de Datos Relacionales)**:
   - Abstracción de bases de datos relacionales en términos estadísticos puros mediante el concepto de *pseudo-índice dativo minimal* (llave primaria), *referenciador dativo* (llave foránea) y *grafo de poblaciones*.

7. **Matización y Crítica Histórica**:
   - Análisis crítico de las definiciones clásicas e inexactas de estadística presentes en los textos de referencia de la literatura (Bartholomew, Fienberg, Monroy, Sprenger, Wild, entre otros).

---

## Cómo citar este trabajo

Si utilizas este resumen o basas tus investigaciones en la Teoría Pura de la Estadística formulada por el autor, por favor cita el documento original alojado en Zenodo:

### Cita en formato APA 7
> Valenzuela Nuche, M. A. (2025). *Elementos para una teoría pura de la estadística* (Borrador). Zenodo. https://doi.org/10.5281/zenodo.18077617

### Cita en formato BibTeX
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

Adicionalmente, este repositorio incluye un archivo de metadatos [CITATION.cff](CITATION.cff) en su raíz, lo que permite a GitHub habilitar el botón nativo de citación en el panel lateral derecho del repositorio.

---

## Licencia

Este repositorio y su contenido se distribuyen bajo la licencia Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0), la misma del documento original alojado en Zenodo.
