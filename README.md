# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.
Os conteudos que aprendemos foram array, number  , boolean , string, operadores logicos e etc .


## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
foram desenvolver jogos , aprender a mexer com codigos , trabalhar com codigos e etc.
O que é uma String?
Por definição, strings são sequências de caracteres alfanuméricos (letras, números e/ou símbolos) amplamente usadas em programação. Em Javascript, uma string sempre estará entre aspas.

const frase = "Mergulhando em tecnologia com Alura";

const frase = ‘Mergulhando em tecnologia com Alura’;


Números JavaScript
JavaScript tem apenas um tipo de número. Números podem ser escritos com ou sem decimais.

Ao contrário de muitas outras linguagens de programação, JavaScript não define diferentes tipos de números, como inteiros, curtos, longos, ponto flutuante etc.

Os números JavaScript são sempre armazenados como números de ponto flutuante de precisão dupla, seguindo o padrão internacional IEEE 754.

Este formato armazena números em 64 bits, onde o número (a fração) é armazenado nos bits 0 a 51, o expoente nos bits 52 a 62 e o sinal no bit 63:


Os números inteiros (números sem ponto ou notação de expoente) são precisos até 15 dígitos.

Exemplo
let x = 999999999999999;   // x will be 999999999999999
let y = 9999999999999999;  // y will be 10000000000000000


Booleanos

Um booleano JavaScript representa um de dois valores: true ou false .


Valores Booleanos
Muitas vezes, na programação, você precisará de um tipo de dado que só pode ter um de dois valores, como

SIM / NÃO
LIGADO / DESLIGADO
VERDADEIRO / FALSO
Para isso, JavaScript tem um tipo de dado Boolean . Ele só pode receber os valores true ou false .


A função Boolean()
Você pode usar a Boolean()função para descobrir se uma expressão (ou uma variável) é verdadeira:

Exemplo
Boolean(10 > 9) 


Os operadores lógicos são elementos fundamentais da linguagem de programação JavaScript. Eles permitem realizar operações de comparação e combinação de valores booleanos, ou seja, valores que podem ser verdadeiros (true) ou falsos (false).



Operadores de comparação
Operadores de comparação são usados ​​em instruções lógicas para determinar igualdade ou diferença entre variáveis ​​ou valores.

Dado que x = 5, a tabela abaixo explica os operadores de comparação:


Como pode ser usado
Operadores de comparação podem ser usados ​​em instruções condicionais para comparar valores e tomar medidas dependendo do resultado:

if (age < 18) text = "Too young to buy alcohol";



JavaScript if, else e else if


Instruções condicionais são usadas para executar diferentes ações com base em diferentes condições.


Declarações condicionais
Muitas vezes, quando você escreve código, você quer executar ações diferentes para decisões diferentes.

Você pode usar instruções condicionais em seu código para fazer isso.

Em JavaScript temos as seguintes instruções condicionais:

Use if para especificar um bloco de código a ser executado, se uma condição especificada for verdadeira
Use else para especificar um bloco de código a ser executado, se a mesma condição for falsa
Use else if para especificar uma nova condição a ser testada, se a primeira condição for falsa
Use switch para especificar muitos blocos alternativos de código a serem executados



A declaração if
Use a ifinstrução para especificar um bloco de código JavaScript a ser executado se uma condição for verdadeira.

Sintaxe
if (condition) {
  //  block of code to be executed if the condition is true
}



Métodos básicos de array
Comprimento do array
Array toString ()
Array at()
Array join()
Array pop()
Array push()


Comprimento do array JavaScript
A lengthpropriedade retorna o comprimento (tamanho) de uma matriz:

Exemplo
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let size = fruits.length;



Funções JavaScript


Uma função JavaScript é um bloco de código projetado para executar uma tarefa específica.

Uma função JavaScript é executada quando "algo" a invoca (a chama).


Exemplo
// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}

Link de sequência de caracteres JavaScript()


Exemplo
let text = "Free Web Building Tutorials!";
let result = text.link("https://www.w3schools.com");

















