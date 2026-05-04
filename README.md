# 🏓 Pro Ping Pong - International Edition

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um simulador de Tênis de Mesa (Ping-Pong) desenvolvido com foco em **Game Feel**, fidelidade visual às normas internacionais e mecânicas competitivas.

## 🚀 Funcionalidades

- **Modo Solo vs CPU:** Inteligência Artificial adaptativa que acompanha o ritmo do jogador.
- **Modo Local PvP:** Jogue contra um amigo no mesmo teclado.
- **Aceleração Competitiva:** A cada rebatida, a velocidade da bola aumenta em **3%**, tornando o rally progressivamente mais desafiador.
- **Áudio Sintetizado:** Efeitos sonoros gerados via `Web Audio API` (sem necessidade de arquivos externos).
- **Estética Profissional:** Cores oficiais baseadas na ITTF (Azul Cobalto) com animações de impacto e inclinação dos paddles.

## 🎮 Como Jogar

1. Baixe o arquivo `index.html`.
2. Abra em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3. Selecione o modo de jogo no menu principal.

### Controles
| Ação | Player 1 (Esquerda) | Player 2 (Direita) |
| :--- | :--- | :--- |
| **Mover para Cima** | `W` | `Seta para Cima` |
| **Mover para Baixo** | `S` | `Seta para Baixo` |

## 🛠️ Tecnologias e Conceitos Aplicados

Este projeto foi construído utilizando conceitos fundamentais de Engenharia de Software e Desenvolvimento de Jogos:

- **Game Loop:** Implementado com `requestAnimationFrame` para uma renderização suave de 60 FPS.
- **Física de Vetores:** Cálculo de reflexão de ângulo baseado na posição de impacto da bola no paddle.
- **Procedural Audio:** Geração de ondas sonoras em tempo real usando `OscillatorNode`.
- **Dificuldade Progressiva:** Algoritmo de aceleração linear para aumentar o engajamento competitivo.

## 📌 Melhorias Futuras

- [ ] Implementação de Multiplayer Online via WebSockets.
- [ ] Sistema de partículas para faíscas neon no impacto.
- [ ] Ranking local de maiores pontuações (LocalStorage).

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

---
Desenvolvido por [Seu Nome ou Usuário do GitHub] 🚀
