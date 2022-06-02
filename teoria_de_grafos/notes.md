# Teoría de grafos
Es una disciplina que estudia los grafos y sus algoritmos.
Es el estudio de las relaciones entre objetos.
Un grafo es una colección de puntos que estan enlazados entre si con una línea.

### **Puentes de Koningsberg**

Un ejemplo es: Los puentes de Koningsberg.
El cual no tiene solución.

**Nota:**
Los grafos deben tener un número par de aristas.

## ¿Qué es un grafo?
- Vertice: Un punto en el grafo.
- Arista: Una linea entre dos puntos.
- Grafo: Un conjunto de vertices y aristas.

Un grafo G se define como:
G = {V, E}
V = Conjunto de vertices o nodos.
E = Conjunto de aristas.

Podemos decir que E es un subconjunto del producto cartesiano de V consigo mismo. Es decir, E = V x V.

V = {A,B,C,D}
V x V = {(A,A), (A,B), (A,C), (A,D), (B,A), (B,B), (B,C), 
(B,D), (C,A), (C,B), (C,C), (C,D), (D,A), (D,B), (D,C), (D,D)}

- Revisar figura en assets
Entonces:
E = {(A,B), (A,B), (A,C), (A,C), (A,D), (B,A), (B,A), (B,D), (C,A), (C,A), (C,D), (D,A), (D,B), (D,C)}

Eliminar aristas duplicadas:
E = {(A,B), (A,B), (A,C), (A,C), (A,D), (B,D), (C,D)}
