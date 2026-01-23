# 🏋️‍♀️ Análisis de Machine Learning para la cadena de gimnasios Model Fitness

## 📌 Descripción del proyecto
Este proyecto aplica técnicas de **Machine Learning y análisis de datos** para
estudiar el comportamiento de los clientes de la cadena de gimnasios *Model Fitness*.
El objetivo principal es **predecir la cancelación de clientes (churn)** y segmentar
usuarios mediante técnicas de clustering, con el fin de apoyar estrategias de
retención y toma de decisiones de negocio.

El análisis se desarrolla en un Jupyter Notebook y abarca desde el análisis
exploratorio de datos hasta la construcción de modelos predictivos y la generación
de recomendaciones prácticas.

## 🎯 Objetivos
- Analizar el comportamiento de los clientes y sus patrones de uso.
- Identificar variables clave asociadas a la cancelación de membresías.
- Construir un modelo predictivo de cancelación de clientes.
- Segmentar a los usuarios en clústeres con características similares.
- Proporcionar recomendaciones para mejorar la retención de clientes.

## 📂 Estructura del proyecto
- `datasets/` → Datasets usados en el análisis
- `notebooks/` → Notebook con el análisis de Machine Learning
- `README.md` → Descripción del proyecto en español
- `README_EN.md` → Descripción del proyecto en inglés
- `requirements.txt` → Dependencias del proyecto

## 🛠️ Tecnologías utilizadas
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 🧪 Metodología

### 1️⃣ Análisis exploratorio de datos (EDA)
- Análisis de distribuciones mediante histogramas.
- Evaluación de relaciones entre variables con una matriz de correlación.
- Identificación de patrones relevantes en el comportamiento de los clientes.

<img width="851" height="794" alt="image" src="https://github.com/user-attachments/assets/81d2b1b7-8465-4e37-ae3d-5275d01a5145" />

### 2️⃣ Modelo de predicción de cancelación
- Preparación y escalado de datos.
- Entrenamiento de modelos de clasificación para predecir la cancelación de clientes.
- Evaluación del desempeño del modelo mediante métricas adecuadas.

### 3️⃣ Segmentación de clientes (Clustering)
- Creación de clústeres de usuarios para identificar perfiles de comportamiento.
- Análisis jerárquico mediante dendrogramas.
- Aplicación del algoritmo K-means.
- Análisis de la distribución de clientes y tasas de cancelación por clúster.

<img width="841" height="614" alt="image" src="https://github.com/user-attachments/assets/c5a6094c-97dd-4e77-88cc-b27fc65782c1" />

<img width="679" height="381" alt="image" src="https://github.com/user-attachments/assets/a14dd2a5-d0ec-48ae-819d-5a91b632c596" />

## 📈 Resultados principales
- Se identificaron variables con alta relación con la cancelación de clientes,
  como frecuencia de visitas, tipo de contrato y antigüedad.
- El modelo de predicción permite identificar clientes con mayor riesgo de churn.
- El análisis de clustering reveló grupos de usuarios con comportamientos
  significativamente distintos, incluyendo clústeres con mayor propensión a la
  cancelación.

## 🧠 Conclusiones clave
- La conexión emocional y social tiene mayor impacto en la retención de clientes que la cercanía física al gimnasio.
- La constancia en la experiencia (frecuencia de visitas, participación en clases e interacción) está fuertemente relacionada con la lealtad del cliente.
- Los contratos de corta duración presentan mayor riesgo de cancelación y requieren generar vínculo desde etapas tempranas.
- La presencia de vínculos sociales (amigos, pareja o conocidos) reduce significativamente la probabilidad de cancelación.
- La segmentación mediante clustering (K-Means) permite identificar perfiles de clientes con comportamientos y riesgos de cancelación diferenciados.

## 📊 Recomendaciones estratégicas
### 1️⃣ Crear rituales desde el primer mes

Acciones:
- Implementar una campaña de “Primeros 30 días” con hitos simbólicos como Mi primera clase, Primer reto personal o Primer logro.

Impacto esperado:
- Generar sentido de pertenencia y conexión emocional desde el inicio de la relación con el cliente.

### 2️⃣ Fomentar vínculos sociales

Acciones:
- Promover inscripciones en dúo o grupo.
- Incentivar clases colaborativas y recompensas por referidos.

Impacto esperado:
- Incrementar el apego emocional y reducir la tasa de cancelación.

### 3️⃣ Segmentar acciones por clúster

Acciones:
- Diseñar comunicaciones diferenciadas según el perfil del cliente:
- Clientes activos: reconocimiento y refuerzo positivo.
- Clientes intermedios: motivación y seguimiento.
- Clientes con riesgo de cancelación: incentivos y mensajes emocionales.

Impacto esperado:
- Mayor efectividad en marketing y personalización de la experiencia.

### 4️⃣Reconocer la constancia

Acciones:
- Celebrar la asistencia y los logros mediante reconocimientos simbólicos (insignias, menciones internas, beneficios).

Impacto esperado:
- Reforzar hábitos positivos y fortalecer la comunidad.

## 💡 Valor del proyecto
Este análisis demuestra cómo los modelos de Machine Learning aplicados a churn prediction y segmentación pueden transformarse en estrategias accionables de retención y marketing, integrando datos cuantitativos con factores emocionales y sociales.
