# Practica PowerShell Sistemas
## 1.ps1
![image](https://user-images.githubusercontent.com/91737963/162325584-3d92752e-1f29-4c17-a3c0-500c51d8800d.png)

Almacena el numero 1 en la variable $number
Seguido esto Write-Host saca por pantalla la informacion que almacenamos en $number, también se le añade "The number is:" y sale 
### The number is: 1
Y así sucessivamente en todo 1.ps1

## 2.ps1
![image](https://user-images.githubusercontent.com/91737963/162325846-f923fc3d-fa23-4ec7-bfdd-875d8d650749.png)

-Lo primero que hace es sacar por pantalla "hello" 5 veces ya que [int]$repeat = 5 y esta dentro de un bucle con "for" y hasta que $counter = 0
-Lo siguiente que se usa con "while" es el mismo resultado que con el "for". Simplemente que aqui dice que repita 5 veces y que cuando $counter llegue a 0 que deje de repetir, en cambio en el for se usa $counter++ que hace que $counter=0+1 y asi hasta llegar 5 repeticiones ya que tiene $repeat = 5
-Lo siguiente que hace con el "do" es hacer que se repita 5 y contador 0 y que salga por pantalla "hello" y tiene $counter++ para que repita desde 0 hasta llegar 5 veces. El resultado es el mismo que los anteriores.
-En el siguiente declara la variable $stringOfCharacters que tiene "PowerShell for Beginners", y con "foreach" hace que lea letra por letra dentro de este declara $character lo que hace es meter lo que esta en la variable $stringOfCharacters y sucesivamente con "toCharArray()" lo que hace es convertir una matriz de cadenas de caracteres.
-Y por ultimo define una variable [string]$stringOfCharacter que tiene "PowerShell for Begginners", sucesivamente con "ToCharArray()" convierte una matriz de cadenas y con el "ForEach-Object" hace la funcion anterior que es imprimir letra por letra y para imprimir usa "Write-Host "$_" "
![image](https://user-images.githubusercontent.com/91737963/162503559-5e2c6a6f-5037-42f6-929b-d44bdf5ea025.png)

## 3.ps1
![image](https://user-images.githubusercontent.com/91737963/162326754-2b7ccdd4-55bc-4613-9a3a-1f7e8e0007a0.png)
![image](https://user-images.githubusercontent.com/91737963/162326910-9bc6067c-3221-4968-8537-3311e98aa91a.png)
