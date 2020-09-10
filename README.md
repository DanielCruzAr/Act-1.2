# Algoritmos de búsqueda y ordenamiento
## Algoritmo de selección
Este método busca en el arreglo el valor más grande y lo intercambia por el que se encuentra en la última posición.
Este algoritmo es de complejidad O(n^2) en el peor de los casos pues contiene un ciclo "for" anidado, lo que hará que se repita el doble de la longitud del vector que recibe la función.
## Algoritmo de burbuja
Este método va comparando cada elemento del arreglo con el siguiente, si el primero es mayor que el segundo se intercambian. 
Es de complejidad O(n^2) en el peor de los casos, pues igual contiene un ciclo anidado.
## Algoritmo merge
El arreglo principal se va dividiendo en dos subarreglos, los cuales se ordenan y se juntan. Es de complejidad O(n) pues el proceso se repite el mismo número de veces que los elementos de la lista.
## Búsqueda secuencial
Busca la clave introducida explorando uno a uno los elementos de la lista. 
Como utiliza un solo ciclo "for" la complejidad es de O(n) pues la operación se repite el mismo número de veces que los elementos de la lista.
## Búsqueda binaria
Se sitúa la lectura al centro de la lista y se le comprueba contra la clave introducida. Si la clave es menor al valor central, se busca entre el valor mínimo de la lista y el valor central - 1. Si la clave es mayor, se busca entre el valor máximo y el valor central + 1. El proceso se repite menos número de veces que los elementos de la lista, por lo cual es de eficiencia O(log2n).
