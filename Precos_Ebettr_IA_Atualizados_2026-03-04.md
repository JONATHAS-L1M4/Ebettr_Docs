# Precos Ebettr IA - Atualizado (04/03/2026)

## Referencia de mercado (03-04/2026)
- n8n Cloud: Starter 20 EUR, Pro 50 EUR, Enterprise a partir de 200 EUR.
- Make: Core USD 9, Pro USD 16, Teams USD 29, Enterprise a partir de USD 209.
- Zapier: Professional USD 29.99 (anual) e Team USD 103.50 por usuario (anual).
- Botpress: Plus USD 89, Team USD 495.
- Cambio de referencia (Banco Central do Brasil, 04/03/2026): USD 5.2091 | EUR 6.0639.

## Justificativa da atualizacao de precos
1. Defasagem da tabela anterior: os valores antigos estavam abaixo da faixa praticada para plataformas com infraestrutura gerenciada, automacao e recursos de agente IA.
2. Posicionamento por benchmark: os novos valores foram ancorados em referencias de mercado (n8n, Make, Zapier e Botpress), buscando competitividade sem subprecificacao.
3. Conversao para realidade local: a calibragem em reais considerou o cambio oficial de 04/03/2026 para reduzir distorcoes entre custo internacional e preco final no Brasil.

## Ajuste de tabela (mensal)

| Plano | Preco atual | Preco atualizado | Variacao |
|---|---:|---:|---:|
| Starter | R$ 90 | R$ 149 | +65,6% |
| Essencial | R$ 150 | R$ 249 | +66,0% |
| Plus | R$ 280 | R$ 449 | +60,4% |
| Pro | R$ 650 | R$ 899 | +38,3% |
| Scale | R$ 1.200 | R$ 1.690 | +40,8% |

---

## Plano Starter (Mensal) - Sem IA
**Preco:** R$ 149 / mes

**Inclui:**
- 5 e-mails para acesso ao painel/automacao
- Formulario sob medida para configurar
- Visualizar execucoes (historico no painel com paginacao)
- Salvar credenciais
- MCP Server N8n

**Fluxos**
- 1 fluxo

**Nao inclui**
- Supabase (RAG)
- MCP Client / Agente / recursos de IA
- Memoria do agente (Redis)

---

## Plano Essencial (Mensal)
**Preco:** R$ 249 / mes

**Inclui:**
- 10 e-mails para acesso ao painel + agente
- MCP Client / Agente (IA)
- Supabase (RAG): 500 MB
- Memoria do agente (Redis): 24h
- Visualizar execucoes (historico no painel com paginacao)
- Salvar credenciais
- Formulario sob medida para configurar
- MCP Server N8n

**Fluxos**
- 1 fluxo

---

## Plano Plus (Mensal)
**Preco:** R$ 449 / mes

**Inclui:**
- 20 e-mails para acesso ao painel + agente
- MCP Client / Agente (IA)
- Supabase (RAG): 1 GB
- Memoria do agente (Redis): 3 dias
- Visualizar execucoes (historico no painel com paginacao)
- Salvar credenciais
- Formulario sob medida para configurar
- MCP Server N8n

**Fluxos**
- 2 fluxos

---

## Plano Pro (Mensal)
**Preco:** R$ 899 / mes

**Inclui:**
- 50 e-mails para acesso ao painel + agente
- MCP Client / Agente (IA)
- Supabase (RAG): 2 GB
- Memoria do agente (Redis): 7 dias
- Visualizar execucoes (historico no painel com paginacao)
- Salvar credenciais
- Formulario sob medida para configurar
- MCP Server N8n

**Fluxos**
- 5 fluxos

---

## Plano Scale (Mensal)
**Preco:** R$ 1.690 / mes

**Inclui:**
- E-mails ilimitados para acesso ao painel + agente
- MCP Client / Agente (IA)
- Supabase (RAG): 5 GB
- Memoria do agente (Redis): 30 dias
- Visualizar execucoes (historico no painel com paginacao)
- Salvar credenciais
- Formulario sob medida para configurar
- MCP Server N8n

**Fluxos**
- 10 fluxos

---

## Regra de Fluxo Extra

**Formula**

```
Preco do fluxo extra = preco do plano / numero de fluxos inclusos
```

**Valor por plano**

| Plano | Calculo | Preco por fluxo extra |
|---|---:|---:|
| Starter | 149 / 1 | R$ 149,00 |
| Essencial | 249 / 1 | R$ 249,00 |
| Plus | 449 / 2 | R$ 224,50 |
| Pro | 899 / 5 | R$ 179,80 |
| Scale | 1690 / 10 | R$ 169,00 |

**Calculo final**

```
Valor mensal = Plano + (fluxos extras x preco do fluxo extra)
```

---

## Franquia de execucoes por mes (sugestao)

| Plano | Execucoes / mes |
|---|---:|
| Starter | 25.000 |
| Essencial | 50.000 |
| Plus | 125.000 |
| Pro | 350.000 |
| Scale | 1.500.000 |

---

## Observacao comercial
- Os valores acima sao sugeridos para manter competitividade frente a plataformas de automacao e agentes de IA em 2026.
- Os custos de token/modelo de IA continuam sendo pagos diretamente pelo cliente.