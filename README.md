# br_financial_bmg
Projeto desenvolvido para solução de problema de classificação.


<p align="center">
  <img width="800" height="500" src="https://user-images.githubusercontent.com/87772120/169603813-8f254444-71c4-4fd6-b49a-9796d8cc06b7.png"
</p> 


# APLICAÇÃO DE TÉCNICAS DE DATA SCIENCE E MACHINE LEARNING EM UM PROBLEMA DE CLASSIFICAÇÃO.
  
Classificar clientes a fim de estabelecer e prever padrões e comportamentos é muito importante para a tomada de decisões de uma empresa e com isso possibilitar a obtenção sempre dos melhores resultados. 

Esse projeto explorou o conceito de análise e ciência de dados ao utilizar machine learning para classificação e definição do comportamento de clientes de uma financeira a fim de apresentar uma direção mais assertiva sobre aprovação de crédito.

A composição do dataset está dividida em 11.994 observações e 19 atributos incluindo os dados sobre o score já conhecido dos clientes. Com isso, a pesquisa focou em desenvolver algoritmos de  machine learning que resolvam o problema de classificação para prever se o cliente irá cumprir com os prazos e pagamentos estabelecidos na proposta de financiamento.

O projeto abordou a análise do dataset, a análise exploratória de dados e plotagem de gráficos para conhecimento das variáveis para aplicação do algoritmo, e implementação dos algoritmos Random e Rede Neural para classificação do comprometimento do cliente.  

Com os resultados obtidos, é sugerido à empresa que se atente às variáveis relacionadas à renda e ao comprometimento da renda dos possíveis clientes, visto que, as análises permitiram observar como principais resultados que, clientes com rendas mais altas tendem a serem melhores pagadores, bem como aqueles que comprometem em até 25% da sua renda com o financiamento, podendo assim gerar clientes mais satisfatórios para a empresa em questão.

<p align="center">
  <img width="700" height="100" src="https://user-images.githubusercontent.com/87772120/169604513-5479bc30-839e-4a1f-b120-f2ef124bbe4e.png"
</p> 
 
  
# Analise Descitiva dos Dados
  
  # Dimensão dos Dados
  <p align="center">
    <img width="500" height="100" src="https://user-images.githubusercontent.com/87772120/169609041-a46b33d1-828d-4ccc-a1ca-b7cb6e9ad0c6.png"
  </p> 
  
  # Detalhe descritivo dos dados
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169609224-8c4d2676-481d-470a-8ba2-ce0d99dda2c7.png"
  </p> 

  # Correlação entre as variaveis categoricas
    
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169609511-57083293-24d7-4740-bed4-72ba77a31926.png"
  </p> 
    
    **É possível observar por meio da correlação de Spearman, que não é significativo a relação entre as variáveis categóricas.**

   # Insights
  <p align="center">
    <img width="1000" height="500" src="https://user-images.githubusercontent.com/87772120/169616382-128fdb5e-62c7-4619-9826-ef167d7197c3.png"
  </p>
    

    **Em relação as variáveis numéricas, é possível observar que clientes com rendas mensais altas são mais propensos a serem bons pagadores quando comparados àqueles com renda menor. Além disso, àqueles clientes que comprometem em até 25% da sua renda mensal, tendem a cumprir com os pagamentos quando comparados àqueles que comprometem um valor superior.**
       
  

 
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

