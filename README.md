# 🇳🇿 NZ Income Tax Refund Calculator

A free, fully client-side calculator to estimate your New Zealand income tax result — no IRD website needed.

👉 **[Try it live](https://derickscorrea.github.io/nz-tax-calculator/)**
---

## Features

### ✅ Income types supported
| Income type | Amount | Deductions |
|---|---|---|
| Salary, wages, benefits & taxable pensions | ✅ | ✅ PAYE |
| NZ interest received | ✅ | ✅ RWT |
| Dividends treated as interest | ✅ | ✅ RWT + imputation credits |
| Māori authority distributions | ✅ | ✅ credits (19.5%) |
| Portfolio investment entity (PIE) income | ✅ | ✅ PIE tax paid |

### ✅ Automatic calculations
| Feature | Detail |
|---|---|
| Tax on taxable income | Official NZ tax brackets — full breakdown shown |
| Tax year toggle | 2024–25 (blended mid-year brackets) and 2025–26 |
| ACC earners' levy | 1.60% (2024–25) or 1.67% (2025–26) of gross salary |
| PIR auto-suggestion | Suggested from total income, manual override supported |
| PIE credit / debit | PIE tax paid vs correct tax at your PIR |
| IETC | Up to $520 for incomes $24,000–$48,000 |
| Māori authority tax credit | 19.5% of distributions |
| Charitable donation rebate | 33.33% of donations to approved NZ charities |
| Working for Families | Manual input field |

### ✅ UX & utility
- 🌙 **Dark mode** — toggle with one click, preference saved
- 🖨 **Print / Save as PDF** — clean print layout with print-optimised CSS
- 📋 **Copy result** — copies a formatted summary to clipboard
- 💾 **Auto-save** — form data saved per tax year in your browser (localStorage)
- ↺ **Reset** — clear all fields for the current tax year with one click
- 📱 **Responsive** — works on mobile and desktop

---

## Tax brackets

### 2025–26 (1 April 2025 to 31 March 2026)
| Income | Rate |
|---|---|
| Up to $15,600 | 10.5% |
| $15,600 – $53,500 | 17.5% |
| $53,500 – $78,100 | 30.0% |
| $78,100 – $180,000 | 33.0% |
| Over $180,000 | 39.0% |

### 2024–25 (blended — tax change 31 July 2024)
IRD changed the brackets mid-year on 31 July 2024. The calculator applies a weighted blend:
- **121/366** days at the old brackets (up to $14k / $48k / $70k / $180k)
- **245/366** days at the new 2025–26 brackets

---

## Auto PIR logic

Your PIR is estimated from your total income using IRD's rules:
| Total income | Suggested PIR |
|---|---|
| Up to $14,000 | 10.5% |
| $14,001 – $48,000 | 17.5% |
| Over $48,000 | 28% |

> **Note:** IRD determines your PIR based on the *lower* of your two most recent years' taxable income. The calculator uses your current year as an estimate. Always verify your actual PIR in myIR under **My profile → Tax rates** and use the manual override if needed.

---

## How to use

1. Select your **tax year** (2024–25 or 2025–26)
2. Log in to [myIR](https://myir.ird.govt.nz) → **Income Summary** → **Last income tax year**
3. Open the **Summary by type** table
4. Enter each row's **Amount** and **Deductions / Imputation credits**
5. Add charitable donations and Working for Families credits if applicable
6. Check the auto-suggested PIR and override if needed
7. Your estimated tax result appears instantly

---

## Privacy

All calculations happen **entirely in your browser**. No data is collected, stored, or sent anywhere. There is no backend or server. Form data is saved to your browser's localStorage only.

---

## Disclaimer

This calculator is a **guide only**. Your official tax result is determined by Inland Revenue (IRD). Always verify your assessment at [ird.govt.nz](https://www.ird.govt.nz).

---

## Contributing

Found a bug or know of a rate change? Open an issue or submit a pull request.
