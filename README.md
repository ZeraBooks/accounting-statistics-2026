# Accounting and bookkeeping statistics 2026

U.S. accountants and auditors earned a median $83,680 a year in May 2025 and
held about 1.6 million jobs, projected to grow 5% by 2035.
Bookkeeping clerks earned a median $50,670 and their jobs are projected to fall
6%. This repository has 51 figures like these in one CSV, each linked to its
BLS, Census, SBA or IRS source.

## Files

| File | What it is |
|---|---|
| `data/statistics.csv` | 51 statistics, one per row: `id`, `statistic`, `value`, `unit`, `period`, `source_name`, `source_url`, `notes`. Values are plain numbers so they sort and sum. |
| `CITATION.cff` | Citation details for this collection. |

## Key figures

| Statistic | Value | Period | Source |
|---|---|---|---|
| Median annual wage, accountants and auditors | $83,680 | May 2025 | [BLS OOH](https://www.bls.gov/ooh/business-and-financial/accountants-and-auditors.htm) |
| Mean annual wage, accountants and auditors | $94,750 | May 2025 | [BLS OEWS](https://www.bls.gov/news.release/ocwage.t01.htm) |
| Accountant and auditor jobs, including self-employed | 1,595,200 | 2025 | [BLS OOH](https://www.bls.gov/ooh/business-and-financial/accountants-and-auditors.htm) |
| Projected change, accountants and auditors | +5% (79,400 jobs) | 2025 to 2035 | [BLS OOH](https://www.bls.gov/ooh/business-and-financial/accountants-and-auditors.htm) |
| Average yearly openings, accountants and auditors | 115,300 | 2025 to 2035 | [BLS OOH](https://www.bls.gov/ooh/business-and-financial/accountants-and-auditors.htm) |
| Median annual wage, bookkeeping, accounting and auditing clerks | $50,670 | May 2025 | [BLS OOH](https://www.bls.gov/ooh/office-and-administrative-support/bookkeeping-accounting-and-auditing-clerks.htm) |
| Projected change, bookkeeping clerks | -6% (85,600 jobs) | 2025 to 2035 | [BLS OOH](https://www.bls.gov/ooh/office-and-administrative-support/bookkeeping-accounting-and-auditing-clerks.htm) |
| Average yearly openings, bookkeeping clerks | 144,100 | 2025 to 2035 | [BLS OOH](https://www.bls.gov/ooh/office-and-administrative-support/bookkeeping-accounting-and-auditing-clerks.htm) |
| Employees, accounting, tax, bookkeeping and payroll services (NAICS 5412) | 1,075,600 | Sep 2026, preliminary | [BLS CES](https://data.bls.gov/timeseries/CEU6054120001) |
| Firms in NAICS 5412 | 120,085 | 2022 | [Census SUSB](https://www.census.gov/data/tables/2022/econ/susb/2022-susb-annual.html) |
| NAICS 5412 firms with fewer than 5 employees | 88,381 (73.6%, our math) | 2022 | [Census SUSB](https://www.census.gov/data/tables/2022/econ/susb/2022-susb-annual.html) |
| CPA firms (NAICS 541211) | 50,885 | 2022 | [Census SUSB](https://www.census.gov/data/tables/2022/econ/susb/2022-susb-annual.html) |
| Bookkeeping and other accounting firms (NAICS 541219) | 45,390 | 2022 | [Census SUSB](https://www.census.gov/data/tables/2022/econ/susb/2022-susb-annual.html) |
| Small businesses in the U.S. | 36,207,130 | 2026 profile | [SBA Office of Advocacy](https://advocacy.sba.gov/wp-content/uploads/2026/02/FINAL_FAQsAboutSmallBusiness_2026_012826.pdf) |
| People with a current IRS preparer number (PTIN) for 2026 | 886,338 | As of Sep 1 2026 | [IRS](https://www.irs.gov/tax-professionals/return-preparer-office-federal-tax-return-preparer-statistics) |

## How to use it

1. Open `data/statistics.csv` in Excel or Google Sheets, or load it with any
   CSV reader. Filter on the `id` prefix to get one group: `pay`, `outlook`,
   `firms`, `clients` or `counts`.
2. Read the `unit` column before you quote a number. Receipts for NAICS 5412
   are in thousands of dollars, as Census publishes them; some other dollar
   figures are in billions.
3. Quote the original source and period next to any figure, then cite this
   collection.

## Why the counts of accountants differ

Three BLS programs count accountants and auditors three ways, and none is
wrong:

| Source | Accountants and auditors | What it counts |
|---|---|---|
| Occupational Outlook Handbook (2025) | 1,595,200 | All jobs, including self-employed |
| OEWS (May 2025) | 1,449,500 | Wage-and-salary jobs reported by employers |
| Current Population Survey (2025) | 1,766,000 | People who say this is their job, from a household survey |

Wages match between the Handbook and OEWS because the Handbook uses OEWS wages.
The CPS 2025 averages leave out October.

## Notes on the data

- Every figure was checked against its primary source on November 4, 2026.
- Percentages noted as "our math" are computed from the cited table and say so
  in the `notes` column.
- None of these are ZeraBooks figures.
- BLS publishes new wage data each spring and new projections each fall, so
  check the source page before quoting a figure next year.

## Learn more

The same figures with context: [Accounting and bookkeeping statistics 2026](https://www.zerabooks.com/research/accounting-bookkeeping-statistics-2026) on zerabooks.com. Staffing figures for firms: [CPA shortage statistics](https://www.zerabooks.com/research/cpa-shortage-statistics).

## License

The content and data in this repository are licensed under
[CC BY 4.0](LICENSE). Free to use and adapt with credit to ZeraBooks.
The underlying figures come from U.S. government sources and remain theirs.

Maintained by ZeraBooks.
