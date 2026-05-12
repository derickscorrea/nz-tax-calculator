# 🇳🇿 NZ Income Tax Refund Calculator

A free, fully client-side calculator to estimate your New Zealand income tax result for the year ended **31 March 2026** — no IRD website needed.

👉 **[Try it live](https://derickscorrea.github.io/nz-tax-calculator/)** ← replace with your GitHub Pages URL

---

## What it does

Fills the gap between receiving your myIR "Summary by type" screen and waiting for your official IRD assessment. Enter your income figures and get an instant estimate of whether you're owed a refund or have a small balance to pay.

### Automatic calculations
- **Tax on taxable income** — applies the official 2025–26 NZ tax brackets with a full bracket breakdown
- **ACC earners' levy** — 1.67% of gross salary
- **PIE credit / debit** — based on your selected PIR (10.5%, 17.5% or 28%)
- **Independent Earner Tax Credit (IETC)** — up to $520 for incomes between $24,000–$48,000

### Income types supported
| Income type | Amount | Deductions |
|---|---|---|
| Salary, wages, benefits & taxable pensions | ✅ | ✅ PAYE |
| NZ interest received | ✅ | ✅ RWT |
| Dividends treated as interest | ✅ | ✅ RWT + imputation credits |
| Portfolio investment entity (PIE) income | ✅ | ✅ PIE tax paid |

### 2025–26 Tax brackets (built-in)
| Income | Rate |
|---|---|
| Up to $15,600 | 10.5% |
| $15,600 – $53,500 | 17.5% |
| $53,500 – $78,100 | 30.0% |
| $78,100 – $180,000 | 33.0% |
| Over $180,000 | 39.0% |

---

## How to use

1. Log in to [myIR](https://myir.ird.govt.nz) → **Income Summary** → **Last income tax year**
2. Open the **Summary by type** table
3. Enter each row's **Amount** and **Deductions / Imputation credits** into the calculator
4. Select your **PIR** (find it in myIR under My profile → Tax rates)
5. Your estimated tax result appears instantly

---

## Privacy

All calculations happen **entirely in your browser**. No data is collected, stored, or sent anywhere. There is no backend.

---

## Disclaimer

This calculator is a **guide only**. Your official tax result is determined by Inland Revenue (IRD). Always verify your assessment at [ird.govt.nz](https://www.ird.govt.nz).

Tax rates and levies are based on the 2025–26 tax year:
- Income tax brackets effective 1 April 2025
- ACC earners' levy: 1.67%

---

## Contributing

Found a bug or know of a rate change? Feel free to open an issue or submit a pull request.
