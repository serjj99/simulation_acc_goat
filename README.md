# 🐐 An application of the Monte Carlo Method and VAR models in animal science  
### Una aplicación del Método Montecarlo y los modelos VAR en ciencia animal  
**Generating synthetic goat movement data**  
**Generación de datos sintéticos del movimiento de cabras**

---

This repository contains the complete code and data associated with the article:

> *An application of the Monte Carlo Method and VAR models in animal science: Generating synthetic goat movement data.*  
> *Una aplicación del Método Montecarlo y los modelos VAR en ciencia animal: Generación de datos sintéticos del movimiento de cabras.*

The goal of this work is to demonstrate how simple mathematical tools — such as the Monte Carlo method and Vector Autoregressive (VAR) models — can be used to generate realistic synthetic data based on triaxial accelerometer readings collected from goats. This approach is useful in contexts where real data is scarce, expensive or difficult to obtain.

---

## 📁 Contents / Contenido

- `simulacion_cabras.ipynb` – Jupyter notebook with all the code, models, simulation steps and visualizations.
- `datos_reales/` – Folder containing the real accelerometer data used in the project.
- `resultados/` – Generated samples and figures comparing real and synthetic data.
- `parametros/` – Fitted parameters for duration distributions and VAR models.

---

## 🧠 Summary / Resumen

In this notebook, we:

- Simulate the sequence of goat activities using a discrete Monte Carlo method.
- Generate activity durations using an exponential distribution fitted to real data.
- Simulate realistic triaxial acceleration signals for each activity using trained VAR models.
- Combine all components into a full synthetic dataset generator.
- Compare real vs. simulated sequences for visual validation.

En este notebook:

- Se simula la secuencia de actividades de las cabras mediante un método de Montecarlo discreto.
- Se genera la duración de cada actividad a partir de una distribución exponencial ajustada a los datos reales.
- Se simulan señales de aceleración triaxial realistas mediante modelos VAR entrenados.
- Se integran todos los elementos en un generador completo de datos sintéticos.
- Se comparan visualmente datos reales y simulados.

---

## 📌 Citation / Cita

If you use this code or dataset, please cite the article or contact the authors:

```bibtex
@article{sanjuan2025montecarlo,
  title     = {An application of the Monte Carlo Method and VAR models in animal science: Generating synthetic goat movement data},
  author    = {Jos\'e M. Calabuig Rodr\'{\i}guez, Llu\'{\i}s M. Garc\'{\i}a Raffi, E. A. S\'anchez P\'erez, Sergi Sanjuan},
  year      = {2025},
  note      = {In preparation}
}
