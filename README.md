# Proyecto-Bioinformatica
Escritura y Lectura resistente a mutaciones:

Para lograr que tanto la escritura como lectura de adn sean resistentes a mutaciones y errores, se usará raptor codes un tipo de código 
de corrección de errores(fountain codes) a modo de que al producirse errores y mutaciones la información se pueda volver a decodificar sin 
perdida ni corrupcion en los datos.
Con el tiempo seria  interesante hacer una comparación encomo se desempeñan diversos tipos de codificaciones y así poder encontrar 
cúal es la mas eficiente para el caso del adn, caso en el cual el alfabeto es pequeño(tamaño 4) pero el largo de la entrada es 
abismalmente grande. Pero como estancia inicial solo se usará raptor codes por ser el codigo de corrección de errores mas eficiente 
actualmente.
