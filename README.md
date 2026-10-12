# Predicción del Riesgo de Falla en Baterías de Vehículos Eléctricos

## Interacción con el proyecto:
Puedes explorar y ejecutar el desarrollo de este proyecto de dos formas:

**En Google Colab:** Ejecuta los notebooks directamente en la nube sin necesidad de configuraciones previas ni instalación de dependencias localmente.
**Localmente:** Clona este repositorio y asegúrate de tener las dependencias instaladas.

## Video:
*Video de la presentación y demostración del proyecto (En proceso)*

---

## Descripción del Proyecto
Este trabajo implementa un sistema de clasificación multiclase mediante aprendizaje supervisado para predecir el nivel de riesgo de falla (**Low**, **Medium**, **High**) en paquetes de baterías de iones de litio de vehículos eléctricos (EV). 

A través del análisis de datos de telemetría y uso (resistencia interna, patrones de carga, temperatura ambiental e indicadores de envejecimiento), se comparan diferentes clasificadores (*Random Forest, MLP, SVM, k-NN, Regresión Logística*) y se evalúa el impacto de técnicas de reducción de dimensionalidad (*PCA* y *UMAP*).