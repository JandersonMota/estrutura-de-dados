# Estrutura de Dados

## Quicksort
Quicksort é um algoritmo de ordenação que funciona por meio da divisão e conquista, e que é muito usado na prática. Ele foi criado por C.A.R. Hoare em 1960, quando trabalhava na tradução de um dicionário de inglês para russo.

### Pontos importantes:

1. **Definição e Funcionamento**:
   - Quicksort é um algoritmo de ordenação eficiente que usa a estratégia de divisão e conquista.
   - Ele seleciona um elemento como pivô e particiona o array de forma que elementos menores que o pivô fiquem à esquerda, e elementos maiores fiquem à direita.

2. **Passos do Algoritmo**:
   - **Escolha do pivô**: pode ser o primeiro elemento, o último, um elemento aleatório, ou o elemento central.
   - **Particionamento**: reorganiza os elementos de forma que todos os menores que o pivô fiquem antes dele, e todos os maiores, depois.
   - **Recursão**: aplica o Quicksort recursivamente nas sublistas (à esquerda e à direita do pivô).

3. **Análise de Complexidade**:
   - **Caso médio**: O(n log n), que ocorre na maioria das vezes.
   - **Pior caso**: O(n²), quando o pivô escolhido é o menor ou maior elemento em um array já ordenado ou quase ordenado.
   - **Melhor caso**: O(n log n), quando o pivô divide o array em duas partes aproximadamente iguais.

4. **Vantagens**:
   - É in-place (não requer memória adicional significativa).
   - Em geral, é mais rápido que o MergeSort e HeapSort na prática.

5. **Desvantagens**:
   - No pior caso, pode ter complexidade O(n²).
   - Pode ser ineficiente para listas já ordenadas ou quase ordenadas (a menos que a escolha do pivô seja otimizada).

6. **Técnicas para Melhorar**:
   - **Escolha inteligente do pivô**: como usar o pivô mediano ou um pivô aleatório para minimizar o risco do pior caso.
   - **Algoritmos de particionamento**: como o de Lomuto e o de Hoare, para reorganizar o array em torno do pivô.

![Exemplo do funcionamento do Quicksort](https://s3.amazonaws.com/hr-challenge-images/quick-sort/QuickSort.png)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
