# Dashboard de Performance de Marketing

## 📌 Contexto do Projeto
Este projeto apresenta uma solução completa de Business Intelligence para a área de Marketing. Utilizando dados de campanhas digitais, o dashboard foi estruturado em **4 visões estratégicas**, permitindo que diferentes níveis da empresa (do operacional ao executivo) tomem decisões baseadas em dados.

## 📊 Estrutura do Dashboard (As 4 Visões)
O projeto foi dividido para responder a necessidades específicas de análise:

1.  **Visão do Cliente**: Destinada ao entendimento profundo do público-alvo, esta visão segmenta os consumidores por escolaridade, estado civil e nível de renda. O objetivo é identificar o perfil do cliente ideal para direcionar estratégias de marketing mais personalizada.
2.  **Visão de Comportamento de Compra do Cliente**: Desenvolvida para analisar padrões de consumo e correlações, esta visão explora a relação entre idade, renda e intenção de compra, além de monitorar a taxa de retorno dos cliente. É essencial para entender os gatilhos que levam à conversão e fidelização.
3.  **Visão de Performance das Campanhas de Marketing**: Focada no monitoramento da saúde financeira e comercial, esta visão apresenta KPIs críticos como Receita Total, Total de Pedidos e Ticket Médio. Ela permite identificar rapidamente as tendências de faturamento ao longo do tempo e os produtos que lideram o volume de vendas.
4.  **Visão dos Padrões de Compra no Ponto de Venda**: Voltada para a análise de desempenho geográfico e por unidade de negócio, esta página detalha o faturamento por loja e por país. Ela ajuda a gestão a entender quais localidades necessitam de mais atenção ou investimentos em infraestrutura.

# Detalhe Técnico #
Para garantir a interatividade e a precisão das visões, utilizei **DAX** para criar medidas dinâmicas e o **Power Query** para a normalização dos dados, tratando valores nulos e padronizando as categorias demográficas presentes no dataset original.

## 🛠️ Problema de Negócio
O objetivo é solucionar a fragmentação dos dados de marketing. Antes deste dashboard, não era possível:
* Cruzar o custo de diferentes plataformas em uma única visão.
* Identificar rapidamente quais campanhas estavam com ROI negativo.
* Entender a jornada do funil (Impressões -> Cliques -> Conversões) de forma visual e intuitiva.

## ⚙️ Tecnologias e Dados
* **Ferramenta**: Power BI Desktop.
* **Processamento (ETL)**: Limpeza e padronização de moedas e datas via Power Query.
* **Dataset**: Base de dados contendo `id_campanha`, `plataforma`, `cliques`, `impressoes`, `custo`, `conversoes` e `receita`.

## 💡 Insights Estratégicos Extraídos
* **Otimização de Verba**: Identificação de plataformas com baixo CPC, mas alta conversão.
* **Escalabilidade**: Detecção de campanhas de alta performance prontas para receber maior investimento.
* **Sazonalidade**: Análise do comportamento das vendas ao longo do período filtrado.

## 📷 Visualização do Projeto
![Visão do Cliente](images/visao_cliente.png)
![Visão do Comportamento de Compra do Cliente](images/visao_comportamento.png)
![Visão da Performance das Campanhas de Marketing](images/visao_performance.png)
![Visão dos Padrões de Compra no Ponto de Venda](images/visao_pontos_venda.png)

## 📂 Como acessar o projeto
1. Baixe o arquivo `Analise_Performance_Marketing.pbix` deste repositório.
2. Certifique-se de ter o **Microsoft Power BI Desktop** instalado.
3. Os dados brutos podem ser consultados na pasta `/data`.

## 📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
