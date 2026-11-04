# Prompt 6 — o painel que mostra o que importa (Claude Dashboards)

**Plano:** Dashboards está em **beta** e só nos planos pagos (Pro, Max, Ultra, Team, Enterprise). No plano grátis, faça só a primeira parte (escolher os números) e acompanhe numa planilha.
No Enterprise vem desligado até o dono da conta ligar.
**Dados:** conecte uma base (BigQuery, Snowflake, Databricks, Redshift, ClickHouse) ou um app como o
Salesforce pelos conectores. Sem isso, dá para começar de uma planilha anexada.

## Primeiro: escolha os números (antes de abrir o painel)
Um painel bom responde a uma pergunta só: "estou chegando lá?".
- **Número de resultado** (o que você quer no fim): faturamento do mês, clientes ativos, consultas feitas.
- **Números que empurram** (o que você consegue mexer hoje): propostas enviadas, primeiras consultas, retorno de pacientes.

```
Me ajude a escolher os números do meu painel.
Meu objetivo para [período] é: [ex.: 120 consultas por mês].
1. Confirme qual é o número de resultado.
2. Sugira de 2 a 4 números que empurram esse resultado e que eu consigo medir toda semana.
3. Para cada um, diga de onde vem o dado (qual sistema ou planilha) e com que frequência atualizar.
Não monte o painel ainda.
```

## Depois: monte o painel
```
Monte um dashboard com: [número de resultado] contra a meta no topo; abaixo, [números que empurram]
semana a semana; um gráfico por número, sem enfeite. Use [conector / planilha anexa].
Em cada gráfico, diga numa frase o que mudou desde a semana passada.
```

**Antes de compartilhar:** clique em cada número e confira a consulta (query) por trás; veja a data da
última atualização em cada gráfico. A Anthropic não publicou taxa de acerto das consultas: confira sempre.
Para análise funda, mande o painel para a sua ferramenta de BI.
