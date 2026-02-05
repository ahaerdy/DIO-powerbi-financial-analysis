# Relatório Estratégico de Performance: Financial Data Analysis

## Introdução

Este projeto consiste na criação de um ecossistema de dados no Power BI utilizando o dataset Financial Sample. O foco foi unir Design de Interface (UI) com Inteligência de Negócios (BI), criando um relatório onde a navegabilidade orienta a descoberta de insights estratégicos.

---

## Arquitetura e Engenharia do Relatório

### 1. Estrutura do Grid e Layout (Visão Técnica)

O relatório foi construído sobre uma estrutura de grid para garantir equilíbrio visual e hierarquia de informações, conforme as boas práticas de UX.

#### Tela 01: Relatório de Vendas (Volume)

Nesta primeira página, o grid foi dividido em quatro áreas principais:

* **Cabeçalho e Menu Lateral:** Área reservada para o título do projeto e os botões de navegação, com imagens associadas para alternar entre páginas de forma intuitiva.
* **Área de KPIs (Topo):** Cartões de resumo com as métricas principais: Vendas Brutas e Unidades Vendidas.
* **Bloco Central de Tendência:** Gráficos de área e linha para visualização da evolução temporal das vendas.
* **Bloco Inferior de Distribuição:** Mapas e gráficos de colunas para segmentação geográfica por país e por produto.

> **[INSERIR TELA_01 AQUI]**

#### Tela 02: Relatório de Lucros (Rentabilidade)

A segunda tela foca na decomposição financeira. Seu grid organiza os visuais da seguinte forma:

* **Painel de Filtros (Slicers):** Posicionado para que qualquer seleção de Segmento ou Produto atualize os gráficos complexos instantaneamente.
* **Visuais de Decomposição:** Centralização da Árvore Hierárquica, permitindo a análise de causa raiz do lucro por diferentes níveis.
* **Painel Comparativo:** Gráficos de Radar e Treemap posicionados lado a lado para comparar simultaneamente o Mix de Produtos e a relevância dos Segmentos de Mercado.
* **Rodapé Analítico:** O Gráfico de Cascata encerra a página explicando a variação e composição do lucro por trimestre.

---

## Storytelling e Insights (Princípio, Meio e Fim)

Abaixo, descrevo a jornada de análise realizada através das interações reais capturadas no painel:

### 1. O Ponto de Partida: Liderança na França

Ao explorarmos a rentabilidade na Tela 02, utilizamos a Árvore Hierárquica para entender quais mercados trazem o melhor retorno financeiro para a empresa.

> **[INSERIR TELA_03 AQUI]**

* **Ação:** Seleção do mercado francês na Árvore Hierárquica.
* **Insight:** A França apresenta o maior lucro acumulado. Através da filtragem cruzada, o Gráfico de Radar revela que o sucesso francês não depende de um único item, mas de um mix equilibrado de produtos, com destaque de margem para o produto Paseo.

### 2. O Coração da Análise: Sazonalidade Trimestral

O fluxo financeiro apresenta variações importantes ao longo do ano. Utilizamos o Gráfico de Cascata (Waterfall) para explicar esses saltos de performance.

> **[INSERIR TELA_06 AQUI]**

* **Ação:** Seleção do 4º Trimestre (Q4) no gráfico de cascata.
* **Insight:** O Q4 é o motor de lucro da organização. O gráfico de cascata indica uma subida íngreme e o Treemap mostra que as vendas governamentais são agressivas neste período, sugerindo uma concentração de fechamento de contratos ao final do ano fiscal.

### 3. A Conclusão: Análise de Nicho no Segmento Midmarket

Para validar a resiliência do modelo de negócio, isolamos o segmento de médias empresas para verificar sua estabilidade fora dos grandes contratos governamentais.

> **[INSERIR TELA_07 AQUI]**

* **Ação:** Seleção do segmento Midmarket no Treemap.
* **Insight:** Ao contrário do setor público, o Midmarket mostra grande estabilidade. O gráfico de radar mantém uma forma simétrica, provando que a empresa possui uma oferta madura e competitiva para o setor privado, operando de forma independente de sazonalidades extremas.

---

## Recursos de Navegabilidade Aplicados

Para atender plenamente ao desafio proposto, foram implementados os seguintes recursos:

* **Botões com Indicadores (Bookmarks):** Permitem trocar visuais e estados do relatório dinamicamente.
* **Navegação por Imagem:** Botões estilizados que proporcionam uma experiência de uso similar a um aplicativo.
* **Segmentadores de Dados:** Configuração de filtros rápidos para País, Produto e Faixa de Desconto.

## Conclusão

Este projeto demonstra a capacidade de unir o rigor técnico (configuração de botões, grids e DAX) com a análise crítica de negócios. O resultado final é um dashboard interativo que transforma dados brutos do Financial Sample em decisões estratégicas fundamentadas.

---

*Relatório desenvolvido como entrega do desafio de projeto para o Bootcamp NTT DATA - Engenharia de Dados com Pythonda DIO.*

