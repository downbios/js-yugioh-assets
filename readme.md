# js-yugioh-assets

**Yu-Gi-Oh | Jo-ken-po Edition**

Um jogo de _jokenpo_ (pedra, papel e tesoura) inspirado em Yu-Gi-Oh, desenvolvido para ilustrar conceitos de lógica de programação aplicados a jogos.

## Visão Geral

Este projeto utiliza uma analogia com cartas de Yu-Gi-Oh para enriquecer os conceitos por trás de um jogo simples de jokenpo. O foco está nos seguintes pilares de programação:

- **Armazenamento e gerenciamento de estado manual** — controle explícito do estado do jogo (quem venceu, quantos pontos, etc.).
- **Funções puras (clean functions)** — sem efeitos colaterais, facilitando testes, leitura e manutenção.
- **Organização de código** — estrutura clara e modular, favorecendo a escalabilidade.

## Estrutura do Projeto

```
├── src/
│ ├── assets/ # recursos estáticos (imagens, áudios, etc.)
│ ├── game.js # lógica principal do jogo (controle de turno, pontuação, etc.)
│ └── ui.js # interface com o usuário (interações, atualizações visuais)
├── index.html # página inicial do jogo
└── README.md # este arquivo
```

## Tecnologias

- **HTML** e **CSS** — marcação e estilo da interface do jogo.
- **JavaScript** — lógica do jogo, manipulação do DOM e controle de fluxo.
