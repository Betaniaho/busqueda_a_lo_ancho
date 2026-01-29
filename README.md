# busqueda_a_lo_ancho_de_arbol_de_expansion
Introducción

Los árboles forman una de las subclases de gráficas que más se utilizan. En particular, la ciencia de la computación hace uso de los árboles ampliamente. En computación, los árboles son útiles para organizar y relacionar datos en una base de datos. Los árboles surgen en problemas teóricos como el tiempo óptimo para ordenar. Uno de los algoritmos para recorrer un árbol es búsqueda a lo ancho, el cual busca procesar todos los vértices en un nivel dado antes de moverse al nivel más alto que sigue.

Este material fue desarrollado con fines educativos para la materia C0108020 Inteligencia Artificial de los programas de Estudios Ingeniería en Sistemas Computacionales e Ingeniería en Informática Administrativa por la Dra. Betania Hernández Ocaña, Dra. Juana Canul Reich.
El objetivo es recorrer un árbol de expansión con el algoritmo de búsqueda a lo ancho. El código corresponde al pseudocódigo descrito en el libro de Matemáticas discretas sexta edición de Richard Johnsonbaugh.

![pseudocódigo_busqueda_a_lo_ancho](https://github.com/user-attachments/assets/b1bd4035-7b01-4db0-8907-b80737a7abab)


El código recorre un árbol de expansión por default de 9 vertices y 8 aristas, el cual puede ser modificado por el usuario final.
El árbol debe cumplir con el teorema: Si T es una gráfica con n vértices, las siguientes son equivalentes:

• a) T es un árbol

• b) Si <i>v</i>  y  <i>w</i> son vértices en T, existe una trayectoria simple única de v  a  w (definición de árbol).

• c) T es conexa y acíclica.

• d) T es conexa y tiene n − 1 aristas.

• e) T es acíclica y tiene n − 1 aristas.

![código_java_busqueda_a_lo_ancho](https://github.com/user-attachments/assets/b9e6fbe7-85e4-44cb-855c-019864fa9814)

La compilación del código da como salida el vector de vertices visitados por el algoritmo de búsqueda a lo ancho.

![salida](https://github.com/user-attachments/assets/8b843ed7-5854-4440-a293-045aff559552)

Conclusión:
Los algoritmos de búsqueda son esenciales en la Ciencias de la Computación.
El código puede ser mejorado u optimizado por el usuario final.

Referencias:
Johnsonbaugh Richard.(2005). Matemáticas discretas (6ta.Edi.). Pearson.
