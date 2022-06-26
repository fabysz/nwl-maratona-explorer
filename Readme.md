<h3>Participei da "Maratona Explorer" com a Rocketseat para estudar mais os conceitos de HTML, CSS e Javascript. 
Neste laboratório consegui compreender melhor o que são variáveis e como aplicá-las. </h3>
<h4>Nota: Deixo salvo no github para fins de pesquisas futuras.</h4>
  
![Screenshot_1](https://user-images.githubusercontent.com/67671454/175816242-64e98786-8262-4dc0-aef5-0f5f1ce54f61.png) 

  ![Desktop-2022 06 25---22 04](https://user-images.githubusercontent.com/67671454/175816260-aa5878a7-2112-416d-9315-2cf1e3038930.gif)

# HTML
- HyperText Markup Language

- Hiper Texto?
- Marcação
  - tags
  - atributos
- Linguagem
  - maneira de escrever

# CSS

- Apresentação visual para o cliente
- Estilos para o HTML
- Cascading Style Sheets
  - Folha de Estilo em Cascata

# Declaração
- Seletor
- Propriedade e Valor

# Conceitos
- Cascata
- Especificidade
- Box Model
- Display block vs inline



### imagem bola de cristal
https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg


# Javascript #

O que é?

* Linguagem de programação 

    -Interpretada e executada pelos navegadores

* A inteligência da tríade
    - HTML é a estrutura, CSS é beleza e o JS é a inteligência

* Não é JAVA
    - Apesar do nome ser semelhante, são linguagem diferentes



Por que JS?

* Aplicativos  
    - Para WEB, Desktop(Eletron) e Mobile(React Native)

* Empresas Famosas
 - Instagram, Google, Netflix, TikTok

 * Moderna e Viva
    - Comunidade e lingauem que cresce cada vez mais


## Sintaxe ##

É presente em toda linguagem e é importante para a comunicação

exemplo: 

const mensagem = "Bom te ver aqui!"
alert(mensagem + (10 * 100) + "Abraços)
// Bom te ver aqui! 1000 Abraços

# Executando Javascript #

* De mandeira imediata 
-> No Browser a partir da ferramenta DevTools aperando o atalho F12 no seu teclado
-> Plataformas online (codepen.io, fronteditor.dev)

* Arquivos no computador(exemplo abaixo)

<!-- em um arquivo index.html -->

<!-- executa o javascript direto no .html -->
<script> alert('Olá')</script>

<!-- importa um arquivo .js no seu .html -->
<script src="./script.js"></script>


```js
// 1. Variáveis
// let estaChovendo = true
// const meuNome = "Fabiana"

## Nota sobre Variável ##

Na programação, uma variável é um objeto (uma posição, frequentemente localizada na memória) capaz de reter e representar um valor ou expressão. Enquanto as variáveis só "existem" em tempo de execução, elas são associadas a "nomes", chamados identificadores, durante o tempo de desenvolvimento. Quando nos referimos à variável, do ponto de vista da programação de computadores, estamos tratando de uma “região de memória (do computador) previamente identificada cuja finalidade é armazenar os dados ou informações de um programa por um determinado espaço de tempo” A memória do computador se organiza tal qual um armário com várias divisões. Sendo cada divisão identificada por um endereço diferente em uma linguagem que o computador entende.

O computador armazena os dados nessas divisões, sendo que em cada divisão só é possível armazenar um dado e toda vez que o computador armazenar um dado em uma dessas divisões, o dado que antes estava armazenado é eliminado. O conteúdo pode ser alterado, mas somente um dado por vez pode ser armazenado naquela divisão. O computador identifica cada divisão por intermédio de um endereço no formato hexadecimal, e as linguagens de programação permitem nomear cada endereço ou posição de memória, facilitando a referência a um endereço de memória. Uma variável é composta por dois elementos básicos: o conteúdo,o valor da variável e identificador, um nome dado à variável para possibilitar sua utilização.

Exemplo de uma variável com JavaScript:

// Variável que contém um dado do tipo "string"

var exemplo = 'Isso é um exemplo de uma variável com nome "exemplo".';
exemplo = 'Agora a variável "exemplo" tem novo valor.';
Classificação de variáveis
Variáveis globais - são aquelas declaradas fora do escopo das funções
Variáveis locais - são aquelas declaradas no inicio do bloco e seus escopos são restritos aos blocos em que foram declaradas
Nomenclatura
Para padrões de nomenclatura veja:

Notação húngara
CamelCase
123 

* let *
Declara uma variável local no escopo do bloco atual, opcionalmente iniciando-a com um valor.
let permite que você declare variáveis limitando seu escopo no bloco, instrução, ou em uma expressão na qual ela é usada. Isso é inverso da keyword var, que define uma variável globalmente ou no escopo inteiro de uma função, independentemente do escopo de bloco.

* Escopo de bloco *
Variáveis declaradas com let são "içadas" para começo do bloco em que elas são definidas (isso é conhecido também pelo termo, hoisting).

Redeclaração de uma mesma variável num mesmo escopo de bloco causa um TypeError.

if (x) {
  let foo;
  let foo; // Emite um TypeError.
}

No entanto, corpos de funções não possuem essa limitação!

function do_something() {
  let foo;
  let foo; // Isso funciona.
}

* const *
Constantes têm escopo de bloco, bem como variáveis ​​declaradas usando a palavra- let chave. O valor de uma constante não pode ser alterado por meio de reatribuição (ou seja, usando o operador de atribuição ) e não pode ser redeclarado (ou seja, por meio de uma declaração de variável ). No entanto, se uma constante for um objeto ou array , suas propriedades ou itens podem ser atualizados ou removidos.

Esta declaração cria uma constante cujo escopo pode ser global ou local ao bloco no qual ela é declarada. As constantes globais não se tornam propriedades do windowobjeto, ao contrário das varvariáveis.

É necessário um inicializador para uma constante. Você deve especificar seu valor na mesma declaração. (Isso faz sentido, já que não pode ser alterado posteriormente.)

A constdeclaração cria uma referência somente leitura para um valor. Isso não significa que o valor que ele contém seja imutável - apenas que o identificador da variável não pode ser reatribuído. Por exemplo, no caso em que o conteúdo é um objeto, isso significa que o conteúdo do objeto (por exemplo, suas propriedades) pode ser alterado.

Todas as considerações sobre a zona morta temporal se aplicam a lete const.

Uma constante não pode compartilhar seu nome com uma função ou variável no mesmo escopo.

Ao contrário varde, constcomeça Declarações , não Declarações . Isso significa que você não pode usar uma declaração solitária constcomo o corpo de um bloco (o que faz sentido, já que não há como acessar a variável).



// 2. Tipos de Dados 
  // String
  // ""
  // ''
  
  // Number
  // 12 - Integer (+ -)
  // 3.2 - Float (+ - )

  // Boolean
  // true ou false
  // const maiorDeDezoito = false

  // undefined - indefinido


// 3. Operadores
  // Atribuição (ex: =)
  // atribui valor
  // let n1 = 12
  // let n2 = 3 

  // Aritméticos (ex: * / + - )
  // calculos matemáticos simples

  // Concatenação de String (+)

  // Comparação (ex: > < == )
  // transforma a expressão em true ou false
  // const maiorQue = 1 > 2 // false
  // const igualA = 1 == 1 // true

// 4. Condicional (if/else)
  // const idade = 18
  // const maiorDeDezoito = idade >= 18 

  // if(maiorDeDezoito) {
  //   alert("Pode tirar carteira de motorista")
  // } else {
  //   alert("Não pode tirar")
  // }

// 5. Estrutura de dados
  // Array - Vetor - Lista
  // Array -----         0     1    2  3
  // const temperaturas = [23.3, 32.2, 1, 5]

  // Object
  // const pessoa = {
  //   nome: "Mayk",
  //   idade: 38,
  //   filhos: ["K", "E", "J", "L", "G"]
  // }
  // console.log(pessoa.filhos[3])

// 6. Function
  // 1. Criação 
  // function nomeDaFuncao() {
  //   console.log('código da função')
  // }

  // 2. Execução
  // nomeDaFuncao()


  // Parâmetros
  // function soma(a, b) {
  //   console.log(a + b)
  // }
  // soma(34, 45)
  // soma(90, 54)

  // Retorno
  // function soma(a, b) {
  //   return a + b
  // }

  // const multiplica = soma(2, 2) * 4
  // console.log(multiplica)

  // console.log(soma(2, 2))


// 7. Extensões da linguagem (ex.: Math, Date ...)

// Math.random()
// Math.floor(1.2)
// Math.ceil(1.2)

// 8. DOM - Document Object Model 
  
  // window
  // window.alert("alerta")
  // document
  // document.write("texto")
  // manipular elementos
  // document.documentElement.style.background = "black"
```

