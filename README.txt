Pregunta 1:
El modelo tendrá dos tablas:
-TABLA_USERS: cuenta con dos columnas ID, USER_NAME.
    ID (clave primaria): tipo INT no nulo;
    USER_NAME: VARCHAR(10) no nulo;
-TABLA_URLS: cuenta con 5 columnas ID, URL, FECHA_INICIO,FECHA_FIN,ACTIVO.
    ID (clave primaria): tipo INT no nulo;
    URL: VARCHAR(8) no nulo;
    FECHA_INICIO: DATETIME() no nulo;
    FECHA_FIN: DATETIME() no nulo;
    ACTIVO: BIT;

Pregunta 2:

Para generar las letras que compondrá la parte variable se utilizará una
String que contendrá todos los caracteres posibles. Se creará un array al que
se le irán añadiendo letras de la anterior String de forma aleatoria hasta llegar
a formar un array de 7 letras.