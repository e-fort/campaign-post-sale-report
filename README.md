# Relatório Pós-Venda de Campanha (Mensuração)

## Visão geral
Este projeto simula uma entrega de **pós-venda de campanha** com foco em **mensuração, insights e recomendações acionáveis** para time comercial e stakeholders.

## Objetivo
Avaliar o desempenho da campanha e responder:
- O investimento gerou eficiência de mídia (CPM, alcance, frequência)?
- Como foi o consumo de vídeo (VTR, taxa de conclusão)?
- Quais cortes performaram melhor (formato, público, posicionamento)?
- O que manter, otimizar ou evitar no próximo flight?

## Métricas analisadas
- CPM, alcance, frequência
- CTR / VTR (quando aplicável)
- Distribuição de investimento por formato/posicionamento
- Comparativos por período (ex.: semana 1 vs semana 2)

## Metodologia (resumo)
1. Definição de KPIs e cortes
2. Consolidação dos dados (plataformas/veículos)
3. Análise comparativa e leitura de eficiência
4. Síntese em narrativa executiva (insight → implicação → recomendação)

## Entregáveis
- Relatório executivo: `docs/relatorio.md`
- Imagens/prints: `images/`
- (Opcional) Queries SQL: `sql/`
- (Opcional) Notebook de análise: `notebooks/`

## Observações
Dados sensíveis foram omitidos. Quando necessário, números são demonstrados em valores fictícios ou percentuais.

## Resultados Principais

### Comparativo de CPM por Plataforma

![CPM por Plataforma](images/download.png)

### Principais Insights

- Plataforma mais eficiente em custo: X (menor CPM)
- Melhor performance de clique: Y (maior CTR)
- Melhor retenção de vídeo: Z (maior VTR)

### Recomendações Estratégicas

1. Priorizar X para campanhas de awareness com foco em eficiência.
2. Manter Y para estratégias de tráfego.
3. Ajustar segmentação em plataformas com CPM elevado.

## Sobre o Projeto

Este case simula uma análise de pós-venda de campanha de mídia, com foco em:

- Consolidação de dados multicanal
- Cálculo de métricas de mídia (CPM, CTR, VTR)
- Benchmarking entre plataformas
- Geração de insights acionáveis
- Construção de narrativa executiva orientada por dados

O objetivo foi demonstrar capacidade analítica, leitura estratégica e tradução de dados em recomendações comerciais.

## Análise Técnica

O notebook completo da análise pode ser acessado em:

notebooks/post_sale_analysis.ipynb

