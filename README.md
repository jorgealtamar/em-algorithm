El código implementa el algoritmo Expectation-Maximization (EM) para el modelo de Mezclas Gaussianas (GMM) en Python.

**Concepto:**

El GMM asume que los datos provienen de una mezcla de distribuciones gaussianas, representando cada una un "cluster". El algoritmo EM busca encontrar los parámetros óptimos de estas distribuciones para agrupar los datos.

**Pasos:**

1. **Inicialización de parámetros:** Se eligen aleatoriamente las medias, covarianzas y probabilidades a priori de pertenencia a cada cluster.
   
2. **E-step:** Se calcula la probabilidad de que cada punto pertenezca a cada cluster usando la función de densidad de probabilidad gaussiana.

3. **M-step:** Se actualizan los parámetros del modelo utilizando las probabilidades calculadas.
   
4. **Iteración:** Los pasos E y M se repiten para mejorar la precisión de los parámetros.
   
5. **Visualización:** Se grafican los resultados, mostrando los clusters identificados.

**Objetivo:**

Identificar estructuras de clusters en datos distribuidos de acuerdo con múltiples distribuciones gaussianas.