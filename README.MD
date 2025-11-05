# Análisis del Sistema Inmunitario Humano (SIH)

Este proyecto presenta un **análisis bioinformático avanzado e interactivo** sobre la distribución de células inmunitarias en los distintos tejidos del cuerpo humano.  
Se ha desarrollado en el marco de la asignatura **Bioinformática** y toma como referencia los datos suplementarios del artículo de *Proc. Natl. Acad. Sci. (PNAS)*, empleando herramientas de análisis de datos y visualización en Python.

---

## Objetivo de la investigación

**Pregunta de investigación:**  
> *¿Hasta qué punto el aumento de la masa del tejido adiposo (como modelo simple de obesidad) modifica el reparto cuantitativo de las células inmunitarias en el organismo?*

El objetivo principal es estudiar la **distribución cuantitativa y relativa** de las células inmunitarias en los tejidos corporales, evaluando cómo un incremento del tejido adiposo (20%) podría afectar a la carga inmunitaria total.

---

## Metodología

1. **Fuentes de datos**  
   - Ficheros suplementarios del estudio:  
     - `pnas.2308511120.sd01.xlsx`  
     - `pnas.2308511120.sd02.xlsx`  
   - Información sobre masa tisular, densidad inmunitaria y proporciones celulares.

2. **Procesamiento de datos**
   - Limpieza y normalización de los datos en `pandas`.
   - Cálculo de densidades y masas inmunitarias totales.
   - Simulación del escenario de obesidad con +20% de masa adiposa.

3. **Visualización**
   - Gráficas interactivas con `plotly` (barras, treemap, scatter log-log, sunburst, barras comparativas).
   - Generación automática del informe final en HTML con todas las figuras y explicaciones interpretativas.

---

## Contenido del repositorio

| Archivo | Descripción |
|----------|--------------|
| `Entregable_Bioinformatica_Inmunidad_INTERACTIVO.ipynb` | Notebook principal con el análisis completo e interacciones paso a paso. |
| `Informe_Bioinformatica_Inmunidad.html` | Informe final interactivo con diseño profesional y figuras explicadas. |
| `pnas.2308511120.sd01.xlsx` | Datos de masas tisulares. |
| `pnas.2308511120.sd02.xlsx` | Datos de densidades inmunitarias. |

---

## Resultados principales

- Los **tejidos linfoides** (bazo, ganglios, médula ósea roja) presentan la mayor **densidad celular inmunitaria**, evidenciando su función central en la defensa del organismo.  
- Tejidos **de gran masa** pero baja densidad (como músculo o sangre) también contribuyen de forma significativa al total inmunitario.  
- El **aumento de tejido adiposo** produce una **redistribución proporcional** de células inmunes, sin alterar el patrón global, pero **incrementando la carga inmunitaria corporal total**.  
- No existe una relación logarítmica directa entre masa tisular y densidad inmunitaria: los **órganos pequeños pueden concentrar una fracción importante del sistema inmunitario.**

---

##  Visualización interactiva

El informe final puede abrirse directamente desde el navegador:

[**Informe_Bioinformatica_Inmunidad.html**](Informe_Bioinformatica_Inmunidad.html)

Incluye:
- 5 análisis gráficos con descripciones interpretativas.
- Visualizaciones interactivas basadas en `Plotly.js`.
- Diseño visual con CSS moderno y modo oscuro.

---

## Tecnologías empleadas

- **Python 3.10+**
- `pandas`, `plotly`, `numpy`, `openpyxl`
- `Jupyter Notebook`
- HTML5 + CSS3 para el informe final

---

## 👤 Autor

**Raúl Mendoza**  
**Adrian Ojeda**  
Estudiante de Ciencia e Ingeniería de Datos  
Universidad de La Laguna (ULL)  
*Curso 2024–2025*

---

## Licencia

Este trabajo se distribuye bajo licencia **MIT**, únicamente para fines académicos y de aprendizaje.

---

> *“Comprender el sistema inmunitario es entender el equilibrio dinámico entre defensa, energía y vida.”*
