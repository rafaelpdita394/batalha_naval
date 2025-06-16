# 🚢 Batalha Naval - Posicionando Navios (Nível Novato)

Desafio introdutório em **linguagem C**, focado em arrays unidimensionais e bidimensionais.  
Simulamos o posicionamento de dois navios em um tabuleiro 10x10 do jogo **Batalha Naval**:

- 1 navio na **horizontal**
- 1 navio na **vertical**

---

## 🧠 Conceitos aplicados

- 🧮 Matrizes (arrays bidimensionais)  
- 📏 Vetores (arrays unidimensionais)  
- 🔁 Estruturas de repetição (`for`)  
- 🧠 Condicionais (`if`)  
- ✍️ Boas práticas (legibilidade, indentação e comentários)

---

## 📋 Requisitos do desafio

- Criar uma matriz 10x10 representando o tabuleiro (`0` = água)
- Posicionar dois navios de tamanho 3:
  - Um na **horizontal**
  - Um na **vertical**
- Usar o valor `3` para representar as partes dos navios
- Garantir:
  - ✅ Os navios **não ultrapassem os limites**
  - ✅ **Não se sobreponham**
- Exibir o tabuleiro formatado no console

---

## 🛠️ Funcionamento do código

- `tabuleiro[10][10]`: matriz que representa o tabuleiro
- Coordenadas dos navios são **definidas diretamente no código**
- A função `exibirTabuleiro()` imprime o estado atual
- Validações impedem:
  - Que os navios saiam do tabuleiro
  - Que um navio sobreponha o outro
- Os navios são posicionados copiando os valores para a matriz conforme orientação

---

## ✅ Exemplo de saída

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
