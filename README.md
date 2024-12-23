## Jogo do Número Secreto

### Descrição
Este código implementa um simples jogo de adivinhação de números. O jogador precisa chutar um número entre 1 e 10, e o programa informa se o chute foi maior, menor ou igual ao número secreto.

### Como funciona
1. **Geração do número secreto:** Um número aleatório é gerado entre 1 e 10, garantindo que não haja repetições.
2. **Chute do jogador:** O jogador insere um número no campo de texto.
3. **Verificação do chute:** O programa compara o chute com o número secreto e fornece um feedback ao jogador.
4. **Contagem de tentativas:** O número de tentativas é incrementado a cada chute errado.
5. **Reinício do jogo:** Ao acertar o número, um botão de reinício é habilitado, permitindo começar uma nova partida.

### Explicação do código (por partes)
* **Variáveis:** Explique o propósito de cada variável (listaDeNumerosSorteados, numeroLimite, numeroSecreto, tentativas).
* **Funções:** Descreva o que cada função faz (exibirTextoNaTela, exibirMensagemInicial, verificarChute, gerarNumeroAleatorio, limparCampo, reiniciarJogo).
* **Lógica:** Explique a lógica por trás da geração de números aleatórios, da verificação dos chutes e do reinício do jogo.

### Tecnologias utilizadas
* **JavaScript:** Linguagem de programação utilizada para criar a lógica do jogo.
* **HTML:** Estrutura da página web.
* **CSS:** Estilização da página (opcional, se você tiver aplicado estilos).

### Observações
* **Acessibilidade:** O código utiliza a Web Speech API para ler as mensagens em voz alta, tornando o jogo mais acessível.
* **Lógica de programação:** Destaque os conceitos de variáveis, funções, condicionais, loops e outras estruturas de programação utilizadas no código.
