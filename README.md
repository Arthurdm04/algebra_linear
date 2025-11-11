# Sistemas Lineares – Projeto (Notebook)

Este repositório contém um notebook Jupyter com uma introdução prática a sistemas lineares, incluindo:
- Exemplo completo 4x4 com solução única
- Implementação do método de Gauss com pivotamento parcial
- Comparação com `numpy.linalg.solve` e verificação de resíduo
- Análise de posto, determinante e número de condição
- Exemplos de sistema inconsistente (sem solução) e com infinitas soluções

## Como usar
1. Instale o Python 3.9+ e o NumPy:
   - Via pip:
     ```
     pip install numpy
     ```
2. Abra o notebook `sistema_linear.ipynb` em um ambiente compatível (Jupyter, VS Code, Google Colab, etc.).
3. Execute as células na ordem para ver a resolução e as análises.

## Arquivos
- `sistema_linear.ipynb`: Notebook principal com teoria mínima e experimentos.

## Observações
- O método de Gauss implementado utiliza pivotamento parcial para maior estabilidade numérica.
- Exemplos adicionais mostram como classificar sistemas via posto e como lidar com casos sem solução ou com infinitas soluções.