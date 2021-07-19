# Pedra - Papel - Tesoura - Lagarto - Spock

<img src = "https://user-images.githubusercontent.com/63079757/126098692-4a884241-f727-4399-a5e8-c7247e5e796d.jpg" width="250">

### Desafio

Pedra-Papel-Tesoura-Lagarto-Spock é uma expansão do clássico jogo Pedra-Papel-Tesoura. Atua sob o mesmo princípio básico, 
mas inclui outras duas armas adicionais: lagarto e Spock, reduzindo, assim, as chances de uma rodada terminar em um empate.

As regras de Pedra-papel-tesoura-lagarto-Spock são:

- Tesoura corta papel
- Papel cobre pedra
- Pedra esmaga lagarto
- Lagarto envenena Spock
- Spock esmaga (ou derrete) tesoura
- Tesoura decapita lagarto
- Lagarto come papel
- Papel refuta Spock
- Spock vaporiza pedra

### E como sempre...

- Pedra amassa tesoura

### Resolução

- Como o jogo é para apenas 2 jogadores, criei um código java para resolver o desafio, onde o usuário desafia o computador.
- A princípio defini as variáveis a serem utilizadas no desafio.
- Depois fiz uma estrutura condicional *switch/case* para definir as opções a serem escolhidas pelo usuário e pelo computador.
- Em cada jogada era necessário verificar 10 situações, então utilizei um *if encadeado* para analisá-las e, assim, resolver o desafio.
- Ao final, o usuário escolhe primeiro a jogada, em seguida o computador joga e é mostrado quem venceu a partida.
