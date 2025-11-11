# COUP-MASTER
Coup Master


coup-master/
│
├── index.html                # Tela principal do jogo (a que geramos)
├── style/
│   ├── main.css              # Estilos principais (o CSS que já criamos)
│   ├── animations.css        # Animações e transições (se quiser separar)
│   └── themes/
│       ├── dark.css          # Tema escuro
│       ├── light.css         # Tema claro (opcional)
│       └── retro.css         # Temas alternativos
│
├── scripts/
│   ├── main.js               # Código principal do jogo (interações e lógica)
│   ├── ui.js                 # Manipulação da interface (cartas, botões, efeitos)
│   ├── network.js            # Comunicação online (ex: WebSocket, futuramente)
│   └── utils.js              # Funções auxiliares (random, delay, etc.)
│
├── assets/
│   ├── images/
│   │   ├── ui/               # Elementos de interface (botões, ícones)
│   │   │   ├── logo.png
│   │   │   ├── background.jpg
│   │   │   └── frame.png
│   │   ├── cards/            # Todas as cartas do jogo
│   │   │   ├── duke.png
│   │   │   ├── captain.png
│   │   │   ├── assassin.png
│   │   │   ├── contessa.png
│   │   │   ├── ambassador.png
│   │   │   ├── inquisitor.png
│   │   │   ├── back.png
│   │   │   └── dead.png
│   │   └── avatars/          # Avatares dos jogadores (padrões ou escolhidos)
│   │       ├── player1.png
│   │       ├── player2.png
│   │       └── default.png
│   │
│   ├── audio/
│   │   ├── bgm/              # Trilhas sonoras
│   │   │   ├── menu.mp3
│   │   │   ├── game.mp3
│   │   │   └── tension.mp3
│   │   └── sfx/              # Efeitos sonoros
│   │       ├── flip.mp3      # Virar carta
│   │       ├── coin.mp3      # Ganhar moeda
│   │       ├── action.mp3    # Fazer ação
│   │       └── lose.mp3      # Perder carta
│   │
│   └── fonts/                # Fontes customizadas (opcional)
│       ├── Cinzel.ttf
│       └── Inter.ttf
│
├── data/
│   ├── cards.json            # Configurações das cartas (nome, poder, imagem)
│   ├── actions.json          # Ações possíveis do jogo
│   └── localization.json     # Traduções (caso queira multilíngue)
│
├── server/                   # (opcional — para modo online)
│   ├── app.js                # Servidor Node.js / Express
│   ├── socket.js             # Comunicação em tempo real (Socket.io)
│   └── gameLogic.js          # Lógica central do jogo
│
├── docs/
│   ├── design-notes.md       # Ideias, anotações e referências
│   ├── roadmap.md            # Planejamento do desenvolvimento
│   └── changelog.md          # Registro de versões
│
└── README.md                 # Descrição geral do projeto
