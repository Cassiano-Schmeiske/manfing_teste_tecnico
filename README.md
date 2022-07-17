# manfing_teste_tecnico
<div align="center">
<img src="https://user-images.githubusercontent.com/94291995/179351991-b7f071fb-247b-44d1-a7cb-aa77ace53870.jpg" />
</div>

Online Retail II: Loja de vendas online sediada no Reino Unido.

Com a necessidade de aumentar o faturamento das vendas online, a Tarefa desenvolvida nesse projeto foi análisar o comportamento dos clientes e desenvolver um sistema de recomendação. O Algoritmo sugeri combinação de produtos dentro das cestas de compras dos clientes analisados. Através dessas informações pode-se criar Campanhas e Técnicas de Vendas: Cross Selling / Descontos.

Clustering foi Selecionado os clientes mais valiosos para formar o programa de fidelidade.

## Business Assumptions:
As seguintes suposições foram feitas sobre o problema de negócio:
- Colunas com dados NA foram removidas
- Só foram consideradas entradas em que o valores de **Price** fossem superiores a 0.
- Os dados de Customers com comportamento fora do padrão foi descartado -> Outlier

## Descrições das Variáveis:
    • InvoiceNo: Invoice Number -> operação 
    • ItemName: Nome do produto
    • Quantidade: Quantidade de produtos -> quantos produtos das faturas foram vendidos.
    • Data da fatura
    • Preço unitário
    • CustomerID: número de cliente exclusivo
    • País

## Machine learning modeling:

- Recommender system: Apriori
- Clustering: K-Means 

## Demonstração do Sistema de Recomendação:
<div align="">
<img src="https://user-images.githubusercontent.com/94291995/179338837-8a19b9c2-edf6-4811-a598-b8847231c926.png" />
</div>
