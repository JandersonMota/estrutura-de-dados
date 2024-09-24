# Estrutura de Dados

## Busca Linear

A Busca Linear, também conhecida como busca sequencial, é um algoritmo de pesquisa que examina cada elemento de uma lista ou arranjo sequencialmente até encontrar o valor desejado.

A busca linear é um método simples de implementar, mas pode ser ineficiente para grandes conjuntos de dados, pois requer uma grande quantidade de tempo e recursos para percorrer todos os registros. No entanto, pode ser útil para listas pequenas ou quando os elementos não estão classificados em ordem.

A eficácia da busca linear depende da posição do item desejado. No melhor caso, o elemento é encontrado na primeira tentativa, mas no pior caso, o elemento está na última posição e são feitas N comparações, sendo N o número total de elementos.

A busca binária é um algoritmo de busca mais eficiente, mas requer que a lista esteja ordenada pelos valores da chave de busca.

### 1. Definição e Funcionamento:
- A busca linear (ou sequencial) é um algoritmo simples de pesquisa que percorre todos os elementos de uma lista ou array um por um até encontrar o valor alvo ou até que todos os elementos tenham sido verificados.
- Ideal para pequenos conjuntos de dados ou quando o array não está ordenado.

### 2. Passos do Algoritmo:
- Inicie no primeiro elemento da lista.
- Compare o elemento atual com o valor alvo.
- Se for igual, o elemento foi encontrado, e a busca termina.
- Se não for, avance para o próximo elemento e repita até encontrar o valor ou chegar ao final da lista.

### 3. Complexidade:
- **Melhor caso**: O(1), se o elemento estiver no início da lista.
- **Pior e caso médio**: O(n), onde n é o número de elementos. No pior caso, é necessário percorrer toda a lista.

### 4. Vantagens:
- Simplicidade de implementação.
- Não requer que os dados estejam ordenados.
- Funciona para qualquer tipo de coleção (array, lista ligada, etc.).

### 5. Desvantagens:
- Ineficiente em grandes listas, pois requer uma verificação por elemento.
- A complexidade O(n) é alta comparada com outros algoritmos de busca, como a busca binária.

### 6. Aplicações:
- Usado quando os dados são pequenos ou estão em uma estrutura desordenada.
- Útil em cenários onde a lista de dados é dinâmica e mudanças frequentes ocorrem na estrutura.

### 7. Exemplo:
- Em uma lista de números `[4, 2, 9, 1, 5]`, se você estiver buscando o número 9, o algoritmo começa em 4, depois 2, e continua até chegar ao 9.

### 8. Comparação com a Busca Binária:
- A busca linear não requer que a lista esteja ordenada, enquanto a busca binária sim.
- A busca linear é menos eficiente que a busca binária para grandes conjuntos de dados.

![image](https://github.com/user-attachments/assets/0d8f25f3-217b-41ad-b7f3-f23e391001be)

### Navegar
> <a href="https://github.com/JandersonMota/estrutura-de-dados">Início do repositório.</a>
