# Logistic_Regression_Derivates-Matrix-Observation
Logistic Regression
La regresión logística es en realidad un método de clasificación. Este tipo de método introduce una no linealidad adicional sobre un clasificador lineal, esto es: $f(x) = w^{T} x + b$, usando una función logística (o sigmoide), $\sigma()$.
\linebreak 

El clasificador de la Regresión Logística se define a continuación:

\[
    \sigma(f(x_{i}))=\left\{
                \begin{array}{ll}
                  \geq 0.5 y_{i} = +1\\
                  <  0.5 y_{i} = -1
                \end{array}
              \right.
\]
\linebreak 

Donde, $ \sigma(f(x)) = \frac{1}{1 + \exp^{-f(x)}}$.
