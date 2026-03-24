Esta es una práctica de la asignatura Procesos Estocásticos.

Se simulará un Paseo Aleatorio Simple. (PAS) y se generarán algunas gráficas asociadas a las simulaciones realizadas.

Un PAS (Paseo Aleatorio Simple) de parámetro p es un proceso estocástico indexado en los naturales.

En tiempo 0, la posición inicial $X_0 = 0$ con probabilidad 1.

Se genera una familia de pasos $Z_t$, con $t$ un natural. $Z_t$ toma los valores 1 con probabilidad p, y -1 con probabilidad 1-p. Las variables $Z_t$ son mutuamente independientes y actúan como pasos del Paseo Aleatorio Simple.

En cada instante de tiempo, se tendrá que la posición se calculará como la posición anterior más el paso que se da en instante t. $X_{t} = X_{t-1} + Z_{t}$.

El PAS entonces modela la posición de un objeto que empieza en posición 0 y se da hacia adelante o hacia atrás por unidad de tiempo, de manera independiente a su movimiento anterior. En este caso, p mide la probabilidad de que se mueva hacia adelante.

