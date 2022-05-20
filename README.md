# br_financial_bmg
Projeto desenvolvido para solução de problema de classificação.


<p align="center">
  <img width="800" height="500" src="https://user-images.githubusercontent.com/87772120/169603813-8f254444-71c4-4fd6-b49a-9796d8cc06b7.png"
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
  <img width="700" height="60" src="https://user-images.githubusercontent.com/87772120/169604513-5479bc30-839e-4a1f-b120-f2ef124bbe4e.png"
</p> 
 
Conclusão desta analise:
Num problema de classificação, a qualidade dos dados é muito importante, não sçao os tipos de variavéis mas também seu volume.

Solução deste problema:
* Obtenção de maiores informações sobre os usuarios
* Criação de features temporais
* Normalização dos dados
* Balanciamento e reescalonamento dos dados.


**Explicação do modelo MLP - Keras utilizado nessa analise**
  
  # MLP - Modelos de rede neural em Keras

O modelo mais simples é definido na classe Sequential que é uma pilha linear de Layers.

  # Camadas de modelo

Camadas de tipo diferente são algumas propriedades em comum, especificamente seu método de inicialização de peso e funções de ativação.

  ### **Inicialização de peso**

O tipo de inicialização usado para uma camada é especificado no argumento init.

Alguns tipos comuns de inicialização de camada incluem:

- “ *uniforme*
    
    “: Os pesos são inicializados em pequenos valores aleatórios uniformemente entre 0 e 0,05.
    
- “ *normal*
    
    “: Os pesos são inicializados com pequenos valores aleatórios gaussianos (média zero e desvio padrão de 0,05).
    
- “ *zero*
    
    “: Todos os pesos são definidos para valores zero.
  
# Analise Descitiva dos Dados
  
  # Dimensão dos Dados
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169609041-a46b33d1-828d-4ccc-a1ca-b7cb6e9ad0c6.png"
  </p> 
  
  # Detalhe descritivo dos dados
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169609224-8c4d2676-481d-470a-8ba2-ce0d99dda2c7.png"
  </p> 

  # Correlação entre as variaveis categoricas
    
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169609511-57083293-24d7-4740-bed4-72ba77a31926.png"
  </p> 
    
    ## **Percebemos que não existem relações fortes entre os atributos, o que não caracteriza com "BOM" pagador alguem que mora no Estado de São Paulo, por exemplo.**

    

