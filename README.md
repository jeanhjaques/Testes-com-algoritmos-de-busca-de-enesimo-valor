# Testes com algoritmos de busca de k-ésimo menor elemento de um vetor

Encontrar o elemento mínimo ou máximo em um conjunto de números é uma tarefa computacional básica que aprendemos resolver na primeira disciplina de programação de um curso
superior da área da Computação. Nesta atividade, devemos solucionar uma generalização desse
problema, conforme estudamos nas aulas:
Problema da seleção do k-ésimo menor elemento: dados um conjunto A com n números inteiros e um número inteiro k, onde 1 ≤ k ≤ n, encontrar o elemento x em A
que é maior ou igual a exatamente k − 1 elementos de A.
Você deverá implementar quatro estratégias para solucionar tal problema, conforme descrição
a seguir. Além disso, você deve medir os tempos de execução desses algoritmos e compará-los.
Para realizar essa tarefa, será necessário gerar conjuntos de dados para realização de experimentos
dessas estratégias.
Você deve implementar as seguintes estratégias para resolver o problema da seleção do késimo menor elemento em um vetor A:
1. Ordene o vetor A e devolva o elemento na posição k. Este é o k-ésimo menor elemento do
vetor A;
2. Construa uma lista de min-prioridades no vetor A. Remova os k primeiros elementos dessa
lista de min-prioridades, imprimindo o valor do último elemento removido. Esse elemento
é o k-ésimo menor elemento de A;
3. Faça a seleção aleatorizada. Isto é, execute o algoritmo RANDOMIZED-SELECT para encontrar o k-ésimo menor elemento de A;
4. Faça a seleção (de tempo de execução pior caso linear). Ou seja, execute o algoritmo SELECT
para encontrar o k-ésimo menor elemento de A.
Observe que você pode escolher qualquer algoritmo de ordenação por comparação que estudamos para implementar a estratégia 1.

# Requisitos para a execução
- Java 8 ou superior
# Como Executar
Para executar basta navegar até a raiz do projeto pelo terminal e executar o comando "javac Main.java" e em seguida o comando "java Main"
