# Estrutura de Dados

## Assuntos abordados

### Algoritmos vs Estruturas de Dados
  - **Algoritmos** são métodos ou procedimentos para resolver problemas (neste caso, de busca ou ordenação).
  - **Estruturas de Dados** são maneiras de organizar e armazenar dados em memória.

### O que é cota superior? (notação O)
É a complexidade de um algoritmo já conhecido para resolver um problema. É semelhante a um recorde mundial, que é estabelecido pelo melhor atleta do momento. Assim como um recorde, a cota superior pode ser melhorada por um algoritmo mais rápido.

### O que é cota inferior? (notação assintótica Ω)
A complexidade da cota inferior, ou lower bound, é uma característica de um problema e não de um algoritmo específico. Ela é uma cota inferior trivial, ou seja, um tempo mínimo que o problema exige, independentemente do algoritmo.

### 1. **Estruturas de Dados Básicas (inicie por aqui para entender as bases)**
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Fila">Fila (Queque)</a>
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Pilha">Pilha (Stack)</a>
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Lista-Circular">Lista Circular</a>

### 2. **Algoritmos de Busca**
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Busca-Linear">Busca Linear</a>
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Busca-Binaria">Busca Binária</a>
    - Criado por John Mauchly em 1946.

### 3. **Algoritmos de Ordenação Simples**
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Insertion-Sort">Insertion Sort</a>
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Selection-Sort">Selection Sort</a>

### 4. **Algoritmos de Ordenação Mais Avançados**
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Merge-Sort">Merge Sort</a>
    - Criado por John Von Neumann em 1945.
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/tree/main/Quicksort">Quicksort</a>
    - Criado por C.A.R. Hoare em 1960.
  - <a href="https://github.com/JandersonMota/estrutura-de-dados/blob/main/Heapsort">Heapsort ou Árvore Binária</a>
    - Criado por J. W. J. Williams em 1964 e aprimorado por Robert W. Floyd.

### 5. **Árvores e Estruturas de Dados Avançadas**
  - Árvore
  - Árvore AVL
  - Árvore rubro-negra
  - B-Tree

## Níveis de Complexidade de Algoritmos

Os níveis de complexidade de tempo de algoritmos são usados para descrever o crescimento do tempo de execução de um algoritmo em função do tamanho da entrada (n). Aqui estão os principais níveis de complexidade, do menor (mais eficiente) ao maior (menos eficiente):

### 1. **O(1) - Constante**
- **Descrição**: O tempo de execução não muda com o aumento do tamanho da entrada. O algoritmo executa em um tempo fixo, independentemente de quantos elementos existam.
- **Exemplo**: Acesso direto a um elemento de um array.

### 2. **O(log n) - Logarítmica**
- **Descrição**: O tempo de execução cresce logaritmicamente em relação ao tamanho da entrada. O aumento do tempo de execução é pequeno à medida que o tamanho da entrada aumenta.
- **Exemplo**: Busca Binária.

### 3. **O(n) - Linear**
- **Descrição**: O tempo de execução cresce proporcionalmente ao tamanho da entrada. Se a entrada dobra, o tempo de execução também dobra.
- **Exemplo**: Busca Linear.

### 4. **O(n log n) - Linear Logarítmica**
- **Descrição**: O tempo de execução cresce mais rápido do que linear, mas mais lentamente que quadrático. É o nível de complexidade de muitos algoritmos eficientes de ordenação.
- **Exemplo**: Merge Sort, Quicksort (caso médio).

### 5. **O(n²) - Quadrática**
- **Descrição**: O tempo de execução cresce proporcionalmente ao quadrado do tamanho da entrada. É comum em algoritmos que têm dois loops aninhados.
- **Exemplo**: Insertion Sort, Selection Sort.

### 6. **O(n³) - Cúbica**
- **Descrição**: O tempo de execução cresce proporcionalmente ao cubo do tamanho da entrada. Algoritmos com três loops aninhados costumam ter essa complexidade.
- **Exemplo**: Algoritmos que envolvem operações em todas as combinações de três elementos.

### 7. **O(2ⁿ) - Exponencial**
- **Descrição**: O tempo de execução dobra a cada novo elemento na entrada. Algoritmos exponenciais tornam-se impraticáveis muito rapidamente à medida que o tamanho da entrada cresce.
- **Exemplo**: Algoritmos de força bruta para resolver o problema do Caixeiro Viajante.

### 8. **O(n!) - Fatorial**
- **Descrição**: O tempo de execução cresce fatorialmente com o tamanho da entrada. Algoritmos com essa complexidade são extremamente ineficientes para entradas grandes.
- **Exemplo**: Permutações de todos os elementos.

## Complexidade
Essa tabela resume a complexidade de tempo dos algoritmos e estruturas de dados nos três casos (melhor, médio e pior).
| Algoritmo/Estrutura    | Melhor Caso      | Caso Médio      | Pior Caso        |
|------------------------|------------------|-----------------|------------------|
| Fila (Queue)           | O(1)             | O(1)            | O(1)             |
| Pilha (Stack)          | O(1)             | O(1)            | O(1)             |
| Lista Circular         | O(1) (inserção)  | O(n) (busca)    | O(n) (busca)     |
| Busca Linear           | O(1)             | O(n)            | O(n)             |
| Busca Binária          | O(1)             | O(log n)        | O(log n)         |
| Insertion Sort         | O(n)             | O(n²)           | O(n²)            |
| Selection Sort         | O(n²)            | O(n²)           | O(n²)            |
| Merge Sort             | O(n log n)       | O(n log n)      | O(n log n)       |
| Quicksort              | O(n log n)       | O(n log n)      | O(n²)            |
| Heapsort               | O(n log n)       | O(n log n)      | O(n log n)       |
| Árvore (Busca)         | O(log n)         | O(log n)        | O(n)             |
| Árvore AVL             | O(log n)         | O(log n)        | O(log n)         |
| Árvore Rubro-Negra     | O(log n)         | O(log n)        | O(log n)         |
| B-Tree                 | O(log n)         | O(log n)        | O(log n)         |

---

## Resumo Visual
Aqui está um gráfico para entender a velocidade de crescimento dos diferentes níveis de complexidade:

- O(1) → Constante
- O(log n) → Logarítmico
- O(n) → Linear
- O(n log n) → Linear Logarítmico
- O(n²) → Quadrático
- O(2ⁿ) → Exponencial
- O(n!) → Fatorial

À medida que subimos na escala, os algoritmos se tornam mais lentos para entradas maiores.

## Para mais informações:
[Para aprender mais](https://www.ime.usp.br/~pf/algoritmos/index.html)
