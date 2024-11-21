# 📊 Análisis de Métricas de Interacción

## 📌 Introducción

Este proyecto analiza el comportamiento de los usuarios en una aplicación de productos alimenticios, centrándose en dos objetivos principales:

1. **Embudo de ventas:** Evaluar el proceso desde el primer contacto con la aplicación hasta la compra final, identificando las etapas con mayores abandonos.
2. **Experimento A/A/B:** Comparar el comportamiento de los usuarios entre dos grupos de control y un grupo de prueba con un diseño de fuente nuevo para evaluar su impacto en la experiencia del usuario.

El análisis utiliza **Python** y bibliotecas como `pandas`, `seaborn`, y `scipy`, proporcionando información clave para la optimización de la interfaz de usuario y la experiencia general.

---

## ⚙️ Herramientas Utilizadas

- **Lenguaje:** Python
- **Entorno:** Jupyter Notebook
- **Bibliotecas:** pandas, numpy, matplotlib, seaborn, scipy

---

## 🔍 Análisis

### 1️⃣ Embudo de Ventas
Se evaluó el flujo de usuarios desde el primer contacto hasta la compra final:
- Identificación de las etapas críticas con mayor abandono.
- Propuestas de mejoras en las áreas de mayor pérdida de usuarios.

### 2️⃣ Experimento A/A/B
Se analizaron tres grupos:
- **Grupo 246 y 247 (Control):** Mantuvieron el diseño original.
- **Grupo 248 (Prueba):** Se implementó un diseño de fuente nuevo.

Se aplicaron pruebas estadísticas (chi-cuadrado) para determinar si el nuevo diseño afectó significativamente el comportamiento del usuario.

---

## 📝 Conclusiones

### 1️⃣ Resultados
- **Grupos de Control (246 y 247):** 
  - No se encontraron diferencias significativas (p-valor = 1.0), validando la correcta asignación de usuarios.
- **Grupo de Prueba (248) vs. Grupos de Control:** 
  - Los p-valores para todos los eventos fueron mayores al nivel de significación ajustado (0.02), indicando que el cambio de fuente no tuvo un impacto significativo.

### 2️⃣ Interpretación
- **Grupos de Control:** La asignación entre los grupos de control fue adecuada, ya que no mostraron diferencias relevantes.
- **Grupo de Prueba:** El nuevo diseño de fuente no afectó negativamente la experiencia del usuario, según los datos analizados.

### 3️⃣ Recomendación Final
Aunque el cambio de fuente no mostró un impacto significativo en el comportamiento del usuario, se recomienda considerar otros factores cualitativos antes de tomar una decisión definitiva sobre su implementación.

---

## 📁 Estructura del Proyecto

1. **Preparación de datos:** Limpieza y preprocesamiento.
2. **Análisis del embudo de ventas:** Visualización y evaluación de las tasas de conversión.
3. **Pruebas estadísticas:** Evaluación del experimento A/A/B.
4. **Conclusiones y recomendaciones:** Interpretación de los hallazgos y sugerencias.

---

# 🤝 Contribuciones
¡Sugerencias y mejoras son bienvenidas!  
Si deseas contribuir a este proyecto, por favor:  
- Crea un *issue* para reportar problemas o sugerir mejoras.  
- Abre un *pull request* con los cambios que quieras proponer.  

¡Gracias por tu interés en mejorar este proyecto! 😊
