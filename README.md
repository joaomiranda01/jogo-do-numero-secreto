# Jogo do Número Secreto

Este é um jogo simples em JavaScript onde o jogador tenta adivinhar um número secreto gerado aleatoriamente. Este projeto é um desafio criado e proposto pela alura, a maior escola online de tecnologia do Brasil, por meio do curso: Lógica de programação: explore funções e listas. 

## Funcionalidades

-   Gera um número secreto aleatório entre 1 e 10 por meio do `Math.random()`.
-   Permite que o jogador insira palpites.
-   Fornece dicas se o palpite é maior ou menor que o número secreto por meio de operadores condicionais `if` `else` etc.
-   Exibe o número de tentativas após o jogador acertar.
-   Permite reiniciar o jogo.
-   Utiliza síntese de voz para feedback através da biblioteca `responsiveVoice.js`.

## Funções Principais

-   `exibirTextoNaTela(tag, texto)`: Exibe um texto em um elemento HTML especificado.
-   `exibirMensagemInicial()`: Exibe a mensagem inicial do jogo.
-   `verificarChute()`: Verifica o palpite do jogador e fornece feedback.
-   `gerarNumeroAleatorio()`: Gera um número aleatório único.
-   `limparCampo()`: Limpa o campo de entrada.
-   `reiniciarJogo()`: Reinicia o jogo com um novo número secreto.

## Tecnologias Utilizadas

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="40" height="40" title="HTML5">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="40" height="40" title="CSS3">
  <img src="https://raw.githubusercontent.com/vscode-icons/vscode-icons/master/images/logo@3x.png" alt="VS Code" width="60" height="60" title="VS Code">
</p>

-   HTML
-   CSS
-   JavaScript
-   responsiveVoice.js (para síntese de voz)


  
## Link direto para o projeto

*[Jogo do número secreto](https://joaomiranda01.github.io/jogo-do-numero-secreto/)



## Como Jogar

1.  Abra o arquivo `index.html` em seu navegador ou entre pelo link acima ⬆️.
2.  Insira um número no campo de entrada e clique em "Chutar".
3.  Siga as dicas para adivinhar o número secreto.
4.  Clique em "Reiniciar" para jogar novamente.

## Estrutura do Projeto

-   `index.html`: Estrutura HTML do jogo.
-   `app.js`: Lógica do jogo em JavaScript.
-   `style.css`: Estilos CSS do jogo.

## Instalação

1.  Clone este repositório: `git clone https://github.com/dolthub/dolt`
2.  Abra o arquivo `index.html` em seu navegador.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.
