# PROBLEMA DE NEGOCIO

A "FlyTech Aeronáutica" é uma empresa fictícia atuante no setor de aviação regional, especializada em fabricar aeronaves leves para transporte executivo e comercial. A empresa oferece aeronaves com foco em eficiência, segurança e inovação tecnológica, atendendo principalmente pequenas e médias empresas, executivos, companhias aéreas regionais e serviços de táxi aéreo na América Latina.
A FlyTech possui forte posicionamento no mercado regional, reconhecida por seus produtos com ótimo custo-benefício e qualidade técnica avançada. Contudo, enfrenta forte concorrência internacional e desafios relacionados à retenção de clientes e manutenção de receita constante.

# PREMISSAS DA ANÁLISE

Para realizar sua análise, você terá acesso aos seguintes dados:

Histórico de Vendas Mensais (últimos 3 anos): vendas detalhadas por modelo de aeronave, quantidade vendida, preço, descontos aplicados e receita total.
Dados Demográficos dos Clientes: setor de atuação, localização geográfica, porte da empresa, número de funcionários e tempo de relacionamento com a FlyTech.
Histórico de Compras: frequência das compras, modelos adquiridos anteriormente, intervalos entre compras.
Feedbacks dos Clientes: avaliações qualitativas e quantitativas.
Dados de Campanhas de Marketing: investimentos mensais em campanhas, canais utilizados, taxas de conversão e retorno sobre investimento.

# CONTEXTO

Nos últimos 12 meses, a FlyTech identificou uma queda significativa nas vendas do modelo "FT-50 Executive", sua principal aeronave destinada ao público executivo, representando 35% da receita anual da empresa. Paralelamente, houve um aumento da taxa de churn de clientes corporativos que anteriormente demonstraram alta fidelidade à marca.
A liderança acredita que entender as causas por trás desses dois fenômenos e antecipar comportamentos futuros dos clientes permitirá desenvolver estratégias efetivas para recuperar vendas e fidelizar clientes existentes.

# ESTRATEGIA DA SOLUÇAO

#### Passo 1: Explorar o histórico de vendas, identificando padrões, tendências e correlações.
#### Passo 2: Crie dashboards no Power BI que apresentam visualmente os principais indicadores relacionados às vendas, churn e perfil dos clientes.
#### Passo 3: Construir uma tabela calendário para analises temporais
#### Passo 4: Identificar possíveis causas para a queda nas vendas do modelo "FT-50 Executive" e para o aumento na taxa de churn.
#### Passo 5: Utilizar análises qualitativas dos feedbacks dos clientes e correlações com dados quantitativos de vendas e marketing para embasar as hipóteses.


# HIPOTESES ANALISADAS
### 1. Queda nas vendas:
 - caiu porque os clientes único diminuiu
 - caiu porque o preço aumentou
 - caiu porque a % de desconto diminuiu
 - as empresas optaram por outro modelos
 - ouve um baixo investimento de marketing

### 2. Aumento de Churn:
 - clientes com menos tempo de fidelização tem mais chances de entrar em churn
 - clientes com menos tempo de fidelização avaliaram com uma nota mais baixa
 - aumentou o número de avaliações ruins 
 - empresas de porte grande teve um maior churn
 - empresas do setor da saúde teve um maior churn
 - empresas da colômbia teve maior churn

#### INSIGTHS DA ANALISE

Após uma análise diagnóstica foi identificado uma forte correlação (próxima de 1)  entre desconto, clientes únicos e unidades vendidas, mostrando uma fragilidade da empresa pois, depende fortemente de novos clientes entrando todos os meses para aumentar o faturamento, e que só é possível vender para os mesmo clientes se der desconto.

Com o marketing próximo de zero ou negativo, indica uma estagnação que pode ser pelo baixo investimento ou campanhas que não estão sendo direcionada de forma assertiva para atrair clientes.

O mesmo vale para a avaliação média da empresa, pois é um indicador relevante que mostra a fragilidade em manter os clientes.
**Prints**

Com queda no investimento em marketing os seguintes indicadores, Faturamento, Clientes únicos e taxa de Conversão tendem a ter um decréscimo 
**Prints**

O modelo FT-50 Executive em comparação ao ano passado teve um crescimento de 8% em quantidade vendida, entretanto o modelo FT-100 Commercial teve queda -22,64% e um aumento no seu preço de 4,52%.
**Prints**

O maior motivo da queda de quantidades vendidas do FT-100 Commercial foi os setores saúde e transporte que diminuíram quase pela metade a quantidade comprada em relação ao ano passado
**Prints**

A empresa teve uma queda na avaliação media em relação ao ano passado, onde é possível ver também uma aumento nas avaliações "muito ruim" e "ruim"
**Prints**
**Prints**

A maioria dos clientes que entraram em churn e que avaliaram com uma nota baixa, e tem em comum o tempo de relacionamento de 5 meses 
**Prints**

A quantidade de churn veio a maior parte de empresas de pequeno porte dos setores Financeiro, Transporte e Saúde nos Países, Brasil, Colômbia e Peru  
**Prints**

# RESULTADO/ RECOMENDAÇÃO
A empresa se mostrou frágil em relação a vender para os mesmos clientes pois, refém dos descontos, a baixa avaliação e os números de churns, a empresa depende fortemente do investimento em campanhas de marketing  mais direcionadas e assertivas para trazer novos clientes.

Há análise mostrou também que o modelo de aero nave que teve decaimento nas vendas foi a FT-100 Commercial nos últimos 12 meses com queda de -22,64%, pois os setores de saúde e transporte que é o principal cliente desse modelo compraram menos em relação ao ano passado. Enquanto o principal modelo da empresa fechou o ano com crescimento de 8%

Seria interessante aumentar a quantidade de investimento em marketing para atrair novos clientes nos próximos meses para aumentar o faturamento, e em paralelo a isso entender junto aos clientes e o time de vendas o motivo das avaliações negativas, se é dos produtos ou do atendimento e coletar essas informações pois, não temos informações detalhadas sobre oque causou o aumento do churn, mas a maior quantidade se concentra em clientes com 5 meses de relacionamento assim como a quantidade de avaliações "ruim" e "muito ruim". 
Outra observação é a média da empresa que caiu em relação ao ano passado.


# VISUALISE A ANALISE COMPLETA
https://app.powerbi.com/reportEmbed?reportId=338bab51-2a30-4d6d-8b3c-853327c01fd5&autoAuth=true&ctid=58674b1f-122e-4f0b-989f-a1e1d8191402


# Próximos Passos
 - Coletar a data que os clientes entraram em churn e comparar com a data dos feedbacks para encontrar um padrão/tendência
 - Analisar as informações coletadas pelo time de vendas e criar gráficos para visualizar os pontos de melhorias em relação as avaliações
