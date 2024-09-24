# Estrutura de Dados

## Pilha (Stack)

A **Pilha** é uma estrutura de dados linear que segue o princípio **LIFO (Last In, First Out)**, ou seja, o último elemento a entrar na pilha é o primeiro a sair. Uma boa analogia seria uma pilha de pratos, onde o prato colocado por último no topo é o primeiro a ser retirado.

### 1. Definição
A Pilha organiza elementos de forma sequencial, onde as operações de inserção e remoção acontecem na mesma extremidade, chamada de **topo**.

### 2. Operações Básicas
- **Push (inserção):** Adiciona um elemento no topo da pilha.
- **Pop (remoção):** Remove o elemento do topo da pilha.
- **Peek (consulta):** Retorna o elemento no topo da pilha sem removê-lo.
- **IsEmpty:** Verifica se a pilha está vazia.
- **IsFull (em implementações com tamanho fixo):** Verifica se a pilha está cheia.

### 3. Aplicações
- **Funções Recursivas:** O controle da recursão é gerenciado por uma pilha (chamada **pilha de execução**).
- **Conversão de Expressões:** Usada para converter expressões infixas para pós-fixas (notação polonesa reversa).
- **Desfazer/Refazer:** Em editores de texto ou programas que utilizam o conceito de desfazer uma ação.
- **Algoritmos de backtracking:** Usada em algoritmos como a busca em profundidade (DFS).

### 4. Implementação
Pilhas podem ser implementadas de duas maneiras principais:
- **Usando arrays:** A pilha tem um tamanho fixo, e o topo da pilha é controlado por um ponteiro.
- **Usando listas ligadas (linked list):** Não há limitação de tamanho, já que os nós podem ser dinamicamente alocados.

### 5. Complexidade
- **Push e Pop:** O(1) — Operações constantes, independentemente do tamanho da pilha.
- **Peek:** O(1) — Consulta constante do elemento no topo.

### 6. Exemplo de Funcionamento
Para uma pilha com elementos `[5, 3, 7]`:
1. `Push(9)` → `[5, 3, 7, 9]`
2. `Pop()` → `[5, 3, 7]` (Elemento 9 removido)
3. `Peek()` → `7` (o elemento do topo).

### 7. Tipos de Pilhas
- **Pilha Estática:** Tamanho fixo e pré-determinado, geralmente implementada com arrays.
- **Pilha Dinâmica:** Tamanho variável, geralmente implementada com listas ligadas.

### 8. Resumo
A Pilha é uma estrutura de dados eficiente e simples, utilizada em uma ampla variedade de aplicações que requerem acesso ordenado ao último elemento inserido.

<img src="https://i0.wp.com/terminaldeinformacao.com/wp-content/uploads/2013/07/pilha-lifo-1.png">

### Para mais informações:
[Para aprender mais](https://www.instagram.com/reel/Cv9ubjuASER/?igsh=MTd5b2RpNWN6cDgzdg==)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
