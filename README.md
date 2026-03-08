# ⚔️ Estrategia de Retención y Monetización: RPG Mobile Analysis
-----------------------------------------------------------------
## 📝 Descripción del Proyecto
Este proyecto consiste en un análisis estadístico avanzado para evaluar el comportamiento de monetización y engagement de los usuarios en un ecosistema de videojuegos. El objetivo es identificar si existen diferencias significativas en el gasto y tiempo de juego entre distintos segmentos generacionales, permitiendo tomar decisiones basadas en datos sobre la optimización del Customer Lifetime Value (CLV).

## 🎯 Objetivos
* **Análisis Descriptivo:** Caracterizar el engagement de los usuarios mediante métricas de intensidad de sesión y frecuencia de login.
* **Verificación de Supuestos:** Evaluar la presencia de valores atípicos (Whales) y la distribución del gasto para seleccionar las pruebas estadísticas adecuadas.
* **Prueba de Hipótesis:** Ejecutar tests de significancia para validar si el segmento Millennial representa una oportunidad de ingresos superior frente a la Gen Z.

## 🛠️ Tecnologías y Librerías
* **Python** (versión 3.x)
* **Librerías principales:** *pandas* y *numpy* para la manipulación y estructuración de datos.
* **matplotlib y seaborn** para la visualización de distribuciones de gasto y diagramas de caja.
* **scipy.stats** para la ejecución de pruebas T de Student y análisis de correlación de Pearson.

## 📊 Hallazgos Principales
* **Comportamiento de la Distribución:** El gasto presenta un sesgo positivo pronunciado, donde el 5% de los usuarios (Whales) desplaza la media de ingresos significativamente hacia arriba.
* **Incremento en Métricas:** Los usuarios con alta intensidad de sesión (>60 min/día) mostraron un ticket promedio de compra 45% superior al promedio casual.
* **Validación de Datos:** Se identificó que la retención temprana es el predictor más fuerte de conversión a pago (p-valor < 0.05).
* **Diferencia Significativa:** El test estadístico confirmó que el segmento de 25-35 años tiene una propensión al gasto 15% mayor, validando la inversión en este nicho.

## ✅ Resultados y Conclusiones
* **Recomendación de Inversión:** Se aconseja proceder con el despliegue de eventos de tiempo limitado (LTE) enfocados en el segmento "Hardcore", garantizando un retorno de inversión superior.
* **Análisis de Riesgo:** Aunque los "Whales" generan la mayoría del ingreso, presentan una alta volatilidad. Se recomienda diversificar mecánicas para monetizar la "clase media" de jugadores.
* **Optimización Estratégica:** Dada la naturaleza del Churn detectado, las futuras estrategias deben enfocarse en el onboarding de los primeros 3 días para asegurar el engagement a largo plazo.
