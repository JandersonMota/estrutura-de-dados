# Estrutura de Dados

## Insertion Sort

O **Insertion Sort** é um algoritmo de ordenação simples e eficiente para pequenas quantidades de dados. Ele é baseado na ideia de construir gradualmente uma sequência ordenada, inserindo elementos em suas posições corretas, uma de cada vez. 

### Pontos importantes:

1. **Definição e Funcionamento**:
   - O Insertion Sort percorre o array, inserindo cada elemento na posição correta em relação aos elementos anteriores, que já estão ordenados.
   - Funciona de maneira semelhante à forma como organizamos cartas em uma mão: pegamos uma carta e a colocamos na posição correta entre as já ordenadas.

2. **Passos do Algoritmo**:
   - Comece com o segundo elemento (índice 1).
   - Compare-o com os elementos anteriores.
   - Desloque os elementos maiores para a direita e insira o elemento na posição correta.
   - Repita até que todos os elementos estejam ordenados.

3. **Complexidade**:
   - **Melhor caso**: O(n), quando a lista já está ordenada.
   - **Pior e caso médio**: O(n²), quando os elementos estão na ordem inversa ou misturados.
   - É considerado ineficiente para grandes listas devido à complexidade quadrática.

4. **Vantagens**:
   - Simples de implementar.
   - Funciona bem para listas pequenas.
   - Estável, ou seja, mantém a ordem relativa dos elementos iguais.
   - Bom para dados quase ordenados, pois o número de comparações e trocas será reduzido.

5. **Desvantagens**:
   - Ineficiente em listas grandes devido à complexidade quadrática no pior caso.
   - Não é adequado para ordenações que envolvem muitos dados desordenados.

6. **Aplicações**:
   - Usado quando o conjunto de dados é pequeno ou quase ordenado.
   - Também pode ser usado como parte de algoritmos mais avançados, como o **Timsort**, que combina o Insertion Sort e o Merge Sort.

7. **Exemplo**:
   Para ordenar o array `[7, 4, 5, 2]`:
   1. O elemento 4 é comparado com 7, e os dois trocam de lugar: `[4, 7, 5, 2]`.
   2. O elemento 5 é comparado com 7 e inserido antes dele: `[4, 5, 7, 2]`.
   3. O elemento 2 é comparado com todos os elementos e inserido no início: `[2, 4, 5, 7]`.

8. **Comparação com outros algoritmos**:
   - Mais simples, porém menos eficiente que o **Merge Sort** ou **Quicksort** para grandes dados.
   - Em pequenas listas ou quase ordenadas, pode ser mais eficiente que o **Selection Sort** e o **Bubble Sort**.

![Exemplo do funcionamento do Insertion Sort](https://miro.medium.com/v2/resize:fit:720/format:webp/1*OwXl0acSOQWPTsikNPtdqw.png)
