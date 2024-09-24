# Estrutura de Dados

## Fila (Queue)

A **Fila** é uma estrutura de dados linear que segue o princípio **FIFO (First In, First Out)**, ou seja, o primeiro elemento a entrar na fila é o primeiro a sair. É semelhante à ideia de uma fila de pessoas em uma fila de espera.

### 1. Definição
A Fila organiza elementos de forma sequencial, permitindo que os elementos sejam adicionados no final e removidos no início.

### 2. Operações Básicas
- **Enqueue (inserção):** Adiciona um elemento ao final da fila.
- **Dequeue (remoção):** Remove o elemento no início da fila.
- **Front (início):** Retorna o elemento no início da fila sem removê-lo.
- **IsEmpty:** Verifica se a fila está vazia.
- **IsFull (em implementações com tamanho fixo):** Verifica se a fila está cheia.

### 3. Aplicações
- **Gerenciamento de recursos:** Fila de impressão, processamento de tarefas em sistemas operacionais.
- **Sistemas de espera:** Atendimento em supermercados, serviços de chamadas.
- **Redes:** Transmissão de pacotes de dados.
- **Algoritmos:** Algoritmos de busca em largura (BFS) usam filas.

### 4. Implementação
Filas podem ser implementadas de várias maneiras:
- **Usando arrays:** A fila tem tamanho fixo e, quando o espaço se esgota, pode ser implementada com movimentação dos elementos.
- **Usando listas ligadas (linked list):** Não há limitação de tamanho, já que os nós podem ser dinamicamente alocados.

### 5. Complexidade
- **Enqueue e Dequeue:** O(1) — Operações constantes, independentemente do tamanho da fila.
- **Consulta (Front e Rear):** O(1).

### 6. Tipos de Filas
- **Fila Simples:** Operações de entrada e saída ocorrem em extremidades opostas.
- **Fila Circular:** Implementa uma fila contínua, reaproveitando o espaço de elementos removidos.
- **Fila Dupla (Deque):** Permite inserção e remoção em ambas as extremidades.
- **Fila de Prioridade:** Cada elemento tem uma prioridade, e o deque ocorre com base na prioridade em vez da ordem de chegada.

### 7. Exemplo de Funcionamento
Para uma fila com elementos `[2, 4, 6]`:
1. `Enqueue(8)` → `[2, 4, 6, 8]`
2. `Dequeue()` → `[4, 6, 8]` (Elemento 2 removido)
3. `Front()` → `4` (o elemento da frente).

### 8. Resumo
A fila é uma estrutura simples, mas eficiente, usada em diversos cenários onde é importante processar os elementos na ordem de chegada.

<img src="https://media.dev.to/cdn-cgi/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F72rf63kl16fl20ktx548.png">

### Para mais informações:
[Para aprender mais](https://www.instagram.com/reel/Cv9ubjuASER/?igsh=MTd5b2RpNWN6cDgzdg==)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
