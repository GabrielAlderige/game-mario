
# 🕹️ Mario Jump Game

Um simples e divertido jogo do Mario feito com HTML, CSS e JavaScript puro. O objetivo é desviar dos canos pulando no tempo certo!

---

## 🌐 Jogue Agora

👉 [Acesse aqui o jogo](https://inspirodesignbr.com/mariogame/)

---

## 📦 Sobre o Projeto

Este é um mini game inspirado no universo do Mario Bros, onde o jogador precisa pular para evitar colisões com o cano. O jogo para automaticamente quando o Mario colide com o obstáculo, mostrando uma imagem de "game over".

---

## 🚀 Tecnologias Utilizadas

- HTML5  
- CSS3 (com animações)  
- JavaScript Vanilla (puro)

---

## 📂 Estrutura de Arquivos

```
mario-jump-game/
├── index.html
├── style.css
├── script.js
└── imgs/
    ├── mario.gif
    ├── game-over.png
    └── pipe.png
```

---

## 🎮 Como Jogar

- **Teclado**: Pressione qualquer tecla para fazer o Mario pular.  
- **Mobile**: Toque na tela para pular.

---

## 🧠 Lógica do Jogo

- O jogo adiciona a classe `jump` ao Mario por 500ms para simular o pulo.
- Um loop contínuo verifica se há colisão entre o Mario e o cano.
- Caso ocorra colisão:
  - As animações param.
  - A imagem do Mario muda para a de "game over".
  - O jogo é encerrado.

---

## 🛠️ Como Rodar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mario-jump-game.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd mario-jump-game
   ```

3. Abra o arquivo `index.html` no navegador  
   ou use a extensão **Live Server** no VS Code para rodar localmente.

---

## ✅ Melhorias Futuras

- Contador de pontos (score).  
- Aumento gradual da velocidade do cano.  
- Sistema de reinício automático.  
- Sons e trilha sonora.

---

## 📸 Preview

<p align="center">
  <img src="./imgs/0419.gif" width="400" alt="Gameplay do Mario Jump" />
</p>

---

## 🧑‍💻 Autor

**Gabriel Alderige**  
📸 Instagram: [@gabcarvalhomelo](https://www.instagram.com/gabcarvalhomelo/)  
💼 LinkedIn: [https://www.linkedin.com/in/gabrielalderige/](https://www.linkedin.com/in/gabrielalderige/)

---

## 📄 Licença

Este projeto está sob a licença MIT.  
Sinta-se livre para usá-lo, modificar e distribuir.
