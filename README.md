# Sistema de Gerenciamento de Heróis

Este é um sistema simples em JavaScript para gerenciar heróis em um jogo de aventura. Ele foi desenvolvido como parte de um desafio da plataforma Digital Innovation One.

## Descrição

O sistema consiste em uma classe `Heroi` que representa um herói em uma aventura. Cada herói possui um nome, idade e tipo (como guerreiro, mago, monge ou ninja). Além disso, há um método `atacar` que determina o tipo de ataque com base no tipo do herói e exibe uma mensagem correspondente.

## Como Usar

Para utilizar o sistema, basta seguir estes passos:

1. Clone o repositório para o seu ambiente local.
2. Abra o arquivo `index.html` em um navegador web.
3. Abra o console do navegador para ver as mensagens de ataque dos heróis.

## Exemplo de Uso

Aqui está um exemplo de como utilizar a classe `Heroi`:

```javascript
// Instanciando um herói
let heroi1 = new Heroi('Aragorn', 30, 'guerreiro');

// Chamando o método atacar
heroi1.atacar();
