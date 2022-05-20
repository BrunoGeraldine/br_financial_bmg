# br_financial_bmg
Projeto desenvolvido para solução de problema de classificação.


<p align="center">
  <img width="1000" height="200" src="https://user-images.githubusercontent.com/87772120/169603813-8f254444-71c4-4fd6-b49a-9796d8cc06b7.png"
</p> 


# APLICAÇÃO DE TÉCNICAS DE DATA SCIENCE E MACHINE LEARNING EM UM PROBLEMA DE CLASSIFICAÇÃO.

**O que é classificação de clientes?**
Podemos definir o que é classificação de clientes como o ato de separá-los com base em critérios específicos. Essa formação de grupos é feita baseando-se em características e comportamentos semelhantes, a fim de personalizar as ações de marketing e as abordagens comerciais e de negocios.

Esse projeto explora o conceito de análise de dados com Ciência dos Dados (Data Science) ao utilizar Aprendizado de Máquina (Machine Learning) para resolver o problema de classificação para definição do comportamento de clientes de uma financeira de modo que apresenta um norte sobre aprovação de credito. A composição do dataset está dividida em 11994 observações e 19 atributos incluindo os dados sobre o "score" já conhecido dos clientes. Com isso, a pesquisa foca em desenvolver algoritmos de Aprendizado de Máquina que resolvam o problema de classificação para prever se o cliente irá cumprir com os prazos e pagamentos estabelecidos na proposta de financeiamento. 
Os processos da metodologia incluem analisar o dataset, fazer análise exploratória de dados e plotagem de gráficos para conhecimento de quais variáveis são necessários manter ou retirar para aplicação do algoritmo, implementar os algoritmos Random e Rede Neural para classificação do comprometimento do cliente. 
Como resultados a acurácia foi de 77% para Random e 81% para a Rede Neural MLP. 
Observando mais atentamente esse conjunto de dados, observamos um grande desbalanciamento entre os dados o que impossibilita aplica como metrica a acuracia 
por isso observaremos as metricas Balanced Accuracy e Kappa Score, metricas mais favoraveis quando temos dados desbalanceados.
E como observação na validação do modelo, encontramos valores bem diferentes das primeiras observações.
<p align="center">
  <img width="1000" height="200" src="https://user-images.githubusercontent.com/87772120/169604513-5479bc30-839e-4a1f-b120-f2ef124bbe4e.png"
</p> 
 
Conclusão desta analise:
Num problema de classificação, a qualidade dos dados é muito importante, não sçao os tipos de variavéis mas também seu volume.

Solução deste problema:
* Obtenção de maiores informações sobre os usuarios
* Criação de features temporais
* Normalização dos dados
* Balanciamento e reescalonamento dos dados.



