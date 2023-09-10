# EvidenciaCasoPalindromosPruebasUnitarias
Caso Palíndromos - Pruebas Unitarias
Integrantes: 
Maria Jose Powell
Valentina Huenchuñir
Fernanda Muñoz

ese es el codigo
https://github.com/mjosepc/palidromo1.git

Paso 1
¿Qué hace el método?
Lo que realiza el método es verificar si la palabra entregada es un palíndromo. 

¿Cómo lo hace?
Se asigna una palabra, esta se da vuelta, quedando que el orden de las letras está invertido, paras así compararla con la palabra original.

¿Cómo lo uso?
Este se usó llamando a la función, donde se le entregó una palabra aleatoria, por ejemplo la palabra “oso”, que es una palabra palíndromo, por lo tanto debería retornar true.


Paso 2
2.1 Tras una discusión individual, cada grupo deberá explicar que hace el método detalladamente. 
La función espalindromo pide una cadena como entrada, luego fija la variable resultado, a la cadena se le separa en subcadenas con el comando .split, después, este se da vuelta, en si se invierte con el comando .reverse y por último  vuelve unir en una cadena con el comando .join y como resultado final retorna verdadero si la variable resultado es estrictamente igual a la cadena entregada al principio por lo tanto es palindromo 


Paso 3: Ok! Si el método funciona ¿Qué puede malir sal? ;-) (15 mins.)

3.1Discutir en grupo el diseño de un plan de pruebas para este caso.

probar con letras aleatorias
probar con numeros
probar con caracteres
probar con combinacion de numeros, letras y caracteres
probar con una cadena vacia

pero nos dimos cuenta de que si le entregamos un numero 

