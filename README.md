# ML-K_Means-GMM 🤖📊
Implementación y análisis de **clustering no supervisado** usando **K-Means** y **Gaussian Mixture Models (GMM)**, con evaluación de métricas y visualización de clusters (PCA 2D).  
Incluye experimentos con datasets como **FIFA 25 Players** y **EastWest Airlines**.

---

## 🚀 Objetivos del proyecto
- Aplicar **K-Means** y **GMM** para segmentación de datos.
- Comparar configuraciones de **K** (número de clusters) usando métricas:
  - *Inercia* (método del codo)
  - *Silhouette Score*
  - *Davies-Bouldin Index*
  - *Calinski-Harabasz Index*
- Visualizar resultados con **PCA 2D**.
- Interpretar clusters mediante **análisis exploratorio** por variables (boxplots y perfiles por cluster).

---

## 🧠 Conceptos clave
- **K-Means:** agrupa por cercanía a centroides (rápido y fuerte como baseline).
- **GMM:** modelo probabilístico (clusters con forma elíptica, asignación “suave”).
- **Escalado (StandardScaler):** esencial para clustering cuando las variables están en distintas escalas.
- **PCA:** reduce dimensionalidad para visualizar sin perder demasiada variación.

---


