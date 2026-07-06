Tecnologias utilizadas

Python 3

Shell Script (Bash)

Linux (Ubuntu)

Git

GitHub

Funcionalidades

A calculadora permite realizar as seguintes operações:



Soma

Subtração

Multiplicação

Divisão

Também possui tratamento para divisão por zero e um menu interativo que permanece em execução até que o usuário escolha encerrar o programa.



Como executar

Abra o terminal.

Navegue até a pasta do projeto.

Conceda permissão de execução ao arquivo:

chmod 744 calculadora.sh

Execute o programa:

./calculadora.sh

Estrutura do projeto

projetocalculadora/

├── calculadora.py

├── calculadora.sh

├── comandos.txt

└── README.md

Explicação do código

O programa solicita dois números ao usuário e apresenta um menu com as operações disponíveis.



Cada operação matemática foi implementada em uma função específica, tornando o código mais organizado, legível e fácil de manter.



Após a execução do cálculo, o programa pergunta ao usuário se deseja realizar uma nova operação. Caso a resposta seja positiva, a calculadora continua em execução utilizando um laço de repetição (while). Caso contrário, o programa é encerrado.



Durante o desenvolvimento foram aplicados conceitos fundamentais de programação, como:



Variáveis

Funções

Estruturas condicionais (if, elif e else)

Laços de repetição (while)

Entrada e saída de dados

Operações matemáticas

Tratamento de erros

Exemplo de utilização

=== CALCULADORA ===



Digite o primeiro número: 10

Digite o segundo número: 5



Escolha uma operação:

1 - Soma

2 - Subtração

3 - Multiplicação

4 - Divisão



Opção: 3



Resultado: 50



Deseja realizar outro cálculo? (s/n): n



Programa encerrado.

Objetivo

O objetivo deste projeto é praticar conceitos de programação em Python, utilização de scripts no Linux, versionamento de código com Git e publicação de projetos no GitHub.

