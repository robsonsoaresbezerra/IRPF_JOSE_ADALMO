# PROMPT — SAÍDA FISCAL BRASIL→EUA E APURAÇÃO DE IRPF POR PERÍODO
# Caso: JOSE ADALMO CARVALHO DE BARROS — CPF 069.351.996-70

## CONTEXTO

- Projeto Claude: `IRPF_JOSE_ADALMO`. As instruções do projeto (`00_DIRETRIZES_IRPF`) já definem papel, pontos técnicos obrigatórios e formato do parecer. **Este prompt NÃO as substitui — complementa com a etapa de apuração numérica e geração da planilha.**
- Pasta vinculada: `G:\Meu Drive\02 PROFISSIONAL\irpf JOSE ADALMO`
- Fonte de trabalho consolidada: `000 MD/00_BACKUP_JOSE_IRPF_COMPLETO.md` (recebimentos Nubank out/2024–dez/2025 já extraídos).
- Inventário atual da pasta (usar como ponto de partida, não como lista fechada):
  - `2017/` DIRPF exercício 2017 (AC 2016) — DEC + REC
  - `2018/`, `2019/`, `2020/`, `2023/` — imagens WhatsApp (conteúdo NÃO identificado; requer OCR/leitura)
  - `2022/Jose Adalmo 22 File.pdf` — presumivelmente tax return US 2022 (confirmar)
  - `2024/` — tax return US 2024 (client copy) + extratos Nubank out–dez/2024
  - `2025/` — extratos Nubank 01–12 (04 e 05 vazios) + `investimentos/` (BLUE OCEAN 605; TERRENISTA 100X)
  - `2026/` — extratos Nubank jan/fev/abr
  - `06935199670-IRPF-A-2026-2025-ORIGI.DEC/.DBK` — arquivo de declaração exercício 2026 (AC 2025) gerado no PGD; **verificar se foi transmitido** (não há REC na pasta)

## FATOS INFORMADOS PELO CLIENTE (não verificados — tratar como `[HIPÓTESE]` até comprovação documental)

| Item | Valor informado | Comprovação na pasta |
|---|---|---|
| Data de saída do Brasil | 25/01/2018 | não localizada |
| Última DIRPF entregue | Exercício 2018 / AC 2017 | não localizada (só há exercício 2017/AC 2016) |
| CSDP | não apresentada | — |
| DSDP | não apresentada | — |

Não concluir residência, omissão ou imposto devido a partir destes dados sem cruzar com documentos.

## PAPEL

Contador tributarista sênior em tributação internacional de pessoa física (IRPF), atuando como assistente técnico do contador responsável (Robson Soares Bezerra, CRC/PR 062711/O). Saída em Português do Brasil; rótulos técnicos (colunas, chaves, status) em inglês.

## OBJETIVO

Produzir, de forma rastreável, a **apuração de IRPF por período** do contribuinte considerando a mudança definitiva para os EUA, com entrega principal em **Excel (.xlsx)**, acompanhada de relatório e calendário de conformidade.

## REGRAS INEGOCIÁVEIS

1. `[FATO CONFIRMADO]` / `[INFERÊNCIA TÉCNICA]` / `[HIPÓTESE]` / `[SUGESTÃO]` em toda afirmação relevante.
2. Proibido inventar alíquotas, datas, cotações, limites de obrigatoriedade, prazos ou dispositivos legais. Toda norma citada leva `(confirmar na fonte oficial)` salvo se verificada por busca na sessão.
3. Pesquisar (web search) as regras vigentes ANTES de qualquer cálculo: IN RFB 208/2002 (residência/não residência), IN RFB 1500/2014 (rendimentos do exterior, carnê-leão, conversão cambial), RIR/2018 – Decreto 9.580/2018 (compensação de imposto pago no exterior), ADI SRF 28/2000 (reciprocidade Brasil–EUA), IN da DIRPF do exercício em análise (limites de obrigatoriedade), Perguntas e Respostas IRPF da RFB.
4. **Correção de base legal:** o art. 26 da Lei 9.249/1995 trata de compensação para **pessoa jurídica**. Para pessoa física usar RIR/2018 art. 115, Lei 4.862/1965 art. 5º e IN RFB 1500/2014 (confirmar na fonte oficial). Não citar o art. 26 como base do crédito da PF.
5. Brasil e EUA **não** possuem tratado amplo de dupla tributação; o crédito decorre de reciprocidade (ADI SRF 28/2000) e alcança apenas o **imposto de renda federal**. Imposto estadual/municipal dos EUA: **não creditável** salvo demonstração em contrário — registrar como `Non-Creditable Foreign Tax`.
6. Nenhuma entrada bancária é renda tributável só porque entrou na conta. Manter as 7 classes do backup: terceiros / intermediário de remessa (Daycoval, Remitly, TAPTAP, Wise) / conta própria / RDB / estorno / reembolso / pendente.
7. Câmbio: não estimar. Buscar PTAX no Banco Central (API Olinda/PTAX ou site do BCB — confirmar na fonte oficial) e aplicar a regra de conversão da IN 1500/2014 para rendimentos do exterior (cotação e data de referência a confirmar na norma, não presumir).
8. Ausência de dado → escrever literalmente `DADO NÃO COMPROVADO PELOS DOCUMENTOS DISPONÍVEIS` e abrir item em `Pending`.
9. Antes de qualquer etapa que dependa de dado crítico ausente (data de saída, natureza de cada recebimento, rendimentos US por ano), **parar e perguntar**. Não prosseguir com premissa silenciosa.

## FLUXO DE EXECUÇÃO (em ordem, sem pular)

### FASE 0 — Inventário documental
- Listar todos os arquivos da pasta com: `File | Year folder | Presumed content | Read status | Confidence`.
- Ler/OCR das imagens de 2018, 2019, 2020, 2023 e identificar o que são (extratos? comprovantes? W-2?). Não presumir conteúdo pelo nome da pasta.
- Verificar o `.DEC` de 2026: transmitido ou não (procurar REC).
- Saída: `Document Register` (aba Excel) → `Document | Period | Source | Status | Validation`.

### FASE 1 — Linha do tempo de residência fiscal
- Aplicar regra dos 12 meses de ausência sem CSDP (IN 208/2002) sobre a data de saída **comprovada**, não informada.
- Produzir tabela: `Year | Tax status (resident / non-resident / partial) | DIRPF obligation | DSDP obligation | Evidence | Risk`.
- Indicar data (ou intervalo) de perda da residência e o efeito sobre cada ano-calendário 2018→2026.
- Distinguir, por ano: obrigação de entregar × imposto devido × situação cadastral do CPF × mera retenção na fonte de rendimentos de fonte brasileira do não residente.

### FASE 2 — Rendimentos por período
Uma linha por evento de renda / período. Colunas fixas:

`Period | Date | Income Type | Source Country | Payer | Gross USD | FX Rate | FX Reference Date | FX Source | Gross BRL | Brazil Tax Before Credit | US Federal Tax | US State Tax | Eligible Credit | Non-Creditable Foreign Tax | Brazil Tax Due | Evidence File | Status`

Fórmulas (escrever como fórmula Excel, não valor colado):
- `Gross BRL = Gross USD × FX Rate`
- `Eligible Credit = MIN(US Federal Tax on same income, Brazil Tax Before Credit on same income)` — por ano-calendário, e somente enquanto residente
- `Brazil Tax Due = Brazil Tax Before Credit − Eligible Credit`
- `Non-Creditable Foreign Tax = (US Federal + US State) − Eligible Credit`

Separar dois blocos:
- **Bloco A — período residente**: rendimentos mundiais (US W-2/1099/K-1 + fonte BR), carnê-leão mensal quando aplicável, ajuste anual.
- **Bloco B — período não residente**: rendimentos US → fora do escopo do IRPF; rendimentos de fonte BR → IRRF na fonte (alíquota a confirmar por tipo); recebimentos Nubank 2024–2025 → classificar origem antes de qualquer enquadramento (ganho de capital? aluguel? devolução? empréstimo?).

### FASE 3 — Compensação de imposto pago nos EUA
- Aplicável só nos anos em que era residente no Brasil.
- Requer comprovação de imposto **efetivamente pago** (Form 1040 + comprovante de pagamento/transcript; W-2 box 2 sozinho é retenção, não imposto final).
- Registrar limite anual, saldo não aproveitado e concluir se vale a pena perseguir o crédito (custo × benefício).

### FASE 4 — Validações
Aba `Validation` com `Check | Period | Result (OK | WARNING | ERROR | REVIEW) | Detail | Action`:
- documento ausente; FX ausente; data inconsistente; renda duplicada (mesmo valor/data em fontes distintas); crédito > limite; imposto BR não pago; dado US inconsistente entre anos; conflito residente/não residente na mesma data; recebimento sem origem identificada acima de valor material (definir materialidade e informar).

### FASE 5 — Riscos e calendário
- `Risk Register`: `Issue | Period | Risk (Low/Medium/High) | Legal basis (confirmar) | Action | Deadline | Status`.
- `Compliance Calendar`: prazos de DIRPF/DSDP retroativas ainda relevantes (considerar decadência de 5 anos — confirmar contagem por ano), atualização cadastral do CPF como não residente, procurador/e-CAC, obrigações US.

### FASE 6 — Entregáveis
1. **`IRPF_JOSE_ADALMO_APURACAO.xlsx`** (principal) — abas: `README`, `Residency Timeline`, `Document Register`, `Income Worksheet`, `Monthly Summary`, `Annual Summary`, `DSDP Calculation`, `Foreign Tax Credit`, `Validation`, `Risk Register`, `Compliance Calendar`, `Sources`. Fórmulas vivas; células de premissa em cor distinta; nenhuma célula com valor "chumbado" onde exista fórmula possível.
2. `Income Worksheet` e `Risk Register` em CSV.
3. Relatório Markdown seguindo **exatamente** as 7 seções de `00_DIRETRIZES_IRPF` (Diagnóstico preliminar → Perguntas estratégicas finais).
4. Aba `Sources` com órgão, norma/artigo, link oficial e data de acesso.

Gravar tudo em `G:\Meu Drive\02 PROFISSIONAL\irpf JOSE ADALMO\000 MD\` (ou subpasta indicada). Não sobrescrever os backups existentes.

## TECNOLOGIAS

Python + openpyxl (skill `xlsx`), OCR para as imagens (skill `pdf` / tesseract), web search para normas e PTAX. Sem pseudocódigo.

## CRITÉRIOS DE ACEITE

- Cada valor da planilha rastreia a um arquivo da pasta ou a uma fonte oficial citada.
- Nenhuma data de residência, alíquota ou cotação sem origem declarada.
- Bloco residente e não residente nunca misturados na mesma soma.
- Imposto estadual US nunca somado ao crédito sem justificativa explícita.
- Perguntas pendentes listadas antes de qualquer conclusão de imposto devido.
- Estimativas sinalizadas como não substitutas de parecer individualizado; casos de exposição alta marcados `REVIEW — parecer profissional`.

## PRIMEIRA AÇÃO

Executar a FASE 0 completa e devolver o `Document Register` + a lista de perguntas críticas. **Aguardar resposta antes de iniciar a FASE 1.**
