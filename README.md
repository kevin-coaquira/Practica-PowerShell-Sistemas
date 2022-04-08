# Practica PowerShell Sistemas
## 1.ps1
![image](https://user-images.githubusercontent.com/91737963/162325584-3d92752e-1f29-4c17-a3c0-500c51d8800d.png)

Almacena el numero 1 en la variable $number
Seguido esto Write-Host saca por pantalla la informacion que almacenamos en $number, también se le añade "The number is:" y sale 
### The number is: 1
Y así sucessivamente en todo 1.ps1

## 2.ps1
![image](https://user-images.githubusercontent.com/91737963/162325846-f923fc3d-fa23-4ec7-bfdd-875d8d650749.png)

-Lo primero que hace es sacar por pantalla "hello" 5 veces ya que [int]$repeat = 5 y esta dentro de un bucle con "for" y hasta que $counter = 0.

-Lo siguiente que se usa con "while" es el mismo resultado que con el "for". Simplemente que aqui dice que repita 5 veces y que cuando $counter llegue a 0 que deje de repetir, en cambio en el for se usa $counter++ que hace que $counter=0+1 y asi hasta llegar 5 repeticiones ya que tiene $repeat = 5.

-Lo siguiente que hace con el "do" es hacer que se repita 5 y contador 0 y que salga por pantalla "hello" y tiene $counter++ para que repita desde 0 hasta llegar 5 veces. El resultado es el mismo que los anteriores.

-En el siguiente declara la variable $stringOfCharacters que tiene "PowerShell for Beginners", y con "foreach" hace que lea letra por letra dentro de este declara $character lo que hace es meter lo que esta en la variable $stringOfCharacters y sucesivamente con "toCharArray()" lo que hace es convertir una matriz de cadenas de caracteres.

-Y por ultimo define una variable [string]$stringOfCharacter que tiene "PowerShell for Begginners", sucesivamente con "ToCharArray()" convierte una matriz de cadenas y con el "ForEach-Object" hace la funcion anterior que es imprimir letra por letra y para imprimir usa "Write-Host "$_" ".

![image](https://user-images.githubusercontent.com/91737963/162503559-5e2c6a6f-5037-42f6-929b-d44bdf5ea025.png)

## 3.ps1
![image](https://user-images.githubusercontent.com/91737963/162326754-2b7ccdd4-55bc-4613-9a3a-1f7e8e0007a0.png)
![image](https://user-images.githubusercontent.com/91737963/162326910-9bc6067c-3221-4968-8537-3311e98aa91a.png)

-Lo primero que hace es una condicional con "if" en la que dice si 4 = 4 que por pantalla salga "4 is equal to 4".

-Lo segundo es otra conficional "if", que hace basicamente lo mismo pero en esta es un string y en el anterior era un integer. Aqui por pantalla aparecera "Both string are equal to each other".

-Lo tercero que hace es aparte crear 2 variable en este caso X, Y que pone el mismo valor a los dos. En la que luego hay una condicional "if" en la que dice si X que es 10 es igual a Y que es 10 que imprima por pantalla "the x and y variable are equal to each other" mediante Write-Host. Y que si X y Y no son lo mismo que salga por pantalla "The x and y variables are NOT equal to each other".

-Lo cuarto define una variable que es $yourName en la que tendra dentro "Ian". Despues coloca otra condicional con "if" y dice que si la variable $yourName es igual a "Ian" que imprima por pantalla "Hay my name is Ian too!" y sino es igual que imprima "Hi $yourName, nice to meet you!".

-Lo quinto es [string]$playerInput = "" lo cual hace que el usuario escriba lo que le pida. En este caso saldra "You walk into a room with two doorways. One to the left and one to the right. Type 'left' or 'Right' to walk through one of the doors.", dependiendo de lo que escriba tomara uno o otro, en este caso si escogiera "left" saldria por pantalla "Played typed left" y si escogiera "right" saldria por pantalla "Played typed right" y si no escoge ninguno de lo anterior saldria por pantalla "Player typed something we didn't understand".

## COMPARISON OPERATORS

-El primero dice que si 5 es igual a 5 se ejecutara la sentencia.

-El segundo dice que si 3 no es igual a 4 se ejecutara la sentencia.

-El tercero dice que si 4 es mayor que 2 se ejecutara la sentencia.

-El cuarto dice que si 2 es mayor o igual que 2 se ejecutara la sentencia.

-El quinto dice que si 1 es menor que 2 se ejecutara la sentencia.

-El sexto dice que si 1 es menor o igual a 2 se ejecutara la sentencia.

## NEXT

-El primero dice que si "hello how are you?" contiene al principio "hello*" que se ejecute la sentencia.

-El segundo dice que si "HELLO" no contiene al principio "BYE" que se ejecute la sentencia.

-El tercero dice que si "HELLO" contiene "H" que se ejecute la sentencia en la que saldra "HELLO"

-El cuarto dice que si "HELLO" no contiene "A" que se ejecute la sentencia en este caso saldra por pantalla "HELLO".

-El quinto dice que si dentro la lista definida contiene el numero 3 que se ejecute la sentencia.

-EL sexto dice que si dentro de lista no contiene el numero 8 que se ejecute la sentencia.

-El septimo dice que si 3 esta dentro de la lista que se ejecute la sentencia.

-El octavo dice que si 6 no esta dentro de la lista que se ejecute la sentencia.

-El noveno dice que si $var  es un "[string]" que se ejecute la sentencia.

-El decimo dice que si $var no es un booleano que se ejecute la sentencia.

## Switch

-El primero dice que si la variable definida dentro de $number es igual a 2 se ejecutara la opción 2 que es "The number is two" y si fuese 1 ejecutaria "The number is one" y sino fuese ninguno de los 2 se ejecutaria la sentencia "default" que diria "I don't know what the number is".

-El segundo dice que si la variable definida dentro de $favouriteColour es igual a blue se ejecute por pantalla "Your favourite colour is Blue""I like Blue too" y sino fuese red dentro de esta variable definida se ejecutaria "Your favourite colour is Red""I like red too.". Y si ninguno de estos estuviera definido en la variable ejecutaria el "default" que en este caso se ejecutaria por pantalla "I don't recognise that colour".
