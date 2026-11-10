# Comparable Company Analysis – Apple vs Peers

A trading comparables valuation of **Apple** against **8 large technology peers**: Microsoft, Alphabet, Amazon, Meta, NVIDIA, Tencent, Samsung Electronics and Adobe. FactSet market data, 2022.

## Build
- **Database** of FactSet market data for 37 companies – the only typed numbers
- **Trading Comps**: peers pulled with INDEX/MATCH; revenue growth, EBITDA and net margins; EV/Revenue, EV/EBITDA and P/E for 2022E and 2023E; peer min, mean, median and max
- **Valuation**: implied enterprise value, equity value and share price for Apple from each multiple
- **Charts**: peer EV/EBITDA and P/E, growth vs margin, and a football-field chart of the implied price range
- **PDF report** with findings, tables and charts

## Key findings
- Peer median 2023E multiples: **14.0x EV/EBITDA** and **20.8x P/E**
- At peer medians, Apple's implied price is **$103–132** vs a market price of **$154** – a premium of about **33%**
- The premium is not explained by growth or margins: Apple's 2023E revenue growth is 5.0% vs a 14.0% peer median, and its EBITDA margin 32.4% vs 42.9%

## Corrections to the first version
- EBITDA-based equity value now adds cash and subtracts debt (it previously added debt and subtracted the share count)
- Apple EPS now comes from net income ÷ diluted shares (6.35) instead of a typed 3.55
- The date now shows the real data period (2022), not July 2026

## Files
- `Comparable_Company_Analysis.xlsx`
- `Comparable_Company_Analysis_Report.pdf`

## Tools
MS Excel (INDEX/MATCH, valuation multiples, charts) · PDF report

## Note
Market data: FactSet download, 2022. For learning, not investment advice.

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
