---
sidebar_position: 10
slug: /valuation/valuation/limitacoes-conclusoes
description: "Limitações da análise e conclusões finais"
---

# Limitações e Conclusões

## Limitações da Análise

### Limitações Metodológicas

- **Dependência de premissas no DCF**: O resultado é sensível a WACC e g, conforme `Analise_Sensibilidade.md`, podendo alterar significativamente o valor.
- **Uso de mediana de múltiplos**: A aplicação direta da mediana setorial (15.0x EV/EBITDA) assume comparabilidade plena de risco, margem e ciclo entre pares.
- **Transações precedentes**: Múltiplos de M&A incluem prêmio de controle e momento de mercado específico, não necessariamente refletindo valor standalone.

### Limitações de Dados

- **Receita e Lucro Líquido (LTM)**: Ausência de valores no repositório; impede cálculo final de EV/Receita e P/L em `Benchmarking_Multiplos.md`.
- **Normalizações**: EBITDA utilizado (2024) pode conter efeitos não recorrentes; ajustes adicionais podem ser necessários.
- **Granularidade regional**: Diferenças por região/canal (vide `Metodologia_Calculo.md`) podem afetar margens e, portanto, múltiplos relativos.

### Premissas Mais Questionáveis

- **WACC base**: Pequenas variações no risco país/setor alteram o valuation de forma desproporcional (vide matriz de sensibilidade).
- **Crescimento perpétuo (g)**: Suposição de crescimento de longo prazo próxima ao crescimento real da economia pode não se materializar em ciclos adversos do agro.
- **Aplicação do múltiplo setorial**: Pressupõe convergência de margens e alavancagem à mediana dos peers (Bayer, Corteva, BASF, FMC), o que pode divergir em determinados períodos.

## Conclusões e Recomendações

### Principais Conclusões

1. **Convergência metodológica**: DCF base aponta Equity Value de aproximadamente **$101.1 Bi** (`Analise_Sensibilidade.md`), enquanto múltiplos e precedentes sugerem faixa próxima.
2. **Valuation relativo**: Mediana setorial de **15.0x EV/EBITDA** aplicada ao EBITDA de **$7.67 Bi** implica **EV $115.0 Bi** e **Equity $96.8 Bi** (`Metodologias_Secundarias.md`).
3. **Transações precedentes**: Múltiplo de **16.5x EV/EBITDA** implica **EV $126.5 Bi** e **Equity $108.3 Bi** (reflete prêmio de controle, `Metodologias_Secundarias.md`).
4. **Drivers críticos**: WACC, câmbio (USD/BRL) e preços de commodities são os principais determinantes do valor; eficiência técnica sustenta prêmio via margens (`Contexto_Recapitulacao.md`).

### Faixa de Valor Final

**Valor Mínimo (Cenário Pessimista)**: **$96.8 Bi** (equity via múltiplos de mercado; cenário sem prêmio, mais conservador)

**Valor Base**: **$101.1 Bi** (equity via DCF base, `Analise_Sensibilidade.md`)

**Valor Máximo (Cenário Otimista)**: **$108.3 Bi** (equity via precedentes com prêmio de controle)

**Valor Alvo (Recomendado)**: **$103.0–105.0 Bi** (média ponderada entre DCF e múltiplos; ajuste qualitativo por inovação e canal)

### Recomendação de Investimento

**Recomendação**: **MANUTENÇÃO**

**Justificativa**: Valuation atual alinhado à mediana setorial em EV/EBITDA. Upside depende da confirmação de margens e execução em inovação/canal; riscos macro (câmbio, commodities) justificam postura neutra até atualização dos dados LTM (Receita e Lucro).

### Catalisadores a Observar

- **Normalização de margens**: Evidências de recorrência do EBITDA e expansão operacional.
- **Câmbio e commodities**: Trajetória favorável reduz pressão de custos e melhora demanda do produtor.
- **Pipeline de P&D e soluções digitais/biológicas**: Aceleração de adoção reforça prêmio de múltiplos.

### Próximos Passos Sugeridos

- **Atualizar LTM**: Inserir Receita e Lucro Líquido (LTM) em `Benchmarking_Multiplos.md` para completar EV/Receita e P/L.
- **Revisar normalizações**: Ajustar EBITDA por itens não recorrentes e validar dívida líquida mais recente.
- **Reconciliação quantitativa**: Preencher `Reconciliacao_Cenarios.md` com pesos e verificar convergência dos métodos vs sensibilidade.

## Implicações Setoriais

### Insights sobre o Setor

- O setor migra para soluções integradas (químicos + biológicos + digital), favorecendo players com P&D robusto e canal próximo ao produtor.

### Tendências Identificadas

- Aumento do uso de dados e plataformas digitais no campo; pressão regulatória e demanda por sustentabilidade impulsionam biológicos.

### Aplicabilidade para Outros Players

- A análise é aplicável a concorrentes com perfil semelhante de risco e inovação (Bayer, Corteva, BASF, FMC), ajustando múltiplos por margem, ciclo e alavancagem específicos.
