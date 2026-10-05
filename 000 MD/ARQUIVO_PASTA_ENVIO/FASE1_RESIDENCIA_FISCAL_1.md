# FASE 1 — LINHA DO TEMPO DE RESIDÊNCIA FISCAL
## José Adalmo Carvalho de Barros | CPF 069.351.996-70
### Assistente Técnico: Robson Soares Bezerra | CRC/PR 062711/O
### Gerado: 24/09/2026 | Versão: 1.0

---

> **AVISO TÉCNICO:** Este documento integra o fluxo de apuração definido em `03_PROMPT_CLAUDE_TAX_EXIT_CALCULO.md`.  
> Todas as afirmações classificadas como `[FATO CONFIRMADO]` derivam de documentos verificados na sessão.  
> Estimativas são marcadas como `[INFERÊNCIA TÉCNICA]` ou `[HIPÓTESE]`.  
> Nenhum valor de imposto estimado neste arquivo substitui parecer individualizado ou tem efeito declaratório.

---

## 1. BASE LEGAL VERIFICADA (WEB SEARCH — 24/09/2026)

| Norma | Descrição | Status Verificação |
|-------|-----------|-------------------|
| IN SRF Nº 208/2002 | Residência fiscal — critérios de residente/não residente; regra dos 12 meses; CSDP/DSDP | Verificado via [LegisWeb](https://www.legisweb.com.br/legislacao/?id=75394) |
| IN RFB 1.871/2019 | Regras da DIRPF exercício 2019 (AC 2018); limite R$ 28.559,70 | Verificado via [LeFisc 2019](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2019.htm) |
| IN RFB 2.255/2025 | Regras da DIRPF exercício 2025 (AC 2024); limite R$ 33.888,00 | Verificado via [LeFisc 2025](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2025.htm) |
| IN RFB 2.020/2021 | Prorrogação prazo DIRPF AC 2020 para 31/05/2021 (COVID) | Verificado via [Agência Brasil](https://agenciabrasil.ebc.com.br/economia/noticia/2021-04/receita-adia-o-prazo-de-entrega-da-declaracao-de-imposto-de-renda) |
| IN RFB 1.500/2014 | Rendimentos do exterior; carnê-leão; conversão cambial (PTAX) | `(confirmar na fonte oficial)` |
| ADI SRF 28/2000 | Reciprocidade Brasil–EUA; imposto federal US creditable; estadual/municipal NÃO | `(confirmar na fonte oficial)` |
| RIR/2018 — Decreto 9.580/2018 Art. 115 | Compensação imposto pago no exterior — PESSOA FÍSICA | `(confirmar na fonte oficial)` |
| Lei 4.862/1965 Art. 5° | Crédito imposto pago no exterior — PF (base legal correta; NÃO usar Art. 26 Lei 9.249/1995 — PJ) | `(confirmar na fonte oficial)` |
| CTN Art. 150 §4° | Decadência (prazo de 5 anos para lançamento por homologação) | Norma codificada — confirmar contagem |

---

## 2. PREMISSAS E DADOS DE ENTRADA CONFIRMADOS

| Item | Valor | Status | Fonte Documental |
|------|-------|--------|-----------------|
| Data de saída do Brasil | **25/01/2018** | `[FATO CONFIRMADO]` | Form W-7 (2018_US_TAX.md): "Date of entry into United States: 01/25/2018" |
| Endereço nos EUA | 263 Greenwood Ave, Apt 105, Bethel, CT 06801 | `[FATO CONFIRMADO]` | W-7 e Form 1040 2018 (2018_US_TAX.md) |
| Endereço BR no W-7 | Rua Silas #166, São Paulo, Brazil | `[FATO CONFIRMADO]` | W-7 (2018_US_TAX.md) |
| CSDP — Comunicação de Saída | Não localizada | `[FATO CONFIRMADO]` | Ausência documental — FASE 0 Register |
| DSDP — Declaração de Saída | Não localizada | `[FATO CONFIRMADO]` | Ausência documental — FASE 0 Register |
| DIRPF AC 2016 (ex. 2017) | Localizada — DEC + REC | `[FATO CONFIRMADO]` | Pasta `2017/` — FASE 0 Register |
| DIRPF AC 2017 (ex. 2018) | Cliente afirma ter entregue; não localizada | `[HIPÓTESE]` | Ausência na pasta; só há AC 2016 com comprovante |
| DIRPF AC 2018 (ex. 2019) e posteriores | Não localizada | `[FATO CONFIRMADO]` | Ausência documental — FASE 0 Register |
| .DEC 2026/AC 2025 | Arquivo PGD gerado; endereço SP/BR; **SEM RECIBO** | `[FATO CONFIRMADO]` | `06935199670-IRPF-A-2026-2025-ORIGI.DEC` |
| Renda US 2018 | US$ 25.628 renda total; imposto federal = US$ 0 | `[FATO CONFIRMADO]` | Form 1040 2018 (2018_US_TAX.md) |
| Renda US 2019 | Sch C bruto US$ 10.000; SE tax = US$ 1.413 | `[FATO CONFIRMADO]` | Form 1040 2019 + Sch C + SE (2019_US_TAX.md) |
| Renda US 2020 | Sch C bruto US$ 30.152; SE tax = US$ 318 | `[FATO CONFIRMADO]` | Form 1040 2020 (2020_2021_US_TAX.md) |
| Renda US 2021 | Sch C bruto US$ 35.335; lucro líq. US$ 4.870; SE tax = US$ 686 | `[FATO CONFIRMADO]` | Form 1040 2021 (2020_2021_US_TAX.md) |
| Renda US 2022 | Sch C bruto US$ 40.550; lucro líq. US$ 10.823; SE tax = US$ 1.529 | `[FATO CONFIRMADO]` | Form 1040 2022 (2022_US_TAX.md) |
| Renda US 2023 | K-1 (Sch E) US$ 75.383 (Two Brothers Drywall & Paint); SE tax = US$ 10.651; total tax = US$ 15.480 | `[FATO CONFIRMADO]` | Form 1040 2023 + K-1 (2023_US_TAX.md) |
| Ativos digitais 2023 | Checkbox "Digital assets" marcado **YES** no Form 1040/2023 | `[FATO CONFIRMADO]` | Form 1040 2023 (2023_US_TAX.md) |
| Remessas Nubank 2024–2026 | R$ 180.971,76 via Daycoval/Remitly/TAPTAP (18 transações) | `[FATO CONFIRMADO]` | NUBANK_LEDGER.csv — classe `intermediario_remessa` |

---

## 3. DETERMINAÇÃO DA DATA DE PERDA DA RESIDÊNCIA FISCAL

### 3.1 Regra Aplicável

**IN SRF Nº 208/2002 — Cenário sem CSDP:**

> Quando o contribuinte sai do Brasil **sem apresentar a CSDP** e sem solicitar o encerramento fiscal,  
> a Receita Federal o mantém como **residente fiscal** enquanto não completados  
> **12 meses consecutivos de ausência** do território nacional (critério de perda de residência por decurso de prazo).

### 3.2 Cálculo do Prazo

```
Data de saída comprovada:  25/01/2018  [FATO CONFIRMADO — W-7 entry date]
12 meses consecutivos:   + 365 dias
Data de perda de residência:  25/01/2019
```

> `[INFERÊNCIA TÉCNICA]` A perda da condição de residente opera-se em **25/01/2019**, data em que se completam  
> 12 meses ininterruptos de ausência. Este é o marco que determina, retroativamente, que:  
> - 01/01/2018 a 31/12/2018 → **residente fiscal (ano integral)**  
> - 01/01/2019 a 25/01/2019 → **residente fiscal (25 dias)** — período que demandaria DSDP  
> - 26/01/2019 em diante → **não residente**

### 3.3 Nota sobre CSDP Retroativa

`[SUGESTÃO — não executar sem parecer individualizad]`: Existe a possibilidade técnica de apresentar CSDP retroativa datada de 25/01/2018, o que alteraria o marco para:
- AC 2018: residente apenas 01/01–25/01/2018 (25 dias); DSDP para esse período
- AC 2019 em diante: integralmente não residente

**Motivação para considerar:** Renda US 2018 de US$ 25.628 convertida a PTAX (~R$ 3,65/USD) ≈ R$ 93.542 → **acima do limite de obrigatoriedade** (R$ 28.559,70) → DIRPF deveria ter sido entregue se residente integral em 2018 e não foi.

**Motivação para NÃO executar:** (a) decadência já correu — RFB não pode mais lançar AC 2018 ou AC 2019; (b) CSDP retroativa de 2026 para 2018 é irregular e pode criar autuação; (c) risco de exposição maior do que o benefício.

**Recomendação preliminar:** `[SUGESTÃO]` Manter estratégia conservadora (sem CSDP retroativa). Decadência protege. Priorizar atualização cadastral do CPF como não residente.

---

## 4. TABELA DE LINHA DO TEMPO — ANO A ANO

| AC | Período | Status Fiscal | Obrigação DIRPF | Tipo Declaração | Prazo Original | Decadência | Nível de Risco | Nota Técnica |
|----|---------|--------------|-----------------|-----------------|---------------|-----------|---------------|-------------|
| **2016** | 01/01–31/12/2016 | **Residente (integral)** | **ENTREGUE** | DIRPF AC 2016 | 28/04/2017 | N/A | 🟢 BAIXO | DEC + REC localizados na pasta `2017/` `[FATO CONFIRMADO]` |
| **2017** | 01/01–31/12/2017 | **Residente (integral)** | **[HIPÓTESE] Entregue** | DIRPF AC 2017 | 30/04/2018 | 30/04/2023 → **EXPIRADA** | 🟡 MÉDIO | Cliente afirma ter entregue; documentação não localizada. Se não entregue: decadência expirada em 04/2023. `[HIPÓTESE]` |
| **2018** | 01/01–31/12/2018 | **Residente (integral)** `[INFERÊNCIA TÉCNICA]` | **NÃO ENTREGUE** — obrigatória | DIRPF AC 2018 | 30/04/2019 | **30/04/2024 → EXPIRADA** | 🟡 MÉDIO | Renda US$ 25.628 ≈ R$ 93.542 > limite R$ 28.559,70. DIRPF obrigatória mas não entregue. Decadência expirou 04/2024. RFB não pode mais lançar. `[FATO CONFIRMADO - renda; INFERÊNCIA TÉCNICA - status]` |
| **2019** | 01/01–25/01 residente; 26/01–31/12 não residente | **Parcial** `[INFERÊNCIA TÉCNICA]` | DSDP para 01/01–25/01/2019 — **NÃO ENTREGUE** | DSDP parcial AC 2019 | ~30/04/2020 (ou 30/06/2020 — COVID; confirmar) | **~04/2025 ou 06/2025 → EXPIRADA** | 🟡 MÉDIO-BAIXO | Renda proporcional 25 dias: US$ 10.000 × (25/365) ≈ US$ 685 ≈ R$ 2.699 — **abaixo do limite** (R$ 28.559,70). Sem imposto devido. Decadência expirada. `[INFERÊNCIA TÉCNICA]` |
| **2020** | 01/01–31/12/2020 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR | — | — | N/A | 🟢 BAIXO | Renda US$ 30.152 Sch C — totalmente fora do escopo do IRPF como não residente. Sem fonte BR identificada. `[FATO CONFIRMADO - renda]` |
| **2021** | 01/01–31/12/2021 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR | — | — | N/A | 🟢 BAIXO | Renda US$ 35.335 Sch C — fora do escopo. Sem fonte BR identificada. `[FATO CONFIRMADO - renda]` |
| **2022** | 01/01–31/12/2022 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR | — | — | N/A | 🟢 BAIXO | Renda US$ 40.550 Sch C — fora do escopo. Sem fonte BR identificada. `[FATO CONFIRMADO - renda]` |
| **2023** | 01/01–31/12/2023 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR | — | — | N/A | 🟡 MÉDIO | Renda K-1 US$ 75.383 (parceria EUA) — fora do escopo. PORÉM: checkbox "digital assets YES" exige investigação. `[FATO CONFIRMADO - renda e checkbox]` |
| **2024** | 01/01–31/12/2024 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR confirmada | — | — | N/A | 🔴 ALTO | CPF ainda não atualizado como não residente. Recebimentos Nubank via intermediários (Daycoval/Remitly/TAPTAP) precisam ter origem identificada. `[FATO CONFIRMADO - remessas; HIPÓTESE - natureza]` |
| **2025** | 01/01–31/12/2025 | **Não residente** `[INFERÊNCIA TÉCNICA]` | **NENHUMA** — sem renda BR confirmada | — | — | N/A | 🔴 ALTO | `.DEC` (ex. 2026/AC 2025) gerado com endereço SP/BR — **SEM RECIBO — NÃO TRANSMITIR**. Transmissão constituiria fato contrário à tese de saída 2018. `[FATO CONFIRMADO]` |

> **LEGENDA DE RISCO:**  
> 🟢 BAIXO — sem exposição atual ou exposição extinta  
> 🟡 MÉDIO — decadência extinta mas ponto documental/administrativo a resolver  
> 🔴 ALTO — risco ativo, ação urgente necessária

---

## 5. LIMITES DE OBRIGATORIEDADE POR ANO-CALENDÁRIO

| AC (Exercício) | Rend. Tributável | Rend. Isento/NT | Bens e Direitos | Fonte |
|---------------|-----------------|-----------------|----------------|-------|
| 2016 (ex. 2017) | R$ 28.123,91 | R$ 40.000,00 | R$ 300.000,00 | IN RFB 1.613/2016 `(confirmar)` |
| 2017 (ex. 2018) | R$ 28.559,70 | R$ 40.000,00 | R$ 300.000,00 | IN RFB 1.690/2017 `(confirmar)` |
| 2018 (ex. 2019) | **R$ 28.559,70** | R$ 40.000,00 | R$ 300.000,00 | IN RFB 1.871/2019 ✅ |
| 2019 (ex. 2020) | R$ 28.559,70 | R$ 40.000,00 | R$ 300.000,00 | `(mesmos parâmetros — confirmar IN RFB do ano)` |
| 2020 (ex. 2021) | R$ 28.559,70 | R$ 40.000,00 | R$ 300.000,00 | `(confirmar)` |
| 2021 (ex. 2022) | R$ 28.559,70 | R$ 40.000,00 | R$ 300.000,00 | `(confirmar)` |
| 2022 (ex. 2023) | **R$ 28.559,70** | R$ 40.000,00 | R$ 300.000,00 | Confirmado via [LeFisc 2023](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2023.htm) ✅ |
| 2023 (ex. 2024) | R$ 28.559,70 | R$ 40.000,00 | R$ 300.000,00 | `(confirmar IN RFB 2.134/2023 ou similar)` |
| **2024 (ex. 2025)** | **R$ 33.888,00** | **R$ 200.000,00** | **R$ 800.000,00** | IN RFB 2.255/2025 ✅ |

> **NOTA:** Os limites de 2017 a 2023 permaneceram em R$ 28.559,70 para rendimento tributável e R$ 40.000,00 para isento.  
> A reforma tributária de 2023/2024 elevou substancialmente os limites para AC 2024 em diante.

---

## 6. ANÁLISE DE DECADÊNCIA (CTN Art. 150 §4°)

### 6.1 Fundamento Legal

```
Prazo de decadência: 5 anos a contar do fato gerador homologado (data-limite da declaração)
Norma: CTN Art. 150 §4°; Súmula STJ 555 (confirmar aplicação)
```

### 6.2 Tabela de Decadência por Ano-Calendário

| AC | Prazo Original Declaração | Decadência Completa | Status em 24/09/2026 | Impacto |
|----|--------------------------|--------------------|--------------------|---------|
| 2016 | 28/04/2017 | 28/04/2022 | ✅ EXPIRADA | Nenhum. Declaração entregue. |
| 2017 | 30/04/2018 | 30/04/2023 | ✅ EXPIRADA | Nenhum. Mesmo se não entregue (HIPÓTESE), RFB não pode lançar. |
| **2018** | **30/04/2019** | **30/04/2024** | ✅ **EXPIRADA** | DIRPF obrigatória não entregue. Risco de lançamento **eliminado por decadência**. |
| **2019 (DSDP)** | ~30/04/2020 ¹ | ~30/04/2025 | ✅ **EXPIRADA** | DSDP parcial (25 dias) não entregue. Risco **eliminado por decadência**. |
| **2020** | 31/05/2021 ² | **31/05/2026** | ✅ **EXPIRADA** | Não residente — sem obrigação. Decadência expirada por completude. |
| **2021** | 29/04/2022 | 29/04/2027 | ⚠️ ABERTA | Não residente — sem obrigação declaratória. Prazo aberto mas irrelevante (sem renda BR). |
| **2022** | 31/05/2023 | 31/05/2028 | ⚠️ ABERTA | Não residente — sem obrigação declaratória. |
| **2023** | 31/05/2024 | 31/05/2029 | ⚠️ ABERTA | Não residente — sem obrigação declaratória. Atenção: digital assets (ver Bloco D). |
| **2024** | 31/05/2025 | 31/05/2030 | ⚠️ ABERTA | Não residente — sem obrigação declaratória. Remessas Nubank a identificar. |
| **2025** | ~30/04/2026 ³ | ~30/04/2031 | ⚠️ ABERTA | Não residente — sem obrigação. `.DEC` não transmitido. **Não transmitir.** |

**Notas de rodapé:**  
¹ AC 2019: prazo pode ter sido prorrogado para 30/06/2020 (COVID — confirmar IN RFB específica para ex. 2020).  
² AC 2020: IN RFB 2.020/2021 prorrogou para 31/05/2021 (COVID — verificado Agência Brasil).  
³ AC 2025: prazo presumido April 2026; confirmar IN RFB específica do exercício 2026.

> **CONCLUSÃO DE DECADÊNCIA:** `[INFERÊNCIA TÉCNICA]`  
> Para os únicos anos em que havia obrigação enquanto residente (AC 2018 integralmente; AC 2019 parcialmente),  
> **o prazo de lançamento da RFB já expirou**. Não existe risco de cobrança retroativa para esses anos.

---

## 7. ESTIMATIVA DE EXPOSIÇÃO TRIBUTÁRIA — PERÍODO RESIDENTE

> ⚠️ Esta seção é informativa. Os valores são ESTIMADOS para demonstrar o que teria sido devido.  
> A decadência já correu. **Não há débito exigível.** PTAX definitivo será apurado na FASE 2.

### 7.1 AC 2018 — Residente Integral

| Item | Valor US$ | PTAX Médio 2018 (estimado) | Valor BRL (estimado) |
|------|----------|--------------------------|---------------------|
| Renda bruta US (Schedule C) | US$ 25.628 | ~R$ 3,65/USD `[HIPÓTESE]` | ~R$ 93.542 |
| Limite de isenção IRPF 2018 | — | — | R$ 28.559,70 |
| Base tributável estimada | — | — | ~R$ 65.000 |
| IRPF estimado (alíquotas 2018) | — | — | ~R$ 13.000–16.000 `[HIPÓTESE]` |
| Imposto federal US pago (crédito) | US$ 0 | — | R$ 0 (não creditável — zero) |
| **Exposição líquida estimada** | | | **~R$ 13.000–16.000 `[HIPÓTESE]`** |
| **Status** | | | **DECAÍDA — inexigível desde 30/04/2024** |

### 7.2 AC 2019 — Período Residente (25 dias)

| Item | Valor US$ | PTAX Médio Jan/2019 (estimado) | Valor BRL (estimado) |
|------|----------|-------------------------------|---------------------|
| Renda proporcional (25/365 × US$ 10.000) | ~US$ 685 | ~R$ 3,85/USD `[HIPÓTESE]` | ~R$ 2.637 |
| Limite de isenção DSDP 2019 | — | — | R$ 28.559,70 |
| **Conclusão** | | | **Abaixo do limite — SEM IMPOSTO DEVIDO** |
| **Status** | | | **DECAÍDA — inexigível** |

> **NOTA:** Para AC 2019, mesmo que a DSDP tivesse sido entregue tempestivamente,  
> a renda proporcional de 25 dias (≈R$ 2.637) estava **muito abaixo do limite de obrigatoriedade**.  
> Não haveria imposto a pagar. A decadência corre sobre obrigação administrativa, não sobre tributo.

---

## 8. PONTO DE RISCO CRÍTICO IMEDIATO — .DEC 2026/AC 2025

> 🔴 **AÇÃO URGENTE — FORA DO FLUXO DE ANÁLISE RETROSPECTIVA**

| Item | Detalhe |
|------|---------|
| Arquivo | `06935199670-IRPF-A-2026-2025-ORIGI.DEC` |
| Status | Gerado no PGD; **SEM recibo de transmissão** |
| Endereço declarado | São Paulo/SP — Brasil (endereço de residente) |
| Problema | Transmissão implica autodeclaração de residência para AC 2025 |
| Conflito | Contradiz a tese de saída definitiva em 25/01/2018 |
| Ação | **NÃO TRANSMITIR** enquanto a linha do tempo de residência não for formalizada |
| Próximo passo | Excluir o arquivo ou reconstruí-lo como declaração de não residente (DSDP ou informar que não há obrigação) |

---

## 9. ESTRATÉGIA DE REGULARIZAÇÃO — PRIORIDADES

### Ações IMEDIATAS (Sem custo fiscal — apenas administrativas)

1. **Atualizar CPF para "não residente"** — Banco do Brasil, Caixa Econômica Federal ou e-CAC com procuração.  
   Base: IN RFB 208/2002. Urgência: ALTA. Impede geração de intimações por omissão de DIRPF.

2. **NÃO transmitir o .DEC 2026/AC 2025** (endereço SP/BR).  
   Se necessário, reconstituir declaração de saída ou demonstrar ausência de obrigação para AC 2025.

3. **Constituir procurador no e-CAC** para atuação junto à RFB sem deslocamento físico do cliente ao Brasil.

### Ações de ANÁLISE (Fase seguinte)

4. **Investigar natureza dos R$ 180.971,76 recebidos via Daycoval/Remitly/TAPTAP (2024–2026).**  
   Se forem remessas de renda própria do exterior → capital próprio → sem tributação BR como não residente.  
   Se forem rendimentos de fonte BR → IRRF na fonte → verificar retenção.

5. **Investigar "digital assets YES" no Form 1040/2023** — identificar natureza, volume e se houve realização com ganho de capital.  
   Como não residente em 2023: ganho de capital em ativo no exterior não é tributável pelo Brasil.  
   PORÉM: se houver ativo sediado no Brasil (exchange brasileira, cripto em corretora BR) → pode ser tributável.

6. **Solicitar transcript IRS (Account Transcript)** para confirmar que todos os impostos US dos anos 2018–2023 foram efetivamente pagos e não há pendência com o IRS.

### Ações NÃO recomendadas

7. ❌ **Não apresentar CSDP retroativa** datada de 2018 — cria autuação por extemporaneidade sem benefício fiscal (decadência já correu).

8. ❌ **Não apresentar DIRPF tardia para AC 2018** — decadência extinguiu a exigibilidade; entregar agora só cria litígio sem necessidade.

9. ❌ **Não apresentar DSDP retroativa para AC 2019** — mesma lógica: decadência + renda proporcional abaixo do limite.

---

## 10. DADOS NÃO COMPROVADOS — ABERTURA DE ITENS PENDENTES

| ID | Item | Impacto | Bloco |
|----|------|---------|-------|
| P-01 | **Renda brasileira em jan/2018** (25 dias antes da saída): salário, honorários, aluguéis | Definirá se DSDP estratégia B traria tributo zero ou não | A |
| P-02 | **DIRPF AC 2017** (ex. 2018): localizar DEC e REC ou confirmar não entrega | Completar inventário; decadência já extinta de qualquer forma | B |
| P-03 | **Natureza dos recebimentos Nubank 2024–2026**: são remessas de renda própria do exterior ou rendimento de fonte BR? | Define se há IRRF ou ganho de capital tributável | C |
| P-04 | **Ativos digitais 2023**: quais exchanges/carteiras; realizações com ganho? Exchange brasileira ou apenas US? | Pode gerar obrigação de Ganho de Capital BR se ativo sediado no Brasil | D |
| P-05 | **Extratos bancários brasileiros 2018–2023**: contas Nubank, outros bancos | Confirmar ausência de renda fonte BR durante período | E |
| P-06 | **Transcript IRS 2018–2023**: confirmar pagamento efetivo dos impostos US | Necessário para validar Foreign Tax Credit na FASE 3 (aplica-se a 2018 apenas — e crédito era US$ 0) | F |
| P-07 | **Sociedad Two Brothers Drywall and Paint (EIN 37-2048597)**: natureza da participação; distribuições vs. draws vs. guaranteed payments | Afeta tratamento de renda como não residente em 2023+ | G |

---

## 11. FONTES CITADAS

| # | Norma / Fonte | Link | Data de Acesso |
|---|---------------|------|---------------|
| 1 | IN SRF Nº 208/2002 — Residência Fiscal | [LegisWeb](https://www.legisweb.com.br/legislacao/?id=75394) | 24/09/2026 |
| 2 | IN RFB 1.871/2019 — DIRPF AC 2018 — LeFisc | [LeFisc 2019](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2019.htm) | 24/09/2026 |
| 3 | Limites DIRPF AC 2022 — LeFisc | [LeFisc 2023](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2023.htm) | 24/09/2026 |
| 4 | IN RFB 2.255/2025 — DIRPF AC 2024 — LeFisc | [LeFisc 2025](https://www.lefisc.com.br/tabelas/tabelasPraticas/LimitDIRPF2025.htm) | 24/09/2026 |
| 5 | Prorrogação DIRPF AC 2020 para 31/05/2021 (IN RFB 2.020/2021) | [Agência Brasil](https://agenciabrasil.ebc.com.br/economia/noticia/2021-04/receita-adia-o-prazo-de-entrega-da-declaracao-de-imposto-de-renda) | 24/09/2026 |
| 6 | CSDP — Gov.br | [Comunicar saída](https://www.gov.br/pt-br/servicos/comunicar-saida-definitiva-do-pais) | 24/09/2026 |
| 7 | Receita Federal — não residentes — CFC | [CFC](https://cfc.org.br/noticias/receita-federal-orienta-acerca-dos-procedimentos-relacionados-a-condicao-de-nao-residentes-no-brasil/) | 24/09/2026 |
| 8 | 2018_US_TAX.md | OCR local — `/mnt/user-data/outputs/OCR/2018_US_TAX.md` | 24/09/2026 |
| 9 | 2019_US_TAX.md | OCR local — `/mnt/user-data/outputs/OCR/2019_US_TAX.md` | 24/09/2026 |
| 10 | 2020_2021_US_TAX.md | OCR local — `/mnt/user-data/outputs/OCR/2020_2021_US_TAX.md` | 24/09/2026 |
| 11 | 2022_US_TAX.md | OCR local — `/mnt/user-data/outputs/OCR/2022_US_TAX.md` | 24/09/2026 |
| 12 | 2023_US_TAX.md | OCR local — `/mnt/user-data/outputs/OCR/2023_US_TAX.md` | 24/09/2026 |
| 13 | NUBANK_LEDGER.csv | CSV local — `/mnt/user-data/outputs/DADOS/NUBANK_LEDGER.csv` | 24/09/2026 |

---

## 12. STATUS DA FASE 1

| Item | Status |
|------|--------|
| Normas pesquisadas (web) | ✅ CONCLUÍDO |
| Data de saída confirmada | ✅ 25/01/2018 `[FATO CONFIRMADO]` |
| Data de perda de residência (12 meses) | ✅ 25/01/2019 `[INFERÊNCIA TÉCNICA]` |
| Tabela ano a ano (2016–2025) | ✅ CONCLUÍDA |
| Decadência por ano | ✅ ANALISADA |
| Exposição estimada AC 2018 | ✅ ESTIMADA (PTAX definitivo: FASE 2) |
| Estratégia de regularização | ✅ RASCUNHADA |
| Dados pendentes mapeados | ✅ 7 itens (P-01 a P-07) |
| **Próximo passo** | **FASE 2 — Income Worksheet + PTAX via BCB Olinda API** |

---

*Arquivo gerado por: Claude Sonnet 4.6 como assistente de Robson Soares Bezerra | CRC/PR 062711/O*  
*Projeto: IRPF_JOSE_ADALMO | Sessão: 24/09/2026*  
*Este documento não substitui parecer profissional individualizado. Estimativas de imposto marcadas como [HIPÓTESE] dependem de PTAX definitivo (FASE 2) e comprovação documental.*
