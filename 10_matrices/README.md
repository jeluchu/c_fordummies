## MATRICES
### Introducción
En esta lección podrás aprender nuevas funciones que podrás utilizar en este lenguaje, además de bucles, formas de adjudicar tamaños de memoria, etc. A medida que avanzamos, la dificultad aumentará, pero no dudes en ver algunos de los ejemplos que te proporciono.
##
### Bucle "FOR"
`for (int i; i<count; i++){code}`  

**"For" es un bucle** muy potente que tiene varias formas de implementarlo, la forma más común es la siguiente: 
```sh
for ('Inicia declarando la variable'; 'Crea una condición a modo de límite'; 'Incrementa la variable declarada')
```
##
### Adjudicar tamaños de memoria

`malloc(size_t capacidad)`  

**Adjudica el espacio para un objeto**, cuyo tamaño es especificado por "capacidad" (por ejemplo puede ser un double). 

##


`realloc(*nombre, size_t double)`   

**Cambia el tamaño** del objeto que punta a nombre, por el tamaño que se especifica en double. Si el valor "nombre", es NULL, la función realloc se comporta a igual que la función "malloc" para el tamaño especificado.

##
### Retornar caracteres "GETCH" 
` getc(FILE *stream) `  

Retorna el carácter siguiente desde el stream de entrada apuntando por el **stream**.  

(FILE *stream), es una variable con un flujo de fichero. **Si llega al final de fichero o hubiera algún error (-1), la función devuelve EOF.**

##
### Enviar caracteres especificados
` ungetc(char c, FILE *stream) `  

Esta función envía el carácter especificado por c, en el stream de entrada apuntado por **stream**.  

Los caracteres apilados serán retornados por lecturas posteriores en ese stream en orden inverso al que fueron apilados.  

**Si la función ungetc es llamada demasiadas veces** al mismo stream sin una lectura interventiva o una operación de posicionamiento de fichero en ese stream, **entonces la operación falla. Tornando al valor EOF.**

##
### End Of File (EOF)
`EOF`  
Es una **expresión constante y negativa**, que es retornada por varias funciones. Indica que no hay más datos de una entrada de un stream.


> Escrito por [Jéluchu](https://http://jeluchu.github.io/)


