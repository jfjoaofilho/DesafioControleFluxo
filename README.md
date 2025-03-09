# DesafioControleFluxo

## Estrutura do Projeto:
- Projeto: DesafioControleFluxo
- Classe Principal: Contador.java
- Classe de Exceção: ParametrosInvalidosException.java

### Explicação do Código
- Leitura dos parâmetros:

  O usuário insere dois números inteiros pelo terminal.
- Validação dos parâmetros:

   Se o primeiro número for maior que o segundo, uma exceção ParametrosInvalidosException é lançada.
- Cálculo da contagem:

  A diferença entre os números define quantas vezes o for será executado.
- Iteração e Impressão:

  O programa imprime "Imprimindo o número X" até atingir o valor da contagem.

### Exemplo de Entrada e Saída
Entrada:
```java
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
```
Saída:
```java
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```
Se o primeiro número for maior:
Entrada:
```java
Digite o primeiro parâmetro:
50
Digite o segundo parâmetro:
30
```
Saída:
```java
O segundo parâmetro deve ser maior que o primeiro
```
