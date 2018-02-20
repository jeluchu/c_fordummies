## Introducción
Aquí os dejo información sobre las librerías que usamos más comúnmente en el lenguaje de C, y además también inluyo una tabla de cada una en donde vienen sus funciones y para que contiene cada librería. Recordad que hago los apuntes según dónde programa, en Ubuntu. Recordad que no todos los sistemas opertivos disponen de todas las librerías existentes.
##
### #INCLUDE <STDIO.H>
>Contiene tipos, macros y funciones para la realización de tareas de E/S.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|clearerr| fclose|feof|ferror|**fflush**|          
fgetc|fgetpos|fgets|fopen|formato|
|**fprintf**|fputc|fputs|fread|feopen   
|**fscanf** |fseek|fsetpos|ftell|fwrite
|getc |**getchar**|gets |perror|**printf**
|putc |**putchar**|puts|remove|rename
|rewind|**scanf**|setbuf|setybuf|**sprintf**
|sscanf|tmpfile|tmpnan|ungetc|vfprintf                      
|vprintf|vsprintf|--------- |---------|---------                 
 ##
 ### #INCLUDE <STDLIB.H>
>Contiene tipos, macros y funciones para la conversión numérica, generación de números aleatorios, búsquedas y ordenación, gestión de memoria y tareas similares.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|abort| abs|atexit|atof|atoi|          
atol|bsearch|calloc|div|exit|
|free|getenv|labs|ldiv|**malloc**   
|mblen |mbstowcs|mbtowc|qsort|rand
|**realloc** |srand|srtod |strtol|strtoul
|**system** |wctomb|---------|---------|---------

 ##
 ### #INCLUDE <STRING.H>
>Contiene tipos, macros y funciones para la manipulación de cadenas de caracteres.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|memchr| memcmp|memcpy|memmove|**memset**|          
strcat|strchr|strcmp|strcoll|strcpy|
|strcspn|strerror|strlen|strmcat|strmcmp   
|strmcpy |strpbrk|strrchr|strspn|strstr
|strtok |strcfrm|--------- |---------|---------
##
 ### #INCLUDE <CTYPE.H>
>Contiene varias funciones para comprobación de tipos y transformación de caracteres.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|tolower| toupper|---------|---------|---------|          
##
 ### #INCLUDE <LOCALE.H>
>Contienen varias macros, funciones y tipos para unidades locales, como unidad monetaria, tiempo, dígitos, etc.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|localeconv| setlocale|---------|---------|---------|
##
 ### #INCLUDE <MATH.H>
>Contiene una macro y varias funciones matemáticas.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|Acos| Asin|atan|atan2|ceil|          
**cos**|cosh|**Exp**|Fabs|floor|
|fmod|frexp|ldexp|**log**|**log10**   
|modf |**pow**|**sin**|sinh|**sqrt**
|**tan** |tanh|--------- |---------|---------
##
 ### #INCLUDE <SETJMP.H>
>Contienen declaraciones que proporcionan una forma de evitar la secuencia normal de llamada y regreso de funciones.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|longjmp| setjmp|---------|---------|---------|
##
 ### #INCLUDE <SIGNAL.H>
>Contiene un tipo, dos funciones y varias macros para manejar condiciones excepcionales que aparecen durante la ejecución, tal como una señal de interrupción de una fuente externa o un error en la ejecución.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|raise| signal|---------|---------|---------|
##
 ### #INCLUDE <TIME.H>
>Contiene tipos, macros y funciones para la la manipulación de información sobre fechas y horas.

|                |        |            |             |                         |
|----------------|------------|-------------------|--|---------------------------|
|asctime|clock|ctime|difftime|Gmtime|          
localtime|mktime|strftime|time|---------|
##

![Icono GDM](./fotos/superdos.png)
