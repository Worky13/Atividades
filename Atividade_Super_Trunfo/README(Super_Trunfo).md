Este é um jogo simples de cartas desenvolvido em C, onde duas cartas representando cidades são comparadas com base em diversos atributos, como
população, área, PIB, pontos turísticos, densidade populacional, PIB per capita e um "Super Poder" calculado.

## Como Funciona

O programa permite ao usuário cadastrar duas cartas, cada uma representando uma cidade. Para cada cidade, são coletados os seguintes dados:

**Estado**: Representado por uma letra de A a H.
**Código da Carta**: Um código único para a carta (ex: A01, B02).
**Nome da Cidade**: O nome da cidade.
**População**: Número de habitantes da cidade.
**Área**: Área da cidade em km².
**PIB**: PIB da cidade em bilhões de reais.
**Pontos Turísticos**: Número de pontos turísticos na cidade.

Com base nesses dados, o programa calcula:

- **Densidade Populacional**: População dividida pela área.
- **PIB per Capita**: PIB dividido pela população.
- **Super Poder**: Um valor calculado com base na população, área, PIB, pontos turísticos, PIB per capita e densidade populacional.

Após o cadastro das duas cartas, o programa compara os atributos de ambas e determina qual carta vence em cada categoria.

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

