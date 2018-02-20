## Introducción
Comenzamos con **"C para Dummies"**, en el cuál según las cosas que voy aprendiendo de este lenguaje, iré subiéndolas a este repositorio. Si queréis ver ejemplos de todas estas lecciones, solo tendréis que dirigiros a [**"Programming"**](https://github.com/Jeluchu/programming).  

Una vez dicho todo esto, comencemos con las nociones básicas de esta nueva lección. En este caso comenzaremos con **00_primitivas**, podrás ver ejemplos en [**"Primitivas"**](https://github.com/Jeluchu/programming/tree/master/2017/clase/00_primitivas).
##
### PRINTF
`printf("Texto");`
`printf("Texto\n");`  

>Printf, es una función con la cuál podremos imprimir en pantalla lo que haya entre las comillas. Si fuera una variable, solo tendríamos que poner:  
 `printf("El valor es %i", valor);`
 Con lo cuál de ese modo %i sería una variable (hay varios tipos que más adelante podréis ver, y lo que ponemos después de la coma, es a que variable estamos llamando), lógicamente tenemos que tener en cuenta de que forma estamos llamando a la variable, ya que si la declaramos como tipo **"int"**, será un entero, y por lo tanto usaremos **"%i"**.
 ##
 ### FPRINTF
 `fprintf("Texto");`
`fprintf("Texto\n");`
> Sigue la misma estructura que **"printf"**, solo que este,  permite que la salida de printf pueda escribirse en cualquier archivo. Su uso suele ser para la impresión de errores, pero puede funcionar con cualquier archivo abierto.
##
### SCANF
 `scanf("%i", &valor);`  

>Lee los datos de entrada en el stdin (flujo de entrada estándar). El Ampersand (&), se utiliza para indicar una dirección de memoria de la variable donde se almacenará el dato. Cuando se guardan de cadenas de caracteres, al tratarse de un array de tipo char, el & se omite.
  ##
  ### FSCANF
 `fscanf("%i", &valor);`  

>Es similar a "Scanf", ya que lee los datos de entrada, pero lo lee en un flujo de entrada dado, por lo general un fichero en el stdin.
  ##

![Icono GDM](./fotos/superuno.png)
