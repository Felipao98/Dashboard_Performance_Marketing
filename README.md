# Dashboard de Performance de Marketing

## 📌 Contexto do Projeto
Este projeto apresenta uma solução completa de Business Intelligence para a área de Marketing. [cite_start]Utilizando dados de campanhas digitais, o dashboard foi estruturado em **4 visões estratégicas**, permitindo que diferentes níveis da empresa (do operacional ao executivo) tomem decisões baseadas em dados.

## 📊 Estrutura do Dashboard (As 4 Visões)
O projeto foi dividido para responder a necessidades específicas de análise:

1.  [cite_start]**Visão Geral (Performance Global)**: Monitoramento dos KPIs principais (Receita Total, ROI Médio e Conversões) para uma leitura rápida da saúde do marketing.
2.  [cite_start]**Visão por Plataforma**: Comparativo detalhado entre Google, Facebook, Instagram e outras, identificando onde o investimento é mais rentável[cite: 2].
3.  [cite_start]**Visão de Campanha**: Análise granular de cada anúncio, focando em métricas de engajamento como CTR e Cliques para otimizar peças criativas.
4.  [cite_start]**Visão Financeira e ROI**: Foco total no controle de custos e no retorno sobre o investimento, permitindo o ajuste fino do orçamento mensal[cite: 2].

## 🛠️ Problema de Negócio
O objetivo é solucionar a fragmentação dos dados de marketing. Antes deste dashboard, não era possível:
* [cite_start]Cruzar o custo de diferentes plataformas em uma única visão[cite: 2].
* [cite_start]Identificar rapidamente quais campanhas estavam com ROI negativo[cite: 2].
* [cite_start]Entender a jornada do funil (Impressões -> Cliques -> Conversões) de forma visual e intuitiva[cite: 2].

## ⚙️ Tecnologias e Dados
* **Ferramenta**: Power BI Desktop.
* [cite_start]**Processamento (ETL)**: Limpeza e padronização de moedas e datas via Power Query[cite: 2].
* [cite_start]**Dataset**: Base de dados contendo `id_campanha`, `plataforma`, `cliques`, `impressoes`, `custo`, `conversoes` e `receita`[cite: 2].

## 💡 Insights Estratégicos Extraídos
* **Otimização de Verba**: Identificação de plataformas com baixo CPC, mas alta conversão.
* **Escalabilidade**: Detecção de campanhas de alta performance prontas para receber maior investimento.
* **Sazonalidade**: Análise do comportamento das vendas ao longo do período filtrado.

## 📷 Visualização do Projeto
![Print do Dashboard](link-da-imagem-aqui)
*(Dica: Coloque uma imagem da tela principal do seu Power BI aqui)*

## 📂 Como acessar o projeto
1. Baixe o arquivo `Analise_Performance_Marketing.pbix` deste repositório.
2. Certifique-se de ter o **Microsoft Power BI Desktop** instalado.
3. Os dados brutos podem ser consultados na pasta `/data`.

## 📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
