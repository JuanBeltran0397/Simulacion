# 🎲 Simulación de Yahtzee con Método de MonteCarlo

## 📌 Descripción

Este proyecto consiste en la implementación de una simulación del juego de mesa **Yahtzee** utilizando el lenguaje de programación Python. El sistema enfrenta a dos jugadores automáticos que toman decisiones estratégicas mediante el uso del **método de MonteCarlo**, con el objetivo de maximizar su puntuación en cada turno.

El programa no solo reproduce la lógica del juego, sino que también permite analizar el comportamiento probabilístico del mismo a través de estadísticas y visualizaciones gráficas.

---

## 🎯 Objetivos

* Implementar el juego Yahtzee para dos jugadores con Python.
* Simular lanzamientos aleatorios con 5 dados.
* Aplicar el método Montecarlo para seleccionar la mejor jugada posible.
* Calcular automáticamente los puntajes de cada categoría


---

## 🧠 Metodología

El programa utiliza el método de **MonteCarlo**, el cual consiste en realizar múltiples simulaciones aleatorias para estimar el valor esperado de distintas decisiones.

En cada turno:

* Se generan valores aleatorios para los dados (distribución uniforme entre 1 y 6).
* Se evalúan todas las posibles combinaciones de dados a conservar (32 combinaciones posibles).
* Para cada combinación, se simulan múltiples tiradas futuras.
* Se calcula el puntaje promedio (valor esperado).
* Se selecciona la opción que maximiza dicho valor.

Finalmente, se elige la mejor categoría disponible en función del puntaje obtenido.

---

## ⚙️ Tecnologías utilizadas

* **Python**
* **Google Colab**
* **Matplotlib** (para visualización de datos)
* **Collections (Counter)** para análisis de frecuencias

---

## 📊 Resultados

El programa genera diferentes resultados y visualizaciones:

* 🏆 Puntaje total de cada jugador
* 📉 Diferencia de puntos entre jugadores
* 📊 Frecuencia de combinaciones (yahtzee, full, escalera, etc.)
* 🎲 Distribución de las caras de los dados
* 📈 Comparación de puntajes por categoría

Además, se observa que al aumentar el número de simulaciones, los resultados tienden a estabilizarse, lo cual evidencia la **convergencia del método de MonteCarlo**.

---

## ▶️ Cómo ejecutar el proyecto

1. Abrir el archivo en **Google Colab** o entorno local con Python.
2. Ejecutar el programa.
3. Ingresar el número de simulaciones cuando se solicite.
4. Observar los resultados en consola y las gráficas generadas.

---

## 📂 Estructura del proyecto

* Funciones para simulación de dados
* Sistema de puntuación del juego
* Algoritmo de decisión (MonteCarlo)
* Clase `Jugador` para manejo de estado
* Generación de estadísticas
* Visualización de resultados

---

## ⚠️ Consideraciones

* El modelo utiliza una versión simplificada de MonteCarlo (no reevalúa decisiones en cada tirada intermedia).
* Los resultados pueden variar dependiendo del número de simulaciones.

---

## 👨‍💻 Autores

Proyecto desarrollado por:
* **Juan Fernando Beltran**
* **Jhojanth Camilo Alegria**

---

## 📌 Conclusión

Este proyecto demuestra cómo el método de MonteCarlo puede aplicarse en problemas de toma de decisiones bajo incertidumbre, permitiendo aproximar soluciones eficientes en escenarios donde el análisis exacto resulta complejo.

