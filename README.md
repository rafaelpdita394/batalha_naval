🚢 Batalha Naval - Posicionando Navios (Nível Novato)
Este é um desafio introdutório em linguagem C com foco em arrays unidimensionais e bidimensionais, onde simulamos o posicionamento de dois navios no tabuleiro de um jogo de Batalha Naval. Um navio é colocado na orientação horizontal e outro na vertical em uma matriz 10x10.

🧠 Conceitos aplicados
Matrizes (arrays bidimensionais)

Vetores (arrays unidimensionais)

Estruturas de repetição (for)

Condicionais (if)

Boas práticas de codificação (legibilidade e comentários)

📋 Requisitos do Desafio
Criar uma matriz 10x10 representando o tabuleiro (valores 0 = água).

Posicionar dois navios de tamanho 3:

Um na horizontal

Outro na vertical

Usar 3 para representar a presença de partes dos navios.

Garantir:

Os navios não ultrapassem os limites do tabuleiro.

Os navios não se sobreponham.

Exibir o tabuleiro no console de forma clara.

🛠️ Como funciona o código
Estrutura principal:
tabuleiro[10][10]: matriz que armazena o estado do jogo.

Coordenadas dos navios são definidas diretamente no código.

Função exibirTabuleiro() mostra a matriz no terminal.

Validações garantem que os navios:

Fiquem dentro dos limites.

Não se sobreponham.

O posicionamento copia os valores dos vetores dos navios para a matriz.

✅ Exemplo de Saída

Tabuleiro:

0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 3 3 3 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 

📎 Arquivo
batalha_naval.c: Código principal do programa

🧪 Como executar
Usando terminal (Linux ou Windows com GCC):

gcc batalha_naval.c -o batalha_naval
./batalha_naval

📚 Possíveis extensões (nível intermediário)
Entrada do usuário para posicionar os navios

Verificação automática de sobreposição com mais navios

Sistema de ataques e verificação de acertos

Interface gráfica com bibliotecas como SDL

👨‍💻 Autor
Desenvolvido por Rafael
