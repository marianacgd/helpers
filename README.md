# HELPERS
Ajuda com as linguagens. Preparação de ambiente, criação de proejto, comandos e dicas.

## JAVASCRIPT


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

   ## Lista

   `List<int> valores = new List<int>();`

   `List<int> valores = new List<int>(2);`

   `List<int> valores = new List<int>(); valores.Add(1); valores.Add(2);`

   //Declaração = `List<int> valores`

   //Criando Instância = `valores = new List<int>();`

   //Atribuição = `valores.Add(1); valores.Add(2);`

   Representa uma lista fortemente tipada de objetos que podem ser acessados por índice. 
   
   Fornece métodos para pesquisar, classificar e manipular listas.
 
   -Fortemente tipada
   
   -Utiliza Classe List 
   
   -Namespace: System.Collections.Generic
   
   -Acesso pelo índice
   
   -Redimensionamento dinâmico 
   
   -Eficiente

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

   ## Listas - Métodos

   Add / AddRange

   Remove / RemoveAt / RemoveAll

   ElementAt

   Insert

   Count

   Clear

   Contains