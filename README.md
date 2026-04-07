# Solano-post1-u3

C1:
Se ejecutó el comando R al iniciar DEBUG sin argumentos. La salida mostró el estado inicial del procesador: los registros de propósito general AX, BX, CX y DX en cero, el registro SP apuntando a 0xFFFE como tope inicial de la pila, y los cuatro registros de segmento (DS, ES, SS, CS) con el mismo valor, correspondiente al segmento del PSP asignado por el DOS. El IP se encontraba en 0x0100, que es la primera dirección ejecutable tras el PSP. Luego se modificó el registro AX con el valor 0x1234 usando R AX, verificando que la modificación es selectiva y no altera el resto del estado del procesador.
C2:
Columna izquierda (073F:0200, 073F:0210...) Es la dirección de memoria en formato segmento:offset. Cada fila avanza 16 bytes (0x10), mostrando dónde comienza ese bloque en la memoria.
Columna central (valores hex como AB CD EF...) Son los datos almacenados en memoria representados en hexadecimal. Cada par de caracteres es un byte, y se muestran 16 bytes por fila separados en dos grupos de 8 para facilitar la lectura.
Columna derecha (puntos ............) Es la representación ASCII de esos mismos bytes. Cuando un byte no corresponde a un carácter imprimible (como AB, CD, EF), se muestra un punto "." en su lugar.
C3:
