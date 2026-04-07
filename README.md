# Solano-post1-u3

Columna izquierda (073F:0200, 073F:0210...) Es la dirección de memoria en formato segmento:offset. Cada fila avanza 16 bytes (0x10), mostrando dónde comienza ese bloque en la memoria.
Columna central (valores hex como AB CD EF...) Son los datos almacenados en memoria representados en hexadecimal. Cada par de caracteres es un byte, y se muestran 16 bytes por fila separados en dos grupos de 8 para facilitar la lectura.
Columna derecha (puntos ............) Es la representación ASCII de esos mismos bytes. Cuando un byte no corresponde a un carácter imprimible (como AB, CD, EF), se muestra un punto "." en su lugar.
