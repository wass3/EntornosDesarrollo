# ED_Debug - TEMA 2 //I.E.S MZ    <img src="https://pbs.twimg.com/profile_images/603270390476120064/HpKRMIqB_400x400.png" alt="drawing" width="70"/>

**1. En la función1… Què fan aquestes línies de codi?**

> String string2 = "string2";

Lo que hace es crear una variable de tipo string y añadirle el valor "string2"

> string2= string2.substring(0, string2.length()-1);

Lo que hace esta línea de código es modificar la variable string2 seleccionando solo algunos caracteres. Es decir, selecciona los caracteres que van desde la posición 0 ("s") hasta la posición equivalente a la longitud del string (6) menos 1. Por lo que el valor de esa variable será "string".

> string2=string2+"1";

Esta línea de código modifica el valor que hay actualmente en string2 ("string") y lo concatena con ese ' + "1" '. Dando como resultado "string1"



**2. Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?**

string1 = "string1";  
string2 = "string1";

**3. Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?**

> El operador que se debería usar para comprobar si 2 string son iguales debería ser la función [string].equals(Objeto)

> En conclusión la condición del if debería ser: (arra1.equals(array2))

(No sé exactamente el por qué no se usa el ==, solo sé que el programa se raya bastante)

**4. La función2() està declarada com segueix:**

> public void funcion2() {  
    System.out.println("--------------------");  
    System.out.println("Aquesta és la funció 2");  
    System.out.println("Com faig la crida perquè funcione????");  
}


**Aquesta funció com l'he de cridar des del mètode MAIN perquè funcione. Existeixen 2
possibilitats. Explica-les.**

La primera opción que se me ocurre para llamar a funcion2() sería simplemete añadiendo deltro del main la siguiente línea de código:

funcion2();

He buscado por internet y no veo otra forma de llamar a la función. Supongo que será almacenandola en alguna variable del main, pero de momento no tengo ni idea.

