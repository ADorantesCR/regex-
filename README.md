# regex-1

Este código es un script de Python que abre un archivo de texto, elimina las líneas que contienen números y escribe el resultado en un nuevo archivo de texto.

Primero, el código importa la biblioteca de expresiones regulares de Python (re). Luego, establece la ruta del archivo de entrada y salida como cadenas de texto.

A continuación, se define una expresión regular (patron) que coincide con cualquier cadena de dígitos.

Luego, el código abre el archivo de entrada en modo de lectura, lee su contenido y lo divide en líneas utilizando el carácter de nueva línea (\n) como separador.

Después, se abre el archivo de salida en modo de escritura. El código itera a través de cada línea del archivo de entrada y verifica si la línea no contiene números utilizando la expresión regular (patron) y si la línea no está vacía utilizando el método strip().

Si la línea cumple con ambas condiciones, se escribe la línea en el archivo de salida. Finalmente, el código cierra ambos archivos.

Este script podría ser útil en un mercado como el de procesamiento de texto y datos. Podría ser utilizado por editores y redactores para eliminar números de documentos de texto para fines de corrección de pruebas, o por empresas que necesiten procesar grandes cantidades de datos de texto para fines de análisis o minería de datos.
