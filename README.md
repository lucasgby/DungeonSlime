# 🏰 DungeoSmile

DungeoSmile é um jogo 2D de exemplo desenvolvido com [MonoGame](https://www.monogame.net/). O projeto segue a documentação oficial do MonoGame como base para aprendizado e expansão futura.

Este projeto é ideal para desenvolvedores que estão aprendendo a criar jogos com MonoGame e desejam entender a estrutura de um projeto real.

---

## 🎮 Sobre o Jogo

**DungeoSmile** é um jogo simples de exploração em uma dungeon onde o jogador controla um personagem por um labirinto. O projeto cobre:

- Criação da estrutura básica com MonoGame
- Sistema de movimentação 2D
- Uso da Pipeline Tool (MGCB) para assets
- Gerenciamento de recursos (sprites, sons, fontes)
- Organização de código em camadas (game loop, lógica, renderização)

---

## 📁 Estrutura do Projeto

```plaintext
DungeoSmile/
│
├── Content/                # Assets do jogo (sprites, áudios, fontes)
│   └── Content.mgcb        # Arquivo de build dos assets
│
├── DungeoSmile.csproj      # Projeto principal em C#
├── Game1.cs                # Classe principal do jogo
├── Program.cs              # Ponto de entrada
├── bin/                    # Saída da compilação (ignorado pelo Git)
├── obj/                    # Arquivos intermediários (ignorado pelo Git)
├── README.md               # Este arquivo
└── .gitignore              # Arquivos e pastas ignoradas pelo Git
```
---

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- [.NET SDK](https://dotnet.microsoft.com/download)
- [MonoGame SDK](https://www.monogame.net/downloads/)
- [MonoGame Pipeline Tool](https://docs.monogame.net/articles/tools/pipeline.html)

### Passos

1. Clone este repositório:
   ```bash git clone https://github.com/lucasgby/DungeoSmile.git cd DungeoSmile```

2. Execute os comandos:
```dotnet build```
```dotnet run```

3. Ou abra o .sln no Visual Studio e pressione F5.

✨ Funcionalidades Implementadas
 Estrutura básica de jogo com MonoGame

 Movimentação do jogador

 Carregamento de recursos via MGCB

 Colisões com paredes

 Sistema de inimigos

 Interface de usuário (HUD)

📚 Créditos
Baseado na documentação oficial da MonoGame.

---

Se quiser que eu personalize com seu nome, GitHub, funcionalidades específicas ou adicionar imagens/gifs do jogo depois, posso fazer isso também. Deseja que eu adicione um botão de build status, preview de tela ou instruções de publicação?