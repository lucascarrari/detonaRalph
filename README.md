# Detona Ralph - O Jogo 🕹️💥

Bem-vindo ao projeto do jogo Detona Ralph! Um divertido jogo estilo "Whac-A-Mole" onde seu objetivo é acertar o Ralph para marcar pontos antes que o tempo acabe.

![Gameplay do Jogo](https://raw.githubusercontent.com/lucascarrari/detonaRalph/main/gameplay_preview.gif)
*(Sugestão: Crie um GIF chamado `gameplay_preview.gif`, adicione à raiz do seu projeto ou a uma pasta `assets`, e atualize o link acima se necessário. Você pode usar ferramentas online como ezgif.com para criar GIFs a partir de vídeos curtos da tela.)*

## 🎮 Como Jogar

1.  **Abra o Jogo:** Visite a página do jogo hospedada [AQUI](https://lucascarrari.github.io/detonaRalph/) (se você configurar o GitHub Pages) ou abra o arquivo `index.html` localmente em seu navegador.
2.  **Objetivo:** Clique nos quadrados onde o personagem Ralph aparecer.
3.  **Pontuação:** Cada acerto no Ralph aumenta sua pontuação (`Your Score`).
4.  **Tempo:** Você tem um tempo limitado (`Time Left`) para marcar o máximo de pontos possível.
5.  **Vidas:** Você começa com 3 vidas (indicado ao lado do ícone do jogador - `player.png`, que parece ser o Felix Jr.). Perderá uma vida se não acertar o Ralph a tempo ou clicar errado (esta mecânica precisa ser implementada no `engine.js`).
6.  **Fim de Jogo:** O jogo termina quando o tempo acaba ou você perde todas as vidas.

## ✨ Funcionalidades (Implementadas e Previstas)

* **Interface do Jogo:**
    * **Painel (Grid):** Uma grade 3x3 onde o Ralph aparece aleatoriamente.
    * **Tempo Restante:** Contador regressivo de tempo.
    * **Pontuação:** Exibição da pontuação atual do jogador.
    * **Vidas:** Exibição das vidas restantes do jogador (Felix Jr.).
* **Mecânicas de Jogo (a serem implementadas em `engine.js`):**
    * Aparição aleatória do Ralph em um dos quadrados do painel.
    * Detecção de clique no quadrado correto (com o Ralph).
    * Incremento da pontuação ao acertar.
    * Decremento do tempo.
    * Lógica de vidas (perda de vidas).
    * Condições de fim de jogo (tempo esgotado ou vidas zeradas).
    * Reinício do jogo.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura base do jogo.
* **CSS3:** Estilização da interface e elementos visuais.
    * **Google Fonts:**
        * `Bebas Neue`
        * `Press Start 2P` (para um toque retrô!)
* **JavaScript:** Lógica do jogo e interatividade (no arquivo `src/scripts/engine.js`).

## 📂 Estrutura do Projeto

detonaRalph/
├── index.html                # Arquivo principal do jogo
├── README.md                 # Este arquivo que você está lendo
└── src/
├── images/
│   └── player.png        # Imagem do avatar do jogador (Felix Jr. para as vidas)
│   └── ralph.png         # (Sugestão) Imagem do Ralph para aparecer nos quadrados
├── scripts/
│   └── engine.js         # Lógica principal do jogo em JavaScript
└── styles/
├── main.css          # Estilos principais do jogo
└── reset.css         # Reset de estilos CSS padrão do navegador


## 🚀 Como Executar Localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/lucascarrari/detonaRalph.git](https://github.com/lucascarrari/detonaRalph.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd detonaRalph
    ```
3.  Abra o arquivo `index.html` no seu navegador web favorito.

## 💡 Melhorias Futuras (Sugestões)

* [ ] Adicionar efeitos sonoros para acertos, erros e música de fundo.
* [ ] Implementar diferentes níveis de dificuldade (Ralph mais rápido, menos tempo).
* [ ] Salvar recordes de pontuação (usando `localStorage`).
* [ ] Animações mais fluidas para o aparecimento e desaparecimento do Ralph.
* [ ] Adicionar outros personagens ou bônus/penalidades.
* [ ] Implementar a lógica completa de perda de vidas no `engine.js`.
* [ ] Tela de "Game Over" com opção de reiniciar.

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas!

1.  Faça um **Fork** deste repositório (`https://github.com/lucascarrari/detonaRalph/fork`).
2.  Crie uma nova **Branch** (`git checkout -b feature/minha-nova-funcionalidade`).
3.  Faça suas alterações e **Commit** (`git commit -m 'Adiciona minha nova funcionalidade'`).
4.  **Push** para a Branch (`git push origin feature/minha-nova-funcionalidade`).
5.  Abra um **Pull Request**.

## 👤 Autor

* **Lucas Carrari**
    * GitHub: [@lucascarrari](https://github.com/lucascarrari)
    * LinkedIn: [lucascarrari](https://www.linkedin.com/in/lucascarrari/)

---

Divirta-se jogando e desenvolvendo! Se gostar do projeto, não se esqueça de dar uma ⭐!
