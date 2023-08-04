# HELPERS
Ajuda com as linguagens. Preparação de ambiente, criação de proejto, comandos e dicas.

## JAVASCRIPT

## 📄**Comandos** 

 <table>
   <tr>
   <td>Comando</td>
   <td>Função</td>
   </tr>
   <tr>
   <td>json-server db.json</td>
   <td> Inicia um servidor JSON de desenvolvimento que pode ser usado para simular uma API RESTful com base no conteúdo do arquivo, permitindo que você crie endpoints com dados fictícios.</td>
   </tr>
   <tr>
   <td>ng serve</td>
   <td>Executa o servidor de desenvolvimento do Angular. Para visualizar seu aplicativo em um navegador, onde ele interage com a API simulada para obter e exibir dados.</td>
   </tr>
   </table>


Métodos de Array:

Array.push() : Adiciona um ou mais elementos ao final de uma matriz e retorna o novo comprimento da matriz.

Array.pop() : Remove o último elemento de uma matriz e retorna esse elemento.

Array.unshift() : Adiciona um ou mais elementos ao início de um array e retorna o novo comprimento do array.

Array.shift() : Remove o primeiro elemento de uma matriz e retorna esse elemento.

Array.concat() : Une dois ou mais arrays e retorna um novo array.

Array.slice() : Extrai uma parte de um array em um novo array sem modificar o array original.

Array.splice() : Adiciona ou remove elementos de uma matriz em um índice específico.

Array.join() : Une todos os elementos de um array em uma string.

Array.indexOf() : Retorna o primeiro índice no qual um determinado elemento pode ser encontrado na matriz.

Array.includes() : Determina se uma matriz inclui um determinado valor.

Array.filter() : Cria um novo array com elementos que passam no teste de uma função fornecida.

Array.map() : Cria uma nova matriz aplicando uma função a cada elemento da matriz original.

Array.flatMap() : cria um novo array chamando uma função para cada elemento do array.

Array.reduce() : Reduz um array a um único valor executando uma função fornecida para cada elemento.

Array.sort() : Classifica os elementos de uma matriz no local e retorna a matriz classificada.

Array.reverse() : Inverte a ordem dos elementos em um array no lugar.

Array.forEach() : Executa uma função fornecida uma vez para cada elemento do array.

Array.every() : executa uma função para cada elemento do array. retorna true se a função retornar true para todos os elementos. 
retorna false se a função retorna false para um elemento.

Array.find() : retorna o valor do primeiro elemento que passa no teste.

Array.findIndex() : retorna o índice (posição) do primeiro elemento que passa no teste.

Array.at() :  retorna um elemento indexado de uma matriz.

Array.entries() : retorna um objeto Array Iterator com pares chave/valor:



Métodos de Objeto:

Object.keys() : Retorna uma matriz dos nomes de propriedades enumeráveis ​​de um determinado objeto.

Object.values() : Retorna uma matriz dos próprios valores de propriedade enumeráveis ​​de um determinado objeto.

Object.entries() : Retorna uma matriz dos próprios pares de valor-chave enumeráveis ​​de um determinado objeto.

Object.assign() : Copia os valores de todas as propriedades enumeráveis ​​de um ou mais objetos de origem para um objeto de destino.

Object.hasOwnProperty() : Retorna um booleano indicando se um objeto tem a propriedade especificada como uma propriedade direta.

Object.freeze() : Congela um objeto, impedindo que novas propriedades sejam adicionadas e propriedades existentes sejam removidas ou 
modificadas.

Object.seal() : Sela um objeto, impedindo que novas propriedades sejam adicionadas e marcando todas as propriedades existentes como 
não configuráveis.

Object.getPrototypeOf() : Retorna o protótipo de um objeto.

Object.setPrototypeOf() : Define o protótipo (isto é, a propriedade interna [[Prototype]]) de um objeto.


## CSHARP

## ⚙️Ambiente 

Kit de Desenvolvimento de Software (SDK) do .NET: 
https://dotnet.microsoft.com/en-us/download

VS Code - Visual Studio Code: https://code.visualstudio.com/

OU 

Visual Studio: https://visualstudio.microsoft.com/pt-br/downloads/

Extensões para .NET, colocar na busca das extensões do VS

C# (Oficial da Microsoft, mais baixada/avaliada)

.NET (Oficial da Microsoft, mais baixada/avaliada)

## Criando meu projeto C# no VS Code
No prompt, e execute o comando: `dotnet new console -o meuPrimeirPrograma`

Deu erro? Apareceu a mensagem de “It was not possible to find any installed .NET Core SDKs”? Não se preocupe, isso pode acontecer em alguns computadores que provavelmente não possuem o .Net instalado. Faça o download em https://download.visualstudio.microsoft.com/download/pr/5aad9c2c-7bb6-45b1-97e7-98f12cb5b63b/6f6d7944c81b043bdb9a7241529a5504/dotnet-sdk-3.1.102-win-x64.exe

Prossiga com a instalação.

Tente novamente executar o comando `dotnet new console -o meuPrimeirPrograma`

## Executando a aplicação C#
Para executar seu projeto, retorne ao prompt de comando, acesse a pasta do seu projeto e em seguida execute o comando `dotnet run`

## Material de Apoio
Documentação .NET CLI https://docs.microsoft.com/pt-br/dotnet/core/tools/

A CLI (interface de linha de comando) do .NET é uma ferramenta multiplataforma para desenvolvimento, criação, execução e publicação de aplicativos .NET. A CLI do .NET está incluída no .NET SDK.

`dotnet` - O driver genérico para a CLI do .NET.

## 📄**Comandos**  
  
   <table>
   <tr>
   <td>Comando</td>
   <td>Função</td>
   </tr>
   <tr>
   <td>dotnet new</td>
   <td>Inicializa um projeto do C# ou F# de um modelo especificado.</td>
   </tr>
   <tr>
   <td>dotnet run</td>
   <td>Executa o aplicativo na origem.</td>
   </tr>
   <tr>
   <td>dotnet build</td>
   <td>	Cria um aplicativo .NET.</td>
   </tr>
   </table>

   ## 📄**Tipos de Dados**  
  
   1) Tipos numéricos inteiros
   Representa numeros inteiros, sem parte fracionária. Os que iniciam com o u ("unsigned") não aceitam valores negativos.
   <table>
   <tr>
   <td>Tipo</td>
   <td>Tamanho</td>
   <td>Faixa de valores</td>
   </tr>
   <tr>
   <td>byte</td>
   <td>8 bits</td>
   <td>0 a 255</td> 
   </tr>
   <tr>
   <td>sbyte</td>
   <td>8 bits</td>
   <td>-128 a 127</td> 
   </tr>
   <tr>
   <td>short</td>
   <td>16 bits</td>
   <td>-32.768 a 32.767</td> 
   </tr>
   <tr>
   <td>ushort</td>
   <td>16 bits</td>
   <td>0 a 65.535</td> 
   </tr>
   <tr>
   <td>int</td>
   <td>32 bits</td>
   <td>-2.147.483.648 a 2.147.483.647</td> 
   </tr>
   <tr>
   <td>uint</td>
   <td>32 bits</td>
   <td>0 a 4.294.967.295</td> 
   </tr>
   <tr>
   <td>long</td>
   <td>64 bits</td>
   <td>-9.223.372.036.854.775.808 a 9.223.372.036.854.775.807</td> 
   </tr>
   <tr>
   <td>ulong</td>
   <td>64 bits</td>
   <td>0 a 18.446.744.073.709.551.615</td> 
   </tr>
   </table>

   2) Tipos numéricos de ponto flutuante
   Representam numeros "reais", que possuem parte fracionária.
   <table>
   <tr>
   <td>Tipo</td>
   <td>Tamanho</td>
   <td>Precisão</td>
   </tr>
   <tr>
   <td>float</td>
   <td>4 byts</td>
   <td>~6 a 9 dígitos</td> 
   </tr>
   <tr>
   <td>double</td>
   <td>8 byts</td>
   <td>~15 a 17 dígitos</td> 
   </tr>
   <tr>
   <td>decimal</td>
   <td>16 byts</td>
   <td>28 a 29 dígitos</td> 
   </tr>
   </table>

   3) Tipo booleano
   Usado para armazenar valores que podem ser representados como Verdadeiro ou Falso.
   <table>
   <tr>
   <td>Tipo</td>
   <td>Tamanho</td>
   <td>Faixa de valores</td>
   </tr>
   <tr>
   <td>bool</td>
   <td>1 bit</td>
   <td>true ou false</td> 
   </tr>
   </table>

   4) Tipos textuais
   Usado para armazenar textos.
   <table>
   <tr>
   <td>Tipo</td>
   <td>Tamanho</td>
   <td>Faixa de valores</td>
   </tr>
   <tr>
   <td>char</td>
   <td>2 bytes</td>
   <td>Um caractere</td> 
   </tr>
   <tr>
   <td>string</td>
   <td>2 bytes por caractere</td>
   <td>Textos</td> 
   </tr>
   </table>

   ## 📄**Operadores Aritméticos**  

   <table>
   <tr>
   <td>Sinal</td>
   <td>Operação</td>
   </tr>
   <tr>
   <td>+</td>
   <td>Soma</td>
   </tr>
   <tr>
   <td>-</td>
   <td>Subtração</td>
   </tr>
   <tr>
   <td>*</td>
   <td>Multiplicação</td>
   </tr>
   <tr>
   <td>/</td>
   <td>Divisão</td>
   </tr>
   <tr>
   <td>%</td>
   <td>Resto</td>
   </tr>
   <tr>
   <td>=</td>
   <td>Atribuição</td>
   </tr>
   <tr>
   <td>==</td>
   <td>Comparação</td>
   </tr>
   </table>
   
   Para algoritmos que possuam cálculos matemáticos: 
   Todas as expressões precisam estar linearizadas, ou seja, em uma “única linha”;

   Precedências, da maior para a menor:
   
   1 - Parênteses;
   
   2 - Expoentes;
   
   3 - Multiplicações e divisões (da esquerda para a direita);
   
   4 - Somas e subtrações (da esquerda para a direita);

   ## 📄**Operadores Relacionais**  

   <table>
   <tr>
   <td>Sinal</td>
   <td>Operação</td>
   </tr>
   <tr>
   <td> > </td>
   <td>Maior que</td>
   </tr>
   <tr>
   <td> < </td>
   <td>Menor que</td>
   </tr>
   <tr>
   <td> >= </td>
   <td>Maior ou igual que</td>
   </tr>
   <tr>
   <td> <= </td>
   <td>Menor ou igual que</td>
   </tr>
   <tr>
   <td> == </td>
   <td>Igual a</td>
   </tr>
   <tr>
   <td> != </td>
   <td>Diferente de</td>
   </tr>
   </table>

   ## 📄**Operadores Lógicos**  

   <table>
   <tr>
   <td>Sinal</td>
   <td>Operação</td>
   <td>Significado</td>
   </tr>
   <tr>
   <td> && </td>
   <td>Conjunção (AND) = E </td>
   <td>Resulta TRUE se ambas as partes forem verdadeiras.</td>
   </tr>
   <tr>
   <td> || </td>
   <td>Disjunção (OR) = OU </td>
   <td>Resulta TRUE se somente uma das partes for verdadeira.</td>
   </tr>
   <tr>
   <td> ! </td>
   <td>Negação (NOT) = NÃO </td>
   <td>Negará uma afirmação, invertendo seu valor lógico: se for true, torna-se false, se for false, torna-se true.</td>
   </tr>

   <table>
   <tr>
   <td>a</td>
   <td>b</td>
   <td>a && b</td>
   <td>a || b</td>
   <td>!a</td>
   <td>!b</td>
   </tr>
   <tr>
   <td>true</td>
   <td>true</td>
   <td>true</td>
   <td>true</td>
   <td>false</td>
   <td>false</td>
   </tr>
   <tr>
   <td>true</td>
   <td>false</td>
   <td>false</td>
   <td>true</td>
   <td>false</td>
   <td>true</td>
   </tr>
   <tr>
   <td>false</td>
   <td>true</td>
   <td>false</td>
   <td>true</td>
   <td>true</td>
   <td>false</td>
   </tr>
   <tr>
   <td>false</td>
   <td>false</td>
   <td>false</td>
   <td>false</td>
   <td>true</td>
   <td>true</td>
   </tr>
   </table>

   ## 📄**Estruturas de Decisão** 

   - Controla o fluxo 
   - De acordo com a condição, podem desviar do fluxo principal. 

   - Estruturas Condicionais:
   
   IF-ELSE: Analisa a expressão e toma uma decisão.
   `if(num > 0) {Console.WriteLine("Numero maior que 0!")} else {Console.WriteLine("Numero menor que 0!")}`
   
   SWITCH-CASE: Analisa o valor e tomar decisão.
   `int number=1; switch(number){case 1: Console.WriteLine("O número é um."); break; case 2: Console.WriteLine("O número é dois."); break;}`

   - Estrutura de Repetição:

   WHILE: Enquanto a condição for verdadeira bloco de código será executado.
   `int i=0; while(i > 5){Console.WriteLine(i); i++; }`

   DO-WHILE: Semelhante ao while, mas garante que as instruções sejam executadas pelo menos uma vez.
   `int i=0; do{Console.WriteLine(i); i++;} while(i > 5);`
   
   FOR: Usado para repetir uma série de instruções especificadas uma quantidade conhecida de vezes. 
   `for(int i = 0; i< 10; i++)`
   (Inicializa a variável ; Expressão booleana ; Incrementa/Decrementa)

   FOREACH: Não precisamos informar a condição de parada
   A repetição vai acontecer de acordo com o tamanho do elemento 
   Executa elementos de uma coleção (Array, List, Stack, Queue)
   `string[] produtos = { "TV", "Notebook", "Tablet", "Celular" }; foreach (string produto in produtos){System.Console.WriteLine("Produto: " + produto);}`

   ## 📄**Listas e Arrays**

   ### Listas

   Representa uma lista fortemente tipada de objetos que podem ser acessados por índice. 
   
   Fornece métodos para pesquisar, classificar e manipular listas.
 
   - Fortemente tipada
   
   - Utiliza Classe List 
   
   - Namespace: System.Collections.Generic
   
   - Acesso pelo índice
   
   - Redimensionamento dinâmico 
   
   - Eficiente

   A Lista possui redimensionamento dinâmico enquanto o array possui um tamanho definido (não podemos alterar o tamanho da posição em tempo de execução).
   
   A Lista possui acervo maior de métodos para manipular coleções. 
   Um único tipo que evita a necessidade de uma análise

   <table>
   <tr>
   <td>Array</td>
   <td>List</td>
   </tr>
   <tr>
   <td>Tamanho fixo</td>
   <td>Sem tamanho fixo</td>
   </tr>
   <tr>
   <td>Redimensionar é "caro"</td>
   <td>Faz a gestão de tamanho</td>
   </tr>
   <tr>
   <td>Dados multidimensionais(matriz)</td>
   <td>Não possui dados multidimensionais "nativo"</td>
   </tr>
   </table>

   Exemplos:

   `List<int> valores = new List<int>();`

   `List<int> valores = new List<int>(2);`

   `List<int> valores = new List<int>(); valores.Add(1); valores.Add(2);`

   `List<int> valores` = //Declaração

   `valores = new List<int>();` = //Criando Instância

   `valores.Add(1); valores.Add(2);` = //Atribuição

   `List<int> valores = new List<int>() {1, 2};`

   ## Listas - Métodos

   Add / AddRange

   Remove / RemoveAt / RemoveAll

   ElementAt

   Insert

   Count

   Clear

   Contains

   ### Arrays

   Arrays são utilizados para armazenar múltiplos valores em uma única variável. 
   Chamamos isso de Variáveis Compostas.    
   No C# esses valores precisam ser de mesmo tipo. 
   Ao nome dado ao Array chamamos de identificador e por ele é possível acessar os valores armazenados. 
   Cada valor recebe um número correspondente a sua posição, chamamos eles de índices. 
   Os índices sempre começam em 0.

   - Armazena conjunto de valores
   
   - Armazena de uma só vez
   
   - Múltiplos valores do mesmo tipo
   
   - “Super variável”
   
   - Memória não é alocada para o array até a criação de uma instância usando o new

   
   Temos algumas formas de declarar uma array. 
   
   A primeira que veremos é a seguinte: 
   
   declaramos o tipo junto com [] (abre e fecha colchetes) recebendo uma instância de um novo array passando o seu tamanho dentro dos colchetes.
   `string[] nomes = new string[3];` onde `new string[3];` = //instância, tipo e tamanho. 

   A segunda que veremos é a seguinte: 
   
   declaramos o tipo junto com [] (abre e fecha colchetes) recebendo uma sequência de dados do tipo declarado dentro de {} (abre e fecha chaves). Cada valor deve ser separado por vírgula. A essa forma damos o nome de declaração por inferência. Nesse caso o tamanho do array é definido pelo número de elementos adicionados.

   `string[] nomes = {"Maria", "João", "Paulo"};` onde `{"Maria", "João", "Paulo"};` = valores adicionados no momento da instanciação.

   Importante: o tamanho de um array é fixo. Ao declarar um tamanho não é possível adicionar valores dinamicamente.

   ### Arrays básicos

   O array é um tipo complexo derivado do System.Array. Existem formas diferentes de criamos uma variável com uma lista de dados, mas iremos iniciar nosso estudo pela seguinte sintaxe:

   `string[] listaNomes = new string[5]; listaNomes[0] = "Camila"; listaNomes[1] = "Gabriel"; listaNomes[2] = "Max"; listaNomes[3] = "Dayane"; listaNomes[4] = "Erlon";`

   - Arrays Unidimensionais (Vetores) 
   1 índice para controlar o array
   
   - Arrays Bidimensionais (Matrizes) 
   2 índices para controlar o array 
   + 1 posição de índice

   Exemplos:

   `int[] numerosDaSorte; // Declaração do array numerosDaSorte = new int[3]; // Instanciando numerosDaSorte[0] = 30; numerosDaSorte[1] = 50; numerosDaSorte[2] = 100; // Atribuição` 

   `int[] idades  = new int[5]{ 20, 26, 36, 18, 80 };`

   `string[] cidade = new string[3]{"Campo Grande", "Campinas", "Florianópolis"};`

    
    ## Arrays - Métodos

    Contains()

    Length()

    First()

    FirstOrDefault()

    Concat()

    CopyTo()

    ## Enums

    - Tipo de enumeração
    
    - Conjunto de constantes nomeadas
    
    - Define um tipo personalizado
    
    - Define os valores possíveis

    Exemplos:

    `public enum Days{ None,//0 Monday,//1 Tuesday,//2 Wednesday,//3...}`
    `enum Generos{ Aventura, Romance, Suspense, Terror}`
    `enum Color{ Red, Green, Blue}`

    Tipo de Dados:
    Existem também os tipos de dados Enum e Struct.

    