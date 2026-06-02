# Girl's Night 🌸

Jogo de cartas interativo para noites em grupo, rodando 100% no navegador — sem instalação, sem dependências, sem servidor.

## Como funciona

Abra o arquivo `girls_night.html` diretamente no navegador. Não é necessário nenhum servidor ou build.

## Funcionalidades

- **120 cartas** embaralhadas aleatoriamente a cada partida
- **6 categorias** de cartas:
  - 🥂 Brindes
  - 💬 Confissões
  - 🎯 Desafios
  - ❓ Perguntas
  - 🤔 Mais Provável
  - 💋 Verdade
- Animação de virada de carta com flip 3D
- Animação de embaralhamento ao iniciar
- Efeitos sonoros gerados via Web Audio API (sem arquivos externos)
- Partículas animadas no fundo
- Modal de regras integrado
- Botão de mute/unmute
- Layout responsivo — funciona em mobile e desktop

## Tecnologia

Arquivo único `girls_night.html` com todo o conteúdo embutido (HTML + CSS + JS + imagens em base64). A única dependência externa é a fonte [Google Fonts](https://fonts.google.com/) (Playfair Display e Lato), carregada via CDN ao abrir o jogo.

## Uso offline

Para uso completamente offline, substitua a linha de import do Google Fonts por fontes locais ou fontes seguras de sistema.

## Estrutura do projeto

```
girls-nigth-game-web/
└── girls_night.html   # Jogo completo em arquivo único
```
