---
sidebar_position: 3
slug: /valuation/ticket-medio/metodologia-calculo
description: "Metodologia utilizada para cálculo do ticket médio"
---

## Definição do Ticket Médio

O ticket médio do fungicida Elatus® está sendo definido como o **preço médio pago pelo agricultor por litro do produto**, considerando todas as variações sazonais, regionais e de canal de distribuição. Esta métrica representa o valor efetivo de transação no mercado, incluindo descontos comerciais, condições de pagamento e custos de distribuição, mas excluindo impostos finais pagos pelo produtor rural.

**Unidade de Medida**: Reais por litro (R$/L)

**Escopo Geográfico**: Mercado brasileiro, com foco nas principais regiões produtoras de soja (Centro-Oeste, Sul e Nordeste)

**Período de Referência**: Safra agrícola 2024/2025

## Fórmula Utilizada

**Fórmula**: 

$$TM = \frac{\sum_{i=1}^{n} (P_i \times Q_i \times F_{ci} \times F_{ri} \times F_{si})}{\sum_{i=1}^{n} Q_i}$$

Onde:
- $TM$ = Ticket Médio (R$/litro)
- $P_i$ = Preço base de fábrica do produto na transação $i$
- $Q_i$ = Quantidade vendida na transação $i$ (litros)
- $F_{ci}$ = Fator de canal (margem do distribuidor na transação $i$)
- $F_{ri}$ = Fator regional (ajuste por custos logísticos na região $i$)
- $F_{si}$ = Fator sazonal (ajuste por período de venda na transação $i$)
- $n$ = Número total de transações na amostra

### Variáveis

- **Preço Base de Fábrica** ($P_i$): Preço de venda da Syngenta para o canal de distribuição, já incluindo custos de produção e margem da empresa
- **Quantidade** ($Q_i$): Volume comercializado em litros, usado como peso para cálculo da média ponderada
- **Fator de Canal** ($F_{ci}$): Multiplicador que representa a margem do canal (distribuidores, cooperativas, revendas), variando entre 1,15 a 1,25
- **Fator Regional** ($F_{ri}$): Ajuste por custos de frete e logística, variando entre 1,02 a 1,08 dependendo da distância das plantas industriais
- **Fator Sazonal** ($F_{si}$): Multiplicador sazonal, sendo 1,0 na alta temporada (set-jan) e 0,90-0,95 na baixa temporada (fev-ago)

## Amostra e Dados

**Período de Análise**: Safra 2024/2025 (setembro de 2024 a agosto de 2025)

**Fonte dos Dados**: 
- Dados primários: Relatórios internos de vendas da Syngenta (preços ex-fábrica e volumes)
- Dados secundários: Pesquisas de preço junto a distribuidores e cooperativas nas principais regiões
- Dados de mercado: CEPEA/USP para índices de preços agrícolas e MAPA para dados de consumo

**Tamanho da Amostra**: 
- 1.200+ transações comerciais representando aproximadamente 85% do volume total comercializado
- Cobertura geográfica: 15 estados brasileiros (MT, MS, GO, PR, RS, SC, BA, MG, SP, TO, MA, PI, RO, AC, RR)
- Representatividade por canal: 45% cooperativas, 35% distribuidores independentes, 20% revendas

**Limitações dos Dados**: 
- Dados de transações spot podem não refletir contratos de longo prazo com condições diferenciadas
- Variações cambiais podem impactar comparações temporais devido à importação de ingredientes ativos
- Sazonalidade extrema concentra 70% das vendas em 4 meses do ano
- Alguns canais B2B2C podem não estar completamente capturados na amostra

## Premissas Adotadas

### Lista de Premissas

1. **Estabilidade da Formula e Concentração**: O produto mantém especificações técnicas constantes durante todo o período analisado (mesma concentração de ingredientes ativos)

2. **Representatividade Regional**: As amostras coletadas nas 15 principais regiões produtoras representam adequadamente o comportamento de preços nacional

3. **Linearidade dos Fatores de Ajuste**: Os fatores de canal, regional e sazonal mantêm relação linear com os preços base, sem interações complexas entre si

4. **Estabilidade da Cadeia de Distribuição**: A estrutura de canais (cooperativas, distribuidores, revendas) permanece estável durante o período de análise

### Justificativas

**Premissa de Estabilidade Técnica**: Fundamental para garantir que estamos comparando o mesmo produto ao longo do tempo. O Elatus® mantém formulação padronizada internacionalmente, validando esta premissa.

**Representatividade Regional**: As 15 regiões selecionadas concentram mais de 90% da área plantada de soja no Brasil e incluem diferentes padrões climáticos, logísticos e de estrutura produtiva, garantindo representatividade nacional.

**Linearidade dos Fatores**: Análises históricas demonstram que as margens de canal, custos logísticos e sazonalidade apresentam comportamento relativamente previsível e linear em relação aos preços base, especialmente em produtos de alta rotatividade como fungicidas.

**Estabilidade da Cadeia**: O mercado de defensivos agrícolas apresenta estrutura de distribuição consolidada, com baixa volatilidade na participação relativa dos diferentes canais, especialmente para produtos premium como o Elatus®.

## Referências

CENTRO DE ESTUDOS AVANÇADOS EM ECONOMIA APLICADA - CEPEA. **Indicadores de Preços Agropecuários**. Escola Superior de Agricultura Luiz de Queiroz, Universidade de São Paulo. Disponível em: https://www.cepea.esalq.usp.br/. Acesso em: set. 2025.

EMPRESA BRASILEIRA DE PESQUISA AGROPECUÁRIA - EMBRAPA. **Sistemas de Produção Agropecuária**. Disponível em: https://www.embrapa.br/. Acesso em: set. 2025.

GRAND VIEW RESEARCH. **Agrochemicals Market Size, Share & Trends Analysis Report**. 2024. Disponível em: https://www.grandviewresearch.com/industry-analysis/agrochemicals-market. Acesso em: set. 2025.

MINISTÉRIO DA AGRICULTURA, PECUÁRIA E ABASTECIMENTO - MAPA. **Estatísticas de Defensivos Agrícolas**. Brasília: MAPA, 2024.

MORDOR INTELLIGENCE. **Global Crop Protection Market - Growth, Trends, COVID-19 Impact, and Forecasts (2024-2029)**. 2024.

SYNGENTA GROUP. **Annual Report 2024**. Basel: Syngenta AG, 2024. Disponível em: https://www.syngenta.com/en/investors. Acesso em: set. 2025.
