# Exchange-Energy-between-polytrope-and-Wymann-IIa-fluid

Este repositorio contiene el código y la documentación de mi trabajo de titulación en Física Teórica (ESPOCH), que modela el **intercambio de energía** entre un **fluido relativista** y un **politropo** en el marco de la **desacoplación gravitacional** por **Deformación Geométrica Mínima Extendida (MGDe)**.

---

## Estructura del Repositorio

Los archivos están organizados para facilitar la comprensión y reproducibilidad del proyecto.

### Código Fuente y Análisis

* `FINAL.nb`: El notebook principal que contiene todos los cálculos y análisis, desde la formulación inicial hasta la generación de los resultados finales.
* `FINAL_C1.nb`, `FINAL_C2.nb`, `FINAL_C3.nb`, `FINAL_C4.nb`: Notebooks que elaboran los resultados específicos para los casos realistas analizados en los capítulos de la tesis.
* `TFG_gallegos_quizhpe_integral_numerica_v3_y_v5.nb`: Archivo con el código final para resolver la integral numérica, un componente clave de los cálculos.
* `tolmancorregido.nb`: Notebook de referencia que incluye correcciones y mejoras a un modelo previo basado en el fluido de Tolman IV.

### Documentación y Visualizaciones

* `INTERCAMBIO ENÉRGETICO ENTRE UN POLITROPO Y UN FLUIDO TIPO WYMAN IIA.pdf`: El documento completo de la tesis.
* `FINAL_GRÁFICAS_PRESENTACION.nb`: Notebook usado para generar los gráficos y visualizaciones para la presentación.
* `FINAL_GRÁFICAS_PRESENTACION.pdf`: Un PDF que contiene una selección de los gráficos más importantes del proyecto, listos para su visualización.

---

## Objetivos de la Investigación

### Objetivo General
Analizar el intercambio energético relativista entre un politropo y un fluido tipo Wyman IIa.

### Objetivos Específicos
* Realizar un estudio bibliográfico sobre el intercambio energético en fluidos relativistas.
* Estudiar el método de desacoplamiento gravitacional por deformación mínima extendida.
* Utilizar un fluido isótropo tipo Wyman IIa como "semilla" en el algoritmo de (Ovalle et al., 2022) para resolver el problema.
* Analizar el intercambio energético entre ambas fuentes gravitacionales.

---

## Resultados Principales

El estudio arrojó las siguientes conclusiones:

### Aceptabilidad Física y Comportamiento del Modelo
* **Sector material**: La densidad de energía ($\rho$) y las presiones radial ($p_r$) y tangencial ($p_t$) son positivas y decrecen desde el centro. La presión tangencial es mayor que la radial ($p_t > p_r$), una característica de la **anisotropía**.
* **Influencia del parámetro $K$**: Al aumentar la constante politrópica $K$, los valores del sector material disminuyen.
* **Métricas**: Las componentes métricas del espacio-tiempo, $e^{-\lambda}$ y $e^{\nu}$, son positivas y se comportan de forma monótona, asegurando la viabilidad del modelo.

### Condiciones de Estabilidad y Causalidad
* **Condiciones de Energía**: La **Condición de Energía Dominante (DEC)** se cumple para todos los casos. Sin embargo, la **Condición de Energía Fuerte (SEC)** solo se satisface para los modelos con $K=0.44$ y $K=0.47$, lo que los hace **físicamente estables**. El modelo con $K=0.43$ es **inestable** al violar esta condición.
* **Corrimiento al rojo ($Z$)**: Es positivo y decreciente. Sus valores en la superficie están dentro de los límites físicos.
* **Condición de Causalidad**: Las velocidades del sonido radial y tangencial no superan la velocidad de la luz, lo que valida el modelo.

### Anisotropía e Intercambio Energético
* **Anisotropía**: Es positiva y aumenta con el radio. Es nula en el centro, lo que indica un núcleo en equilibrio.
* **Intercambio Energético ($\Delta E$)**: Es positivo y creciente desde el centro hacia la superficie. Un valor $\Delta E > 0$ significa que el politropo **cede energía** al fluido perfecto para coexistir. A menor valor de $K$, mayor es la zona de intercambio energético.

---

## Referencias Clave

* Contreras, E., & Stuchlik, Z. (2022). **Energy exchange between Tolman VII and a polytropic fluid.** *European Physical Journal C, 82*(4), 365.
* Ovalle, J., Contreras, E., & Stuchlik, Z. (2022). **Energy exchange between relativistic fluids: the polytropic case.** *European Physical Journal C, 82*(2), 168.
* Ovalle, J. (2019). **Decoupling gravitational sources in general relativity: The extended case.** *Physics Letters B, 788*, 213–218.
