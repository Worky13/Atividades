Este projeto implementa um tabuleiro simplificado de Batalha Naval com habilidades especiais em C. O código demonstra 
o posicionamento de navios e a aplicação de três tipos de habilidades especiais no tabuleiro.

## Descrição
**O programa cria:**

Um tabuleiro 10x10 inicializado com água (0)

4 navios posicionados em diferentes orientações (horizontal, vertical, diagonais)

3 habilidades especiais com padrões distintos:

Cone: padrão triangular

Cruz: padrão em cruz

Octaedro: padrão em losango


## Saída do Programa
**O programa exibirá:**

O tabuleiro final com:

0 para água

3 para navios

5 para áreas afetadas por habilidades

As matrizes de cada habilidade especial


## Principais Funcionalidades

Inicialização do tabuleiro com água

Posicionamento dos navios:

Navio 1: horizontal

Navio 2: vertical

Navio 3: diagonal principal

Navio 4: diagonal secundária

Criação das habilidades:

Cone: padrão triangular

Cruz: padrão em cruz

Octaedro: padrão em losango

Aplicação das habilidades no tabuleiro


## Matrizes de Habilidade

Habilidade	Formato	Tamanho
Cone	      △	     7x7
Cruz	      +	     7x7
Octaedro	  ◇	     7x7


## Como Executar

1. Compilação: Compile o código usando um compilador C, como gcc.
2. Execução: Execute o programa gerado: ./super_trunfo
3. Cadastro de Cartas: Siga as instruções no terminal para cadastrar as duas cartas.
4. Comparação: Após o cadastro, o programa exibirá os dados das cartas e fará a comparação entre elas.

## Requisitos

GitHub Codespaces
ou
Visual Studio Code: baixe e instale o Visual Studio Code, e adicione a extensão C/C++ da Microsoft. Você também precisará do compilador MinGW.

## Licença

Esta é uma atividade desenvolvida para o Curso de Redes de Computadores da faculdade Estácio, na máteria Introdução à Programação de Computadores 
pelo aluno Matheus dos Santos Segura. O código é aberto e está livre para uso e modificação.