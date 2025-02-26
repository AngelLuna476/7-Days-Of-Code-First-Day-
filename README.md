<h1 align="center">#7_Days_Of_Code_(1/7)</h1>

*Proyecto del programa de formación ORACLE NEX EDUCATION en conjunto con ALURA LATAM*

Comienzo de la jornada de #7DaysOfCode ;), en este primer desafío se corrigen unas operaciones en donde el número es el mismo, mas sin embargo, no son del mismo tipo;
Se busca lograr realiza rla operación mediante el uso de Java Scrip que la operación y/o comparación de los números se realicen de la forma correcta.

---

## Marco Teórico:

Existe una situación muy común para quienes usan Javascript: problemas con los tipos de 
variables al comparar los valores de dos variables entre sí.

En lenguajes de programación compilados, como Java y C#, este problema se detecta en tiempo 
de compilación, y tienes un aviso claro del error mientras desarrollas el código.

En JavaScript, estos errores pasan desapercibidos, ya que el código no pasa por un compilador. 
Es decir, los errores solo aparecen en tiempo de ejecución.
 
La parte más confusa para quienes están comenzando a aprender lógica con JavaScript es la 
operación de igualdad entre valores. Dependiendo de cómo escribas tu código, JavaScript 
hará una conversión de tipo a un tipo booleano de manera implícita (automática), y esto 
afectará a variables que eran Strings, Numbers, Object, etc.

Esto causa algunos comportamientos extraños, como todos estos ejemplos a continuación que retornan true:

console.log( false == '0' );
console.log( null == undefined );
console.log( " \t\r\n" == 0 );
console.log( ' ' == 0 );

Lo cual no tiene necesariamente mucho sentido.
(Puedes probar todo esto yendo a tu navegador, haciendo clic con el botón derecho, 
eligiendo la opción “Inspeccionar” y la pestaña “Consola”. En esa pestaña, basta 
con copiar y pegar cada una de las líneas anteriores para confirmar que todas 
realmente retornan true).

---

## Requisitos:

Este proyecto usa únicamente **JavaScript**.  
Se puede probar directamente en tu navegador.

---

## Tecnologías Usadas 💻

- **[JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)**.
