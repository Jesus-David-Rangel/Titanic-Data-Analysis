# Identificación de Factores de Supervivencia en la Tragedia del RMS Titanic

**Descripción del Proyecto:**

Este proyecto realiza un análisis exploratorio y predictivo sobre el conjunto de datos del Titanic, con el objetivo de identificar los principales factores que influyeron en la supervivencia de los pasajeros y construir modelos de predicción básicos. El proceso incluye la limpieza e imputación de datos, la ingeniería de características (como la extracción de títulos, el tamaño de familia y la variable “is_alone”), la visualización de patrones relevantes y la evaluación de modelos como Regresión Logística, Bosque Aleatorio y métodos de ensamble.

El análisis reveló que el sexo fue la variable más influyente, ya que las mujeres presentaron una probabilidad de supervivencia significativamente mayor que los hombres. La clase del billete también mostró una fuerte correlación con la supervivencia, donde los pasajeros de primera clase sobrevivieron con más frecuencia que los de segunda y tercera clase. La edad desempeñó un papel importante: los niños y adultos jóvenes tendieron a sobrevivir más, especialmente en combinación con el género y la clase social. Además, el tamaño de la familia presentó una relación no lineal: las familias pequeñas (de dos a cuatro miembros) obtuvieron mejores resultados que las muy grandes o los pasajeros que viajaban solos.

Asimismo, se observó que las tarifas más altas se asociaron con una mayor probabilidad de supervivencia, reflejando diferencias socioeconómicas entre los pasajeros. Los títulos extraídos de los nombres (como Mr, Mrs o Miss) y el puerto de embarque también aportaron información predictiva relevante. Tras la ingeniería de características, el modelo de Bosque Aleatorio alcanzó una precisión cercana al 80 % en la fase de validación, siendo las variables más importantes el sexo, la clase, la tarifa, la edad y el título.

En conclusión, las características demográficas y socioeconómicas simples explican gran parte de la variación en la supervivencia. La ingeniería de variables, especialmente la relacionada con los títulos y el tamaño de la familia, mejora significativamente la capacidad predictiva y la interpretación de los modelos.

---

# Identification of Survival Factors in the RMS Titanic Tragedy

**Project Description:**

This project performs exploratory and predictive analysis on the Titanic dataset with the aim of identifying the main factors that influenced passenger survival and building simple predictive models. The process includes data cleaning and imputation, feature engineering (such as title extraction, family size, and the “is_alone” variable), visualization of relevant patterns, and evaluation of models including Logistic Regression, Random Forest, and ensemble approaches.

The analysis revealed that sex was the most influential variable, as women had a significantly higher probability of survival than men. Ticket class also showed a strong correlation with survival, with first-class passengers surviving more frequently than those in second and third class. Age played a key role: children and young adults tended to survive more, especially in combination with gender and class. Family size displayed a non-linear relationship with survival, as small families (two to four members) achieved better outcomes than very large families or solo travelers.

Higher fares were associated with increased survival, reflecting socio-economic advantages. Extracted name titles (Mr, Mrs, Miss, etc.) and port of embarkation also provided additional predictive power. After feature engineering, the Random Forest model achieved validation accuracy close to 80%, with the most relevant features being sex, class, fare, age, and title.

In conclusion, simple demographic and socio-economic characteristics explain most of the variation in survival. Feature engineering, particularly involving titles and family structure, significantly enhances both the predictive performance and interpretability of the models.
