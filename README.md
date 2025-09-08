# Exchange-Energy-between-polytrope-and-Wymann-IIa-fluid
Este repositorio contiene el desarrollo y la implementación de los modelos presentados en mi trabajo de titulación en Física Teórica (ESPOCH).

El proyecto aborda el intercambio de energía entre un fluido relativista y un politropo en el marco de la desacoplación gravitacional mediante la Deformación Geométrica Mínima Extendida (MGDe).

## Objetivos de la investigación
### Objetivo General
-> Analizar el intercambio energ´etico relativista entre un politropo y un fluido tipo Wyman
IIa.

### Objetivos específicos
-> Realizar un estudio bibliográfico del intercambio energético entre fluidos relativistas.

-> Estudiar el desacople gravitacional por deformación mínima extendida.

-> Emplear la semilla de fluido isótropo de tipo Wyman IIa en el algoritmo desarrollado por
(Ovalle et al., 2022) para resolver nuestro problema.

->Analizar el intercambio energético de ambas fuentes gravitacionales

## Resultados
### Aceptabilidad Física y Comportamiento del Modelo

-> Comportamiento del sector material: La densidad de energía ($\rho$) y las presiones radial ($p_r$) y tangencial ($p_t$) son funciones positivas, continuas y monótonamente decrecientes desde el centro de la estrella ($r=0$) hacia la superficie. Se observa que la presión tangencial domina a la presión radial ($p_t(r)>p_r(r)$), lo cual es una característica de la anisotropía. La presión radial se anula en la superficie estelar, cumpliendo con la condición necesaria ($p_r(R) = 0$).

-> Influencia de la constante politrópica ($K$): Los valores del sector material ($\rho, p_r, p_t$) disminuyen a medida que la constante $K$ aumenta. Se observa un comportamiento más suave de la presión tangencial en comparación con la presión radial.

-> Comportamiento de las métricas: Las componentes métricas del espacio-tiempo son positivas y finitas. La métrica radial ($e^{-\lambda}$) es monótonamente decreciente, mientras que la métrica temporal ($e^{\nu}$) es monótonamente creciente. Este comportamiento es esencial para la viabilidad del modelo.

### Condiciones de Estabilidad y Causalidad

-> Condición de Energía Dominante (DEC): se satisface para todos los valores de $K$ analizados, lo que valida la plausibilidad física del modelo.

-> Condición de Energía Fuerte (SEC): se cumple para $K = 0.44$ y $K = 0.47$, indicando la estabilidad de estos modelos estelares. Sin embargo, se viola para $K = 0.43$, sugiriendo que este modelo en particular es físicamente inestable.

-> Corrimiento al rojo ($Z$): La función de corrimiento al rojo es positiva y decreciente. Para los modelos estables, el valor en la superficie es menor que el límite $3.842$. Para el modelo inestable ($K=0.43$), el valor es $Z=0.735938$, que es menor al límite universal de $5.211$.

-> Condición de causalidad: El modelo cumple con la condición de causalidad, ya que las velocidades del sonido radial ($v_r^2$) y tangencial ($v_t^2$) en el interior de la estrella no exceden la velocidad de la luz ($c=1$).

### Anisotropía e Intercambio Energético
-> Anisotropía: La anisotropía del modelo es positiva y aumenta con el radio, confirmando que la presión tangencial es mayor que la radial. La anisotropía es nula en el centro de la estrella, lo que indica un estado de equilibrio en el núcleo.

Intercambio Energético ( \Delta E ):

-> El intercambio energético es positivo y creciente desde el centro hacia la superficie, siendo nulo en el centro.

-> Un valor $\Delta E > 0$ implica que el fluido politrópico cede energía al fluido perfecto circundante para mantener la coexistencia dentro del cuerpo estelar.

-> Se observa que una disminución en la constante $K$ genera una zona de mayor intercambio energético. Este intercambio es más elevado en configuraciones más compactas.

## Bibliografía util
-> Contreras, E., Stuchlik, Z. Energy exchange between Tolman VII and a polytropic fluid. Eur. Phys. J. C 82, 365 (2022). https://doi.org/10.1140/epjc/s10052-022-10350-9

-> OVALLE, J. & CONTRERAS, E. & STUCHLIK, Z, 2022. Energy exchange between relativistic
fluids: the polytropic case. Eur. Phys. J. C. Available from DOI: https://doi.org/10.1140/epjc/s10052-022-10168-5.



-> OVALLE, J., 2019. Decoupling gravitational sources in general relativity: The extended case.
Physics Letters B. Vol. 788, pp. 213–218. ISSN 0370-2693. Available from DOI: https://doi.org/10.1016/j.physletb.2018.11.029.





