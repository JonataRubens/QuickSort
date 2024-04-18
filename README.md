# QuickSort
 

Este é um código em C que implementa o algoritmo de ordenação Quicksort para ordenar um vetor de inteiros.

1. **Função `swap`**:
   - Esta função recebe dois ponteiros para inteiros como parâmetros.
   - Troca os valores apontados pelos ponteiros.

2. **Função `particao`**:
   - Esta função recebe um vetor de inteiros, um índice de início e um índice de fim como parâmetros.
   - Seleciona o último elemento do vetor como pivô.
   - Particiona o vetor de forma que todos os elementos menores que o pivô fiquem à esquerda e todos os elementos maiores fiquem à direita.
   - Retorna o índice do pivô depois da partição.

3. **Função `quick_sort`**:
   - Esta função implementa o algoritmo Quicksort.
   - Usa recursão para ordenar subvetores.
   - Chama a função `particao` para encontrar o índice do pivô e particionar o vetor.
   - Recursivamente ordena os subvetores à esquerda e à direita do pivô.

4. **Função `main`**:
   - Define um vetor de inteiros não ordenado.
   - Calcula o tamanho do vetor.
   - Chama a função `quick_sort` para ordenar o vetor.
   - Imprime o vetor ordenado.

