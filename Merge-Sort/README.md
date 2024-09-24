# Estrutura de Dados

## Merge Sort
Merge Sort é um algoritmo de ordenação que funciona de acordo com a estratégia “dividir para conquistar”. Ele divide uma estrutura em subconjuntos, ordena os elementos de cada subconjunto e, por fim, mistura os subconjuntos em um conjunto final ordenado. Ele foi criado pelo matemático americano John Von Neumann em 1945.

### Pontos importantes:

1. **Definição e Funcionamento**:
   - Merge Sort é um algoritmo de ordenação baseado no princípio da divisão e conquista.
   - Ele divide repetidamente o array em duas metades até que cada subarray tenha apenas um elemento e, em seguida, reconstrói o array ordenado a partir dessas partes menores.

2. **Passos do Algoritmo**:
   - **Divisão**: O array é dividido em duas metades de forma recursiva até que o tamanho seja 1.
   - **Conquista**: Combina duas metades menores de maneira que os elementos sejam ordenados.
   - **Mesclagem (Merge)**: As duas sublistas já ordenadas são combinadas em uma única lista ordenada.

3. **Análise de Complexidade**:
   - **Complexidade no pior, melhor e caso médio**: O(n log n), pois o array é dividido logaritmicamente e cada etapa de mesclagem percorre todas as sublistas.
   - **Uso de memória**: O Merge Sort requer O(n) de espaço adicional, pois necessita de um array temporário para combinar as sublistas.

4. **Vantagens**:
   - **Estável**: Mantém a ordem relativa dos elementos iguais no array original.
   - **Desempenho consistente**: Possui a mesma complexidade em todos os casos, ao contrário do Quicksort.
   - É adequado para listas grandes e para listas armazenadas em dispositivos de armazenamento externo (ex., discos rígidos).

5. **Desvantagens**:
   - **Uso de memória extra**: Precisa de espaço adicional proporcional ao tamanho do array.
   - Para listas pequenas, pode ser mais lento que algoritmos como o Quicksort ou o Insertion Sort.

6. **Processo de Mesclagem**:
   - A função de mesclagem é responsável por combinar duas metades ordenadas em uma única lista ordenada. Ela percorre ambos os arrays e coloca os elementos em ordem.

7. **Aplicação**:
   - O Merge Sort é preferido em cenários que exigem uma ordenação estável e onde o espaço extra não é um problema. É também útil quando os dados não cabem inteiramente na memória principal.

### Comparação com Quicksort:
- Merge Sort garante O(n log n) mesmo no pior caso, enquanto o Quicksort pode cair para O(n²) se mal implementado.
- Merge Sort é melhor para dados em discos ou sistemas distribuídos, enquanto o Quicksort geralmente é mais rápido em memória.
- [Veja o repositório do Quicksort no GitHub](https://github.com/JandersonMota/estrutura-de-dados/tree/main/Quicksort)

![Exemplo do funcionamento do Quicksort](https://www.w3schools.com/dsa/img_mergesort_long.png)

### Para mais informações:
[Leitura](https://www.w3schools.com/dsa/dsa_algo_mergesort.php)
[Vídeo](https://www.instagram.com/reel/CvulfWogTfy/?igsh=cGs3N3VxaGlhdGJy)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
