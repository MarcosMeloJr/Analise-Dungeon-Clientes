# Projeto de Análise da Empresa de Crédito Dungeon
<div style="display: flex; justify-content: space-between;"> <br>
<img width="1000" alt="netflix" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/atelie-de-costura.jpg">
  
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
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Bases%20Excel%20.png">

 
<br />
 


# Prototipação
A prototipação foi realizada utilizando a ferramenta Figma, permitindo visualizar uma prévia de como ficará a entrega final. Foi utilizado o Adobe Color para extrair o número HEX de cada cor.

#### Protótipo 1
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Prot%C3%B3tipo%20Ateli%C3%AA.png">


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

 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Modelagem.png">
 
 
<br />
  
<br />
 
 
  
# Dashboard Interativo
Com os dados devidamente processados, começamos a elaboração de visualizações com dados estatísticos pertinentes, que servirão como base para responder às questões propostas inicialmente. Foi necessário desenvolver algumas medidas utilizando fórmulas DAX para melhor analisar os dados e extrair insights significativos.

- [Clique aqui para visualizar o dashboard de maneira interativa](https://app.powerbi.com/view?r=eyJrIjoiMmM5NjBhMjUtMzkyMy00ZmVjLWI1ZWEtNDZhZWNhZmQ0NWFkIiwidCI6ImI2ZTUxYmY3LTlmNjItNDM0Ny1hYTk1LTlhYzljMjI2OTFlOCJ9)

<br />
 
![DASHBOARD](https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Dashboard%20Completo.png)





<br />
<br />


# Descobertas e Insights
<img width="1000" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Insights.png">

Terminada a construção visual e realizada acurada análise do material notou-se as seguintes percepções:
- A margem de lucro líquido representou 59% do faturamento da empresa. Uma margem de lucro líquido de 59% é relativamente alta e indica que a empresa está gerando um lucro significativo em relação ao seu faturamento. Isso pode ser considerado um sinal positivo de saúde financeira da empresa.
- O ticket médio foi de R$ 6,11. Um ticket médio baixo pode indicar que os produtos ou serviços da empresa são relativamente acessíveis ou que a empresa pode atender a um grande volume de clientes.
- O produto mais vendido foi a Xuxa representando 84% das vendas realizadas no trimestre.
- Foi identificado o Top 3 Clientes que mais contribuíram para a receita ao longo dos três meses.

 
 <br />
 
 
 
 # Recomendações ao tomador de decisão
Em seguida foram apresentadas algumas alternativas, baseadas nas análises realizadas, que pudessem melhorar as vendas no próximo trimestre:
- Melhor administração do estoque, uma vez que é conhecido os produtos mais populares. Dessa forma agilizaria o tempo de entrega e aumentaria a satisfação dos clientes.
- Possibilidade de ajuste na estratégia de marketing para aumentar a venda dos produtos menos populares;
- Utilizar estratégias de fidelização para os clientes que mais contribuíram (Top 3 Clientes) permanecerem adquirindo produtos.   Ex: Programa de pontos: Eles receberiam pontos a cada compra e trocariam por descontos, produtos gratuitos ou brindes exclusivos.   2) Acesso antecipado a lançamentos de produtos novos. 
- Implementação de um sistema de brindes ou amostras grátis para surpreender e agradar os clientes aumentando assim a preferência pela marca. Altamente recomendado para clientes esporádicos, visando fidelizá-los.


<br />

# BÔNUS - Dica de Ferramenta - Tooltip
- As dicas de ferramentas no Power BI permitem análises dentro de outras análises, conforme mostrado no vídeo abaixo.
 



https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/ToolTip%20Ateli%C3%AA.mp4
