# Estrutura de Dados

## Selection Sort

O Selection Sort é um algoritmo simples de ordenação que percorre o array repetidamente, selecionando o menor (ou maior, dependendo da ordem) elemento restante e colocando-o em sua posição correta. 

### Pontos importantes:

1. **Definição e Funcionamento**:
    - O Selection Sort divide o array em duas partes: a parte já ordenada e a parte não ordenada.
    - Em cada iteração, ele seleciona o menor (ou maior) elemento da parte não ordenada e troca com o primeiro elemento dessa parte, expandindo a parte ordenada.

2. **Passos do Algoritmo**:
    - Encontre o menor elemento no array não ordenado.
    - Troque-o com o primeiro elemento da parte não ordenada.
    - Repita o processo com o restante do array, movendo o limite entre as partes ordenada e não ordenada.

3. **Complexidade**:
    - Pior, melhor e caso médio: `O(n²)`, porque, independentemente do estado inicial do array, o algoritmo sempre percorre todas as posições.
    - Não depende da ordenação inicial dos dados, ao contrário do Insertion Sort, que pode ser mais eficiente em dados quase ordenados.

4. **Vantagens**:
    - Simples de entender e implementar.
    - Não requer memória adicional significativa, pois é um algoritmo **in-place** (não precisa de espaço extra para ordenar).

5. **Desvantagens**:
    - Ineficiente para grandes conjuntos de dados devido à sua complexidade `O(n²)`.
    - Mesmo que o array já esteja ordenado, ele ainda percorre todas as comparações.

6. **Aplicações**:
    - Usado em cenários onde o custo de troca (swap) é baixo e as trocas precisam ser minimizadas, pois faz no máximo `n-1` trocas.

7. **Exemplo**:
   Para ordenar o array `[64, 25, 12, 22, 11]`:
    1. Encontre o menor elemento (11) e troque com o primeiro elemento: `[11, 25, 12, 22, 64]`.
    2. Encontre o menor entre os elementos restantes (12) e troque com o segundo: `[11, 12, 25, 22, 64]`.
    3. Continue até que o array esteja ordenado: `[11, 12, 22, 25, 64]`.

8. **Comparação com outros algoritmos**:
    - Embora seja mais simples que o Quicksort e Merge Sort, o Selection Sort é menos eficiente para listas grandes.
    - Em relação ao Bubble Sort, o Selection Sort realiza menos trocas, o que pode ser uma vantagem dependendo do sistema.

![Exemplo do funcionamento do Busca Binária](https://www.w3resource.com/w3r_images/selection-short.png)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
