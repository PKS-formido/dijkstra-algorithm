# dijkstra-algorithm
Menor caminho de um nó para outro usando algoritmo dijkstra

# Algoritmo de Dijkstra para Encontrar o Menor Caminho em um Grafo

O algoritmo de Dijkstra é um método eficiente para encontrar o menor caminho entre dois nós em um grafo ponderado. Ele funciona bem para grafos com pesos não negativos.

## Funcionamento do Algoritmo

1. **Inicialização**: Defina a distância do nó de origem como 0 e as distâncias de todos os outros nós como infinito. Marque o nó de origem como "visitado".

2. **Seleção do Nó**: Escolha o nó não visitado com a menor distância calculada até o momento.

3. **Exploração das Adjacências**: Para cada nó adjacente não visitado ao nó atual, calcule a distância total passando pelo nó atual. Se essa distância for menor do que a distância registrada para o nó adjacente, atualize-a.

4. **Marcação como Visitado**: Após explorar todos os nós adjacentes, marque o nó atual como visitado.

5. **Repetição**: Repita os passos 2 a 4 até que todos os nós tenham sido visitados.
