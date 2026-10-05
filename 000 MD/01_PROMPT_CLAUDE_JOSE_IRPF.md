# CLAUDE TASK --- JOSE IRPF

## ROLE

Act as a senior Brazilian tax-accounting analyst specialized in IRPF,
Brazilian tax residence, bank reconciliation and financial forensic
analysis.

Use rigorous source-based analysis. Do not invent facts.

## SOURCE

Use `02_BACKUP_JOSE_IRPF_COMPLETO.md` as the working source for all
extracted data and project context.

## PRIMARY OBJECTIVE

Reconstruct and analyze ALL receipt/entry information in the backup.

Produce:

  ---------------------------------------------------------------------------------
  Date        Payer /     Receiver /      Amount (BRL) Classification   Source /
              Origin      Destination                                   Evidence
  ----------- ----------- ------------- -------------- ---------------- -----------

  ---------------------------------------------------------------------------------

## REQUIRED

1.  Consolidate by payer, date, amount and receiver.
2.  Calculate subtotals by payer.
3.  Calculate totals by month and year.
4.  Separate:
    -   third-party receipts;
    -   own-account transfers;
    -   international remittances;
    -   RDB applications/redemptions;
    -   PIX reversals/estornos;
    -   reimbursements;
    -   unidentified/pending items.
5.  Never classify a bank entry as taxable income merely because money
    entered the account.
6.  Flag duplicates, reversals, internal transfers and documentary gaps.
7.  For material/uncertain entries, state the missing evidence.

## IRPF PROJECT CONTEXT

Use exactly as documented: - Reported departure from Brazil:
25/01/2018. - Last DIRPF: Exercise 2018 / Calendar Year 2017. - CSDP:
reported as not filed. - DSDP: reported as not filed.

Do not automatically conclude tax residence, taxable income, omission or
tax liability.

## DATA QUALITY

-   Preserve source names, dates and amounts.
-   Do not silently merge or correct transactions.
-   Keep reversals separate from genuine receipts.
-   Keep own-account transfers separate from third-party receipts.
-   Keep remittance intermediaries separate from the economic source
    until documentary evidence establishes the origin.
-   If unsupported, write:
    `DADO NÃO COMPROVADO PELOS DOCUMENTOS DISPONÍVEIS`.

## OUTPUT

### 1. EXECUTIVE SUMMARY

### 2. CONSOLIDATED RECEIPTS

### 3. TOTALS BY PAYER

### 4. TOTALS BY MONTH/YEAR

### 5. CLASSIFICATION

### 6. DOCUMENTARY PENDING

### 7. IRPF RECONCILIATION ISSUES

### 8. AUDIT TRAIL

For important conclusions, identify the source file/page or source
reference available in the backup.

## RESTRICTIONS

Do not invent transactions, purposes, legislation, thresholds, tax
calculations or documentary evidence.

Do not treat: - every PIX as income; - every remittance as income; - RDB
redemption as new income; - a reversal as a new receipt.

If information is insufficient, state:
`DADO NÃO COMPROVADO PELOS DOCUMENTOS DISPONÍVEIS`.

## FIRST TASK

First reconstruct the complete receipt ledger from the backup. Then
identify inconsistencies, missing documents and transactions requiring
further investigation. Only after that discuss possible IRPF treatment.
