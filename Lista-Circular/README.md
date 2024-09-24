# Estrutura de Dados

## Lista Circular

A **Lista Circular** é uma variação da lista ligada em que o último elemento aponta para o primeiro, formando um ciclo. Isso permite que a lista seja percorrida de forma contínua, sem a necessidade de chegar a um final.

### 1. Definição
Uma **Lista Circular** é uma lista onde:
- Cada elemento (ou nó) contém um valor e uma referência (ponteiro) para o próximo nó.
- O último nó da lista aponta de volta para o primeiro nó, formando um ciclo.

### 2. Tipos de Lista Circular
- **Lista Circular Simples:** Cada nó tem apenas um ponteiro para o próximo elemento, e o último nó aponta para o primeiro.
- **Lista Circular Duplamente Ligada:** Cada nó possui dois ponteiros, um para o próximo nó e outro para o anterior. O último nó aponta para o primeiro, e o primeiro aponta para o último.

### 3. Operações Básicas
- **Inserção:** Um novo nó pode ser inserido em qualquer posição da lista, ajustando os ponteiros para manter o ciclo.
- **Remoção:** O nó removido tem seus ponteiros ajustados para que o ciclo seja mantido, conectando o nó anterior ao próximo.
- **Percorrimento:** Pode-se começar de qualquer ponto da lista e continuar indefinidamente, já que ela não possui fim.

### 4. Vantagens
- **Ciclo contínuo:** Como não há um fim na lista, você pode percorrê-la continuamente, útil para aplicações que precisam de repetição cíclica.
- **Eficiência na navegação:** Ao contrário de listas lineares, você pode retornar ao início da lista sem precisar percorrê-la completamente.

### 5. Desvantagens
- **Complexidade:** Manter a referência cíclica correta pode tornar a implementação mais complexa, especialmente em operações de inserção e remoção.
- **Sobrecarga de memória:** Em listas circulares duplamente ligadas, há um custo adicional de memória devido à necessidade de dois ponteiros por nó (anterior e próximo).

### 6. Aplicações
- **Sistemas operacionais:** Usada em algoritmos de escalonamento circular (round-robin) para gerenciar processos em tempo compartilhado.
- **Jogos ou simulações:** Útil para representar jogadores ou entidades que agem repetidamente em um ciclo.
- **Buffer circular:** Usado para armazenar dados em buffers circulares, onde o início e o fim estão conectados.

### 7. Exemplo de Funcionamento
Em uma **Lista Circular Simples** com os elementos `A -> B -> C -> A`:
- O elemento `C` aponta de volta para o elemento `A`, formando um ciclo.
- Se o elemento `B` for removido, o ponteiro de `A` será ajustado para apontar diretamente para `C`.

### 8. Complexidade
- **Inserção e Remoção:** O(1) — Se você tiver o ponteiro para o nó onde a operação deve ocorrer, pode ajustar os ponteiros diretamente.
- **Percorrimento:** O(n) — Para percorrer a lista, é necessário visitar cada nó, assim como em uma lista ligada comum.

### 9. Comparação com Outras Estruturas
- Em comparação com a **Lista Simplesmente Ligada**, a Lista Circular permite um percorrimento contínuo, mas é mais complexa de implementar.
- Em comparação com a **Lista Duplamente Ligada**, a versão circular adiciona a característica de ciclo, mas com o mesmo custo de ponteiros duplos.

### 10. Resumo
A **Lista Circular** é uma estrutura poderosa para situações que exigem percorrimento contínuo, sendo útil em aplicações de sistemas operacionais, buffers e simulações que necessitam de repetição cíclica.

![image](https://github.com/user-attachments/assets/8815db98-9d65-481c-aa7e-0ff140402e21)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
