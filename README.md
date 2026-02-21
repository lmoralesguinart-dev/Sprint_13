# Luz y Caos: Análisis y Clasificación Automatizada de Obras de Arte

Análisis computacional de pintura clásica mediante técnicas de Machine Learning y reducción de dimensionalidad.

---

## 📌 Descripción del proyecto

Este repositorio contiene un proyecto de análisis visual aplicado a obras pictóricas pertenecientes a los principales movimientos de la Historia del Arte (Renacimiento, Barroco, Romanticismo y Realismo, Impresionismo, Post-impresionismo y Vanguardias).

El objetivo principal es explorar hasta qué punto una obra de arte puede ser traducida a descriptores numéricos capaces de capturar patrones estilísticos y permitir su clasificación automatizada.

El estudio se centra en:

- 🎨 **Análisis cromático**: luminosidad, intensidad y distribución del color.
- 🧩 **Análisis estructural**: textura, entropía, homogeneidad y complejidad visual.
- 🧠 **Clasificación supervisada**: predicción del movimiento artístico a partir de variables técnicas.
- 📊 **Clustering no supervisado**: detección de agrupaciones naturales entre estilos.

---

## ⚙️ Metodología

- Recopilación de un dataset compuesto por obras al óleo de 50 pintores influyentes.
- Extracción de **9 variables estadísticas** a partir de cada imagen mediante procesamiento computacional.
- Construcción de un DataFrame estructurado para análisis exploratorio.
- Reducción de dimensionalidad con **PCA** para interpretar la evolución histórica en un plano “Complejidad vs. Luz”.
- Clustering con **K-Means** para identificar agrupaciones naturales entre estilos.
- Clasificación supervisada mediante **Random Forest**.
- Aplicación de **SMOTE** para equilibrar clases.
- Validación externa con 24 obras de autores no presentes en el dataset.

---

## 🛠 Herramientas utilizadas

- Python
- OpenCV
- Scikit-image
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Resultados

- El modelo Random Forest alcanzó una **precisión del 51,25%**, mejorando aproximadamente un 40% el baseline de la clase mayoritaria.
- El análisis PCA permitió mapear los movimientos artísticos en un espacio interpretable como **“Luminosidad vs. Complejidad”**.
- Movimientos como el Impresionismo mostraron una firma estructural distintiva.
- La validación con autores no vistos confirmó la capacidad de generalización del modelo.
- Los resultados sugieren que los estilos artísticos poseen una **huella matemática medible**, incluso cuando se describen mediante solo nueve variables agregadas.

---

## 🎯 Conclusiones

Este proyecto demuestra que el arte, aunque profundamente subjetivo, contiene regularidades formales cuantificables.

La reducción de obras pictóricas a descriptores matemáticos no sustituye la interpretación histórica, pero abre una nueva vía de análisis complementaria. La evolución artística puede observarse, al menos parcialmente, como un desplazamiento progresivo hacia mayores niveles de luminosidad y diversidad estructural.

Más que reducir el arte a números, este enfoque revela que incluso la intuición deja rastro estadístico.

---

## 📚 Referencias

Rubayo, S. (2021). *Te gusta el arte aunque no lo sepas*. Paidós.
