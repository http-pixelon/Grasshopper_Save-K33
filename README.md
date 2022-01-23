# Grasshopper_Save-K33
:speech_balloon: Me adicione no Discord: [`! Pixelon#2947`](https://discord.com/users/230834721372766208)
<h3 align="left">Meu progresso no Grasshopper</h3>


<li> Variaveis/Funções:
  
  1- `drawBox()`
  
  > Cria um quadrado com base na cor entre parênteses. Por exemplo, drawBox(red) desenha um quadrado vermelho.

CÓDIGO DE EXEMPLO:
  
 
```js
drawBox(blue); //Esse código desenhará um quadrado azul.
```
  
  ##
  
  2- `newLine()`
  
  > Move o cursor, o pequeno gafanhoto, para a próxima linha. Geralmente é útil ao criar quadrados com drawBox().
  

CÓDIGO DE EXEMPLO:
  
```js
drawBox(blue);
newLine();
drawBox(blue);
  //Esse código desenhará um quadrado azul, se moverá para a próxima linha e, em seguida, desenhará outro quadrado azul.
```
  ##
  
  3- `pickRandom()`
  
  CÓDIGO DE EXEMPLO:
  
 
  > Escolhe uma cor aleatória, item de uma array ou número.
  

CÓDIGO DE EXEMPLO:
  
 
  ```js
  var arrayOfColors = ['blue', 'orange'];
var randomColor = pickRandom(arrayOfColors); //randomColor será 'blue' ou 'orange'.
  ```
  
  ##
  
  4- `str`
  
  > Letras, palavras e frases são chamadas de strings na programação. As aspas são usadas para mostrar o início e o fim de uma string. Por exemplo, 'hello world' é uma string..
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  drawBoxes('royg');
  // 'royg' é uma string usada na função drawBoxes() para criar caixas vermelhas, laranja, amarelas e verdes.
  ```

  ##
  
  5- `boolean`
  
  > Um boolean é um dos dois valores especiais em JavaScript, true ou false. Eles são úteis para lidar com estados que possuem apenas duas possibilidades.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  var isLearningToCode = true; var shouldWearSocksWithSandals = false;
  // É true que você está aprendendo a programar, mas é false que se deva usar meias com sandálias.
  ```
  
  ##
  
  6- `var`
  
  > Uma forma de armazenar um valor para uso posterior, também conhecido como variável. Uma var deve ter um nome (também conhecido como identificador) e, opcionalmente, pode ser atribuído um valor, que pode ser um número, uma string ou um dado mais complexo.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  var cityOfOrigin = 'Pittsburgh';
var cityOfDestination;
cityOfDestination = 'Manila';
  // cityOfOrigin é uma variável que será igual a 'Pittsburgh'. Em seguida, outra variável chamada cityOfDestination é criada e mais tarde recebe um novo valor de 'Manila'.
  ```
  
  ##
  
  7- `print()`
  
  > Pega o que está entre parênteses e exibe. Por exemplo, `print('xanagem')` exibiria o texto 'xanagem'.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  print('Hello, Pixelworld!')
  // O texto 'Hello, Pixelworld!' será impresso.
  ```
  
  ##
  
  8- `Encadeamento`
  
  > O encadeamento permite que os programadores apliquem várias chamadas de função diferentes ao mesmo identificador.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  svg​.append('circle')
    ​.attr('fill', 'blue')
    ​.attr('r', 200);
  // Um círculo SVG é criado com um atributo de azul para seu preenchimento e um raio de 200 aplicado ao mesmo tempo usando .append() e duas chamadas de função .attr() encadeadas.
  ```
  
  ##
  
  9- `Acessar uma Propriedade`
  
  > Um objeto pode armazenar várias informações dentro de uma variável. A notação de ponto é usada para acessar uma propriedade de um objeto. Por exemplo, `objectName.propertyName.`
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  var objectName = {
    propertyName: 'Codificar é divertido demais vei​.',
    otherPropertyName: 'este também é um valor chave'
};
print(objectName​.propertyName);
  // Este código imprimirá 'Codificar é divertido demais vei.'
  ```
  
  ##
  
   10- `{ }`
  
  > Um objeto armazena vários valores que possuem nomes de propriedade (ou chave). Isso permite que eles sejam facilmente acessados posteriormente no código.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```js
  var groceries = {
    maças: 5,
    bananas: 2
};
  // maças e bananas são propriedades do objeto groceries. 5 e 2 são os valores associados a essas propriedades. groceries.maças, por exemplo, é igual a 5.
  ```
 
  ##
  
  11- `[ ]`
  
  > Em JavaScript, uma array é uma lista de itens. Os itens podem ser diferentes tipos de dados: números, strings e até mesmo outras arrays. Uma array dentro de outra array é chamada de aninhamento de arrays.
  
  > Indexação da array começa em 0. Por exemplo, myArray[0] vincula-se ao 1º item na array denominada myArray. Enquanto myArray[1] se vincula ao 2º item.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```var exampleArray = ['blue', 'orange', 5, 10, [50, 10]];
  // exampleArray tem 5 itens. Ela contém strings, números e uma array; que tem dois itens que são números.
  ```
 
  ##
  
    12- `=`
  
  > "Define (ou redefine)" o valor armazenado em uma variável. À esquerda está a variável que você gostaria de ajustar e à direita está o novo valor.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```var myNumber = 10;
  // myNumber será igual a 10.
  ```
 
  ##
  
      13- `*=`
  
  > "Multiplica" o valor associado à variável à esquerda pelo valor à direita e atribui o valor resultante à variável existente.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```var myNumber = 10;
myNumber *= 5;
  // myNumber será igual a 50.
  ```
 
  ##
  
      14- `+=`
  
  > "Adiciona" o valor associado à variável à esquerda com o valor à direita e atribui o valor resultante à variável existente.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```var myNumber = 10;
myNumber += 5;
  // myNumber será igual a 15.
  ```
 
  ##
  
      15- `/=`
  
  > "Divide" o valor associado à variável à esquerda pelo valor à direita e atribui o valor resultante à variável existente.
  
  CÓDIGO DE EXEMPLO:
  
 
  ```var myNumber = 10;
myNumber /= 5;
  // myNumber será igual a 2.
  ```
 
  ##
  
  
  <details>
 <summary><b> Clique aqui para ver o meu Progresso-Grass 💡 </b></summary>

    Um simples progresso de Pixelon.
    No final irei explicar cada coisa
    
  | Partes Grass  | Status |
| ------------- | ------------- |
| drawBox()  | ✅  |
| newLine()  | ✅  |
|   |   |

</details>
  
  ~Farm K33:
  
  301010101013+
