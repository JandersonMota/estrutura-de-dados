# Estrutura de Dados

## Heapsort

O **Heapsort** é um algoritmo de ordenação baseado na estrutura de dados conhecida como **heap** (ou **árvore binária**). Ele é eficiente e possui um tempo de execução O(n log n), sendo amplamente utilizado em diversas aplicações devido à sua estabilidade e eficiência.

### 1. Definição
- O **Heapsort** constrói um **heap máximo** ou **mínimo** a partir dos dados a serem ordenados e, em seguida, extrai o maior (ou menor) elemento repetidamente para ordenar os dados.
- Um **heap** é uma árvore binária completa em que cada nó segue a propriedade de heap:
  - **Heap máximo:** Cada pai é maior que seus filhos.
  - **Heap mínimo:** Cada pai é menor que seus filhos.

### 2. Funcionamento
O algoritmo pode ser dividido em duas fases principais:
1. **Construção do Heap:** Converte o array original em um heap máximo ou mínimo.
2. **Ordenação:** Repetidamente extrai o maior (ou menor) elemento do heap e ajusta o heap para manter a propriedade de heap.

### 3. Passos do Algoritmo
1. **Construção do Heap:**
   - Construa um heap máximo a partir do array (para ordenar em ordem crescente).
   - A partir da metade do array, desça cada nó para garantir que a propriedade de heap seja mantida.
2. **Ordenação:**
   - Remova o maior elemento (raiz do heap) e troque-o com o último elemento do array.
   - Reduza o tamanho do heap e reorganize o restante do heap para restaurar a propriedade de heap.
   - Repita o processo até que todos os elementos estejam ordenados.

### 4. Complexidade
- **Melhor caso:** O(n log n)
- **Pior caso:** O(n log n)
- **Caso médio:** O(n log n)

A complexidade do **Heapsort** é a mesma em todos os casos, pois o algoritmo sempre realiza o mesmo número de operações, independentemente do estado inicial dos dados.

### 5. Vantagens
- **Eficiência:** O(n log n) em todos os casos, tornando-o mais eficiente que algoritmos quadráticos como Insertion Sort e Selection Sort.
- **Estabilidade de memória:** Não requer espaço adicional significativo, pois é um algoritmo **in-place** (realiza a ordenação sem alocar memória extra para outra estrutura de dados).
- **Determinístico:** Ao contrário do Quicksort, o Heapsort não depende de decisões aleatórias ou do estado inicial da lista.

### 6. Desvantagens
- **Não é estável:** O **Heapsort** não preserva a ordem relativa de elementos iguais, o que pode ser uma desvantagem em alguns contextos.
- **Desempenho prático:** Embora tenha a mesma complexidade de outros algoritmos de ordenação como o Quicksort e o Merge Sort, o Heapsort costuma ser mais lento em cenários práticos devido ao overhead das operações de heapificação.

### 7. Aplicações
- **Sistemas de tempo real:** O Heapsort é utilizado em situações onde é importante garantir o pior caso O(n log n), como em sistemas embarcados ou em sistemas de tempo real.
- **Filas de prioridade:** O algoritmo pode ser utilizado para gerenciar filas de prioridade, onde é necessário manter a ordem dos elementos de forma eficiente.

### 8. Exemplo de Funcionamento
Dado o array `[4, 10, 3, 5, 1]`, o **Heapsort** funcionaria da seguinte forma:

1. Construa o heap máximo: `[10, 5, 3, 4, 1]`.
2. Troque o primeiro (maior) elemento com o último: `[1, 5, 3, 4, 10]`.
3. Reorganize o heap para manter a propriedade de heap: `[5, 4, 3, 1, 10]`.
4. Continue esse processo até que o array esteja ordenado: `[1, 3, 4, 5, 10]`.

### 9. Comparação com Outros Algoritmos
- **Quicksort:** Embora o Quicksort tenha uma complexidade O(n log n) no caso médio, ele pode ter um desempenho O(n²) no pior caso, enquanto o Heapsort é sempre O(n log n).
- **Merge Sort:** Ambos têm a mesma complexidade, mas o Merge Sort requer memória adicional para armazenar subarrays, enquanto o Heapsort é in-place.

### 10. Resumo
O **Heapsort** é um algoritmo de ordenação eficiente com complexidade garantida O(n log n) para todos os casos. Ele é útil em sistemas que necessitam de uma ordenação previsível e sem alocações de memória extras, mas pode ser menos prático em comparação com outros algoritmos em termos de desempenho real.

<img src="https://formulafunction.wordpress.com/wp-content/uploads/2017/07/heapsort.png?w=1182">

### Para mais informações:
[Para aprender mais](https://formulafunction.wordpress.com/2017/07/18/heapsort/)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
