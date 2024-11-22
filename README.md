# Algoritmos de Ordenamiento y Búsqueda

Este repositorio contiene tres scripts con implementaciones de algoritmos de ordenamiento y búsqueda de valores en un arreglo. Los algoritmos implementados son:

1. **Bubble Sort**: Algoritmo de ordenamiento basado en la comparación y el intercambio de elementos adyacentes.
2. **Selection Sort**: Algoritmo de ordenamiento basado en la selección repetida del mínimo (o máximo) elemento y su colocación en la posición correcta.
3. **MaxMin Finder**: Algoritmo para encontrar el valor máximo y mínimo en un arreglo de enteros.

## Scripts

### 1. BubbleSort.py

**Descripción**: Este script implementa el algoritmo de ordenamiento Bubble Sort. La función `bubble_sort` recibe un arreglo de enteros y lo ordena en orden ascendente.

**Funcionamiento**:
- Recorre el arreglo repetidamente, comparando elementos adyacentes y los intercambia si están en el orden incorrecto.
- Si en una pasada no se realiza ningún intercambio, el algoritmo termina anticipadamente, ya que el arreglo está ordenado.

**Ejemplo de uso**:

```python
print(bubble_sort([64, 34, 25, 12, 22, 11, 90]))  # Esperado: [11, 12, 22, 25, 34, 64, 90]
print(bubble_sort([1, 2, 3, 4, 5]))               # Esperado: [1, 2, 3, 4, 5] (arreglo ya ordenado)


``` Referncias
Bubble Sort en Python. (s. f.). El Libro de Python. https://ellibrodepython.com/bubble-sort
GeeksforGeeks. (2023b, agosto 28). Python Program for Selection Sort. GeeksforGeeks. https://www.geeksforgeeks.org/python-program-for-selection-sort/
GeeksforGeeks. (2021, 17 junio). max() and min() in Python. GeeksforGeeks. https://www.geeksforgeeks.org/max-min-python/
