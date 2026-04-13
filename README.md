# sprint12 - Análise de Tendências de Vídeos por Região (YouTube Trends Analytics)

## Visão Geral
Neste projeto, realizei uma análise exploratória sobre vídeos em alta em diferentes regiões, com o objetivo de identificar:
- Padrões de tendências ao longo do tempo
- Diferenças de comportamento entre países
- Categorias de conteúdo com maior presença em rankings

A análise foi conduzida com foco em transformar dados em insights sobre consumo de conteúdo digital.

## Problema de Negócio
Plataformas e criadores precisam entender:

- Quais tipos de conteúdo entram em tendência com mais frequência?
- Existe variação entre países?
- Como o timing (datas/semanas) influencia o volume de tendências?

## Abordagem Analítica
1. Data Cleaning & Preparação
- Conversão de datas para formato datetime
- Validação de integridade dos dados
- Criação de features temporais

2. Feature Engineering
Foram criadas variáveis estratégicas:
- Semana do ano (ISO week)
- Períodos semanais
- Estrutura temporal para análise de tendências

## Tecnologias Utilizadas
Python
Pandas
Jupyter Notebook
