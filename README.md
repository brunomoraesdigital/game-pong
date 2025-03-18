# Pong Game

Este é um jogo clássico de **Pong**, desenvolvido como parte do meu aprendizado em desenvolvimento web. O jogo foi feito com **HTML**, **CSS** e **JavaScript**.

<a href="https://brunomoraesdigital.github.io/pong/" target="_blank" rel="noopener noreferrer">Ver Demonstração</a>

## Objetivo do Projeto

O **Pong Game** foi criado com o intuito de:
- Recriar o clássico jogo Pong de forma simples e divertida.
- Praticar o uso de JavaScript para manipulação de elementos no DOM e lógica de jogo.
- Melhorar as habilidades de design e responsividade com **CSS** e estruturar com **HTML**.

## Funcionalidades

- **Controle de Raquetes**: O jogador pode mover as raquetes para esquerda e para direita usando o teclado.
  - Raquete direita: setas `←` (para esquerda) e `→` (para direita)
  
- **Bola em Movimento**: A bola se move automaticamente e quica nas paresdes e na raquete.
  
- **Pontuação**: A pontuação atual e o recorde são exibidos na tela, ficando registrando o recorde ao início de uma nova partida.
  
- **Nível**: O nível do jogo é exibido na tela e aumenta conforme a pontuação sobe. A cada **100 pontos**, a dificuldade do jogo aumenta.  

- **Vidas**: O jogador tem um limite de **5 vidas**, exibidas na tela. A cada certo número de pontos obtidos, o jogador ganha uma vida extra.  

- **Reinício Automático**: Após cada ponto marcado, a bola e as raquetes são reposicionadas automaticamente no centro da tela.  

- **Design Simples**: O jogo possui uma interface minimalista, com elementos bem definidos para uma experiência clara e intuitiva.

- **Design Responsivo**: Funciona em qualquer tamanho de tela.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página e dos elementos do jogo.
- **CSS**: Estilização do jogo, com destaque para a responsividade.
- **JavaScript**: Lógica do jogo e alguns ajustes de posicao.

## Melhorias a serem implementadas

- [x] incluir a pontuação máxima para o valor de 5 digitos.
- [x] Ajustar a velocidade da bola ao acertar as raquetes, a bolinha está ganhando velocidade ao colidir com a raquete.
- [x] Incluir uma contagem de tempo para inicio do jogo, bem como para reinicio do jogo (relançamento bolinha, após perder uma vida).
- [x] Dependendo de onde a bolinha acertar na raquete, a bolinha deve ir em um angulo direrente.
- [x] Incluir um pequeno tutorial.
- [x] Movimentar a raquete com o mouse.
- [x] Movimentar a raquete com o teclado.
- [x] Incluir um loader de pré-carregamento antes do jogo iniciar, uma animação de carregamento deve ser exibida para garantir que todos os elementos estejam prontos antes da jogabilidade começar.

## Problemas Observados a Serem Resolvidos

- [x] A bola nem sempre reinicia indo para o lado contrário.
- [x] A bola deve reiniciar sempre indo para cima, para evitar perder a bola caso o jogador mova a raquete rápido demais.
- [x] As raquetes tem um pequeno atraso para iniciar o movimento.
- [x] Algumas vezes a bolinha desliza verticalmente e rente pela lateral da raquete, ou mesmo passa por dentro da raquete.
- [x] Quando o cursor do mouse sai da area do jogo, para de controlar a raquete.

## Licença

Este projeto está licenciado sob a Licença AGPL v3 - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

