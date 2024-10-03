# Calculadora de IMC em Python

Esta **calculadora de IMC (Índice de Massa Corporal)** desenvolvida em **Python**. Com ela, o usuário pode inserir seu peso e altura para que seja calculado rapidamente seu IMC.

## Funcionalidades

- **Entrada de dados**: O usuário insere seu peso em **Kilos** e altura em **Metros**.
- **Tratamento de erros**: Através das funções de **'try'** e **'except'** é possível garantir que apenas valores númerios sejam permitidos, fazendo com que o código não pare caso seja inserida qualquer informação diferente de números. Além disso, pensando no usuário, foi inserida uma função que troca virgula por ponto, pois em algumas localidades é comum utilizar virgula para separar valores.
- **Resultados**: Após calcular o **IMC**, o programa exibe a categoria correspondente as diretrizes da **OMS(Organização Mundial da Saúde)**:

| **Classificação**              | **IMC (kg/m²)**           |
| ------------------------------ | ------------------------- |
| Abaixo do peso                 | Menor que 18,5            |
| Peso normal                    | 18,5 – 24,9               |
| Sobrepeso                      | 25,0 – 29,9               |
| Obesidade grau I               | 30,0 – 34,9               |
| Obesidade grau II              | 35,0 – 39,9               |
| Obesidade grau III (Mórbida)   | Maior ou igual a 40,0      |

## Como usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Clone este repositório ou faça o download do código fonte.
3. Abra o terminal e navegue até o diretório do projeto.
4. Execute o programa.
