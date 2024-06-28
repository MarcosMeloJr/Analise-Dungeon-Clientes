# Projeto de Análise da Empresa de Crédito Dungeon
<div style="display: flex; justify-content: space-between;"> <br>
<img width="1000" alt="netflix" src="https://github.com/MarcosMeloJr/Analise-Dungeon-Clientes/blob/main/Capa.jpeg">
  
# Sobre o Projeto:
- O objetivo primário deste projeto é desenvolver um painel que demonstre o cenário e o perfil dos associados que possuem conta na Cooperativa Dungeon. Utilizando uma base fictícia de dados, o painel fornecerá informações detalhadas sobre agência, carteira e conta dos associados, além de segmentá-los em PF (Pessoa Física), PJ (Pessoa Jurídica) e Agro.
- Este painel será uma ferramenta essencial para as equipes da cooperativa, auxiliando nas tomadas de decisões estratégicas para aumentar o volume de associados. Através da análise detalhada dessas informações, espera-se identificar insights valiosos que contribuirão para a captação e retenção de membros, além de proporcionar uma visão clara do perfil e comportamento financeiro dos associados.
<br />

# Etapas do Projeto (DataOps)
- Perguntas de negócio;
- Mapeamento dos dados;
- Prototipação;
- ETL (Extração, Transformação e Carregamento);
- Descobertas e insights;
- Sugestões de decisão.

<br />

# Perguntas de Negócio
Com o objetivo de fornecer um quadro geral dos insights a partir dos dados fornecidos, foi decidido que deveriam ser respondidas as seguintes perguntas: 
 
- Quantos associados há na carteira de clientes?
- Qual o valor total investido, de crédito tomado e de consórcios feito? (Adicione filtros para analisar por área)
- Mostre se houve evolução na aquisição dos clientes?
- Quantos clientes estão ativos e quantos usam PIX?

  Respondidas essas perguntas, as respostas fornecerão um quadro geral do cenário atual e do comportamento dos nossos associados, permitindo uma compreensão mais aprofundada de suas necessidades e padrões de movimentação financeira.


<br />

# Mapeamento dos Dados
- Os dados foram planilhados e estruturados no Excel.
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Analise-Dungeon-Clientes/blob/main/Base%20Original.jpeg">

 
<br />
 


# Prototipação
A prototipação foi realizada utilizando a ferramenta Figma, permitindo visualizar uma prévia de como ficará a entrega final. Foi utilizado o Adobe Color para extrair o número HEX de cada cor.

#### Protótipo 1
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Analise-Dungeon-Clientes/blob/main/Dungeon.png">


# ETL (Extração, Transformação e Carregamento)
### Preparação dos dados
- 	Extração da base fornecida para o Power Query;
-   Limpeza de dados inconsistentes;
-   Coluna Investimentos: Subst. Valores: Hífen por “vazio”;
-   Mudança dos tipos de coluna: Data e Hora para Data, Texto para Número Decimal Fixo;
-   Arredondamento das casas decimais (2 casas);
-   Substituição de valores textuais para melhor leitura;
-   Alteração da nomenclatura dos cabeçalhos;
-   Carregamento dos dados limpos para o Power BI.

 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Analise-Dungeon-Clientes/blob/main/Base%20Formatada.jpeg">
 
 
<br />
  
<br />
 
 
  
# Dashboard Interativo
Com os dados devidamente processados, começamos a elaboração de visualizações com dados estatísticos pertinentes, que servirão como base para responder às questões propostas inicialmente. Foi necessário desenvolver algumas medidas utilizando fórmulas DAX para melhor analisar os dados e extrair insights significativos.

- [Clique aqui para visualizar o dashboard de maneira interativa](https://app.powerbi.com/view?r=eyJrIjoiODY4NWJlNjItMThjYy00MDNjLTg0ZGItZmE0ZTkxMzI1YmIzIiwidCI6ImI2ZTUxYmY3LTlmNjItNDM0Ny1hYTk1LTlhYzljMjI2OTFlOCJ9)

<br />
 
![DASHBOARD](https://github.com/MarcosMeloJr/Analise-Dungeon-Clientes/blob/main/Dashboard.png)





<br />
<br />


# Descobertas e Insights
<img width="1000" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Insights.png">

Após a finalização do dashboard e a realização de uma análise minuciosa do material, foram observados os seguintes insights:
-A cooperativa possui um total de 17.155 associados, mostrando um tamanho de base significativo.
- Houve um aumento considerável no número de associados adquiridos desde 2016 até 2021.
- 70% dos clientes estão ativos, movimentando suas contas nos últimos 180 dias, o que reflete uma base de associados engajada.
- 90% dos associados possuem contas com Pix, mostrando uma alta adoção de tecnologias de pagamento modernas.]
- Menos de 1% dos associados não são correntistas, indicando que a maioria dos associados utiliza os serviços bancários oferecidos pela cooperativa.

 
 <br />
 
 
 
 # Recomendações ao tomador de decisão
Com base nos insights alcançados, algumas alternativas foram propostas aos dirigentes para que a empresa possa aprimorar seus resultados:
- Aumentar a Captação de Crédito: Incentivar os associados a utilizarem mais as linhas de crédito disponíveis, oferecendo condições atrativas e campanhas de conscientização sobre as vantagens de tomar crédito na cooperativa;
- Expandir o Uso do Pix: Aproveitar a alta adoção do Pix para oferecer novos serviços e facilidades. Programas de cashback ou descontos em transferências seriam interessantes para aumentar a fidelização dos associados;
- Engajar Associados Inativos: Implementar programas de reativação para os 30% de associados que não estão ativos. Oferecer benefícios exclusivos ou facilidades para motivá-los a movimentar suas contas novamente;
- Investigar o Crescimento na Adesão: Manter e intensificar as estratégias que levaram ao aumento considerável de associados entre 2016 e 2021. Isso pode incluir campanhas de marketing direcionadas, programas de indicação e a melhoria contínua dos serviços oferecidos.


<br />

# BÔNUS - Dica de Ferramenta - Tooltip
- As dicas de ferramentas no Power BI permitem análises dentro de outras análises, conforme mostrado no vídeo abaixo.
 



https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/ToolTip%20Ateli%C3%AA.mp4
