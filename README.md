# Mario Kart.JS 🏁

Simulador de Corridas inspirado no jogo Mario Kart, desenvolvido com Node.js. O projeto foi realizado como parte do curso **Formação em Node.js** da **Dio**.

## Descrição 🎮

Mario Kart é uma famosa série de jogos de corrida da Nintendo. Neste desafio, criamos uma versão simplificada para simular corridas entre personagens do universo Mario Kart. Cada personagem possui atributos de **Velocidade**, **Manobrabilidade** e **Poder**, que são usados nas diferentes fases da corrida para determinar o vencedor.

O projeto foca em simular a lógica das corridas, gerando blocos de pista aleatórios (RETA, CURVA ou CONFRONTO) e utilizando dados e atributos dos personagens para determinar quem vence cada rodada.

## Funcionalidades 🔧

- **Corrida entre dois jogadores**: O jogador pode escolher dois personagens do universo Mario Kart para disputar a corrida.
- **Blocos de pista aleatórios**: A cada rodada, um bloco aleatório é sorteado (RETA, CURVA ou CONFRONTO), e o personagem deve usar seu atributo correspondente para disputar a rodada.
- **Dado de 6 lados**: A disputa é decidida por um dado de 6 lados, somado com o atributo do personagem (Velocidade, Manobrabilidade ou Poder).
- **Sistema de pontos**: O personagem que ganhar a disputa de cada rodada marca um ponto. No caso de um CONFRONTO, o perdedor perde um ponto.
- **Condição de vitória**: Ao final das 5 rodadas, o personagem com mais pontos é o vencedor.

## Personagens 🏎️

O projeto inclui os seguintes personagens:

| Personagem | Velocidade | Manobrabilidade | Poder |
|------------|------------|-----------------|-------|
| **Mario**  | 4          | 3               | 3     |
| **Peach**  | 3          | 4               | 2     |
| **Yoshi**  | 2          | 4               | 3     |
| **Bowser** | 5          | 2               | 5     |
| **Luigi**  | 3          | 4               | 4     |
| **Donkey Kong** | 2      | 2               | 5     |

## Regras do Jogo 📜

- **Jogadores**: O jogo permite a escolha de dois personagens para competir.
- **Pistas**: A corrida é realizada em uma pista de 5 rodadas. A cada rodada, um bloco da pista é sorteado (RETA, CURVA ou CONFRONTO).
  - **RETA**: O jogador rola um dado de 6 lados e soma seu atributo **Velocidade**.
  - **CURVA**: O jogador rola um dado de 6 lados e soma seu atributo **Manobrabilidade**.
  - **CONFRONTO**: O jogador rola um dado de 6 lados e soma seu atributo **Poder**. O perdedor perde um ponto.
- **Condição de Vitória**: Ao final de 5 rodadas, o jogador com mais pontos vence a corrida.

## Como Rodar 🚀

### Pré-requisitos
- Node.js (v12 ou superior) instalado

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mario-kart-js.git
   cd mario-kart-js
Instale as dependências:

bash
Copiar
Editar
npm install
Execute o simulador:

bash
Copiar
Editar
node index.js
Veja o resultado da corrida no terminal!

Aprendizado 📚
Este projeto foi desenvolvido durante o curso Formação em Node.js da Dio, e foi uma excelente oportunidade para aplicar o aprendizado sobre:

Estruturas de dados e objetos em JavaScript
Lógica de programação utilizando funções assíncronas
Manipulação de eventos aleatórios e simulação de mecânicas de jogos
Contribuições 🤝
Se você tem sugestões para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Fique à vontade para contribuir!
