# SENAI Fullstack [Education]

## Resolução dos exercícios da Semana 05

### M3S05 | Explicação dos Exercícios

Olá, turma. Os exercícios seguirão a mesma base do projeto que desenvolvemos em aula. Esses exercícios ajudarão você a entender como criar testes unitários para diferentes funcionalidades em uma aplicação Angular. A prática de escrever testes não apenas melhora a qualidade do código, mas também aumenta a confiança na manutenção e evolução do software. Boa sorte e divirtam-se testando!

### M3S05 | Ex 01 - Criação dos funções

Adicione no HTML principal do seu componente 3 novos botões, além do botão do somar que já existe. Os novos botões serão: subtrair, dividir e multiplicar. Em seguida, crie 3 funções para serem chamadas em cada botão.

Crie no serviço estas funções:

- Uma função que receberá 2 parâmetros e retornará a subtração deles.
- Uma função que receberá 2 parâmetros e retornará a divisão deles. Antes de retornar o valor, adicionar uma condição onde, se que o valor do segundo parâmetro for igual a 0, deve ser lançado um throw error com a mensagem “Divisão por zero“.
- Uma função que receberá 2 parâmetros e retornará a multiplicação deles.

Estas funções serão chamadas no componente principal e serão usadas nos novos botões adicionados.

### M3S05 | Ex 02 - Teste de Subtração

- Crie um teste que verifique se a função `subtração` do `CalculatoraService` retorna o resultado correto ao subtrair dois números.

### M3S05 | Ex 03 - Teste de Multiplicação

- Crie um teste que verifique se a função `multiplicação`do `CalculatoraService` retorna o resultado correto ao multiplicar dois números.

### M3S05 | Ex 04 - Teste de Divisão

- Crie um teste que verifique se a função `divisão`do `CalculatoraService` retorna o resultado correto ao dividir dois números.

### M3S05 | Ex 05 - Teste de Divisão por zero

- Crie um teste que verifique se a função `dividir`lança um erro ao tentar dividir por zero.

### M3S05 | Ex 06 - Testes de cálculo no componente

- Crie um teste que verifique se a função `dividir`lança um erro ao tentar dividir por zero.

### M3S05 | Ex 07 - Teste de ngModel

- Crie um teste que verifique se o `ngModel` está funcionando corretamente, ou seja, se a entrada do usuário atualiza as variáveis `num1` e `num2` no componente.
