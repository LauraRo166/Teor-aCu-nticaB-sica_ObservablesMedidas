
# Teoría cuántica básica, Observables y Medidas

## Estructura Repositorio

- En el repositorio se encuentra un archivo .gitignore ya que el trabajo se realizó desde Intellij y se desea evitar la inclusión del directorio .idea.
- El Jupyter **donde se encuentran los ejercicios desarrollados** es el archivo llamado **TeoriaCuantica_ObservablesyMedidas**.

  
## Simule el primer sistema cuántico descrito en la sección 4.1.

***Librerías:*** Para esta simulación es necesaria la librería numpy.

***Ejecución:*** La simulación pedirá un serie de entradas para poder retornar las probabilidades. Se pedirá en el siguiente orden:
 - Número de posiciones.
 - Amplitudes de las posiciones (De la forma a+bj)
 - Posición para calcular la probabilidad.
 - La probabilidad de encontrar la partícula en la posición dada.
 - Se preguntará si se desea ingresar otro vector.
 - En caso de que no el código finalizará. En caso de que si se pedirá el ingreso de las amplitudes para el nuevo estado.
 - La probabilidad de transición al nuevo estado.

## Complete los retos de programación del capítulo 4.

*Para esta sección es necesaria la librería numpy.*

1. ***Amplitud de transición.*** 
    **Ejecución:** 
    - Se ingresan los vectores uno por uno de la forma [1+0j,0+0j,1+0j] → 1,0 0,0 1,0
    - Se imprime la probabilidad de transición.
    - 
2. ***Media y Varianza de una matriz hermitiana.***
    **Ejecución:** 
    - Elementos del vector en la forma ya descrita.
    - La matriz se ingresa fila por fila, cada fila se ingresa de igual manera que el vector.
    - Imprime si la matriz es hermitiana o no.
    - Si es hermitiana imprime la media y varianza.

3. ***Valores propios del observable.***
   **Ejecución:**
    - Elementos del vector en la forma ya descrita.
    - Elementos de la matriz de la forma ya descrita.
    - Imprime si la matriz es hermitiana o no.
    - Si es hermitiana imprime los valores y vectores propios del observable, junto a las probabilidades de cada vector y la suma de probabilidades de los mismos.

4. ***Dinámica del sistema.***
   **Ejecución:**
    - Elementos del vector en la forma ya descrita.
    - Cantidad de matrices unitarias.
    - Ingreso de los elementos de  las matrices de la forma ya descrita.
    - Imprime el estado final.
   
## Realice los siguientes problemas e incluyalos como ejemplos

1. ***4.3.1***
   **Librería:** Numpy
   **Ejecución:** Al ejecutarse se imprimen las probabilidaes de colapso tanto de izquiera como de derecha.

2. ***4.3.2***
   **Librería:** Numpy, MatPlotLib
   **Ejecución:** Muestra un diagrama de barras con las probabilidades de colapso calculadas anteriormente.
    
    **NOTA:** Es necesario ejecutar antes 4.3.1.

3. ***4.4.1***
   **Librería:** Numpy
   **Ejecución:** Al ejecutarse comprueba si las matrices ya dadas por el ejercicio son unitarias o no. Además de verificar si así mismo su producto también lo es o no.

4. ***4.4.2***
   **Ejecución:** Con el estado inicial y la matriz U ya dada por el ejercicio al ejecutarse realiza los 3 clicks. Calcula la probabilidad en el punto 3 en el click3.

5. ***Discusiones 4.5.2 y 4.5.3*** 
    Las discusiones se encuentran al final del archivo Jupyter.

