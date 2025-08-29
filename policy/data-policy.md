# Data Policy

## Major reforms

### Create a national ID system and corresponding data exchange layer like Estonia's e-ID & X-Road

- Identity verification and poor data interoperability is a huge administrative burden on both the public and private sector, and a huge reason why is our lack of a single standardized digital ID
- [Estonia's digital government reforms from the 90s have had a huge impact](https://vabamu.ee/wp-content/uploads/2025/04/Government-DigitizationEfficiency-and-Performance-in-the-US-and-Estonia.pdf):
  - Saves roughly 2% of GDP yearly
  - Uses once-only process for public sector data entry
  - Allows audit of data access
  - Everything from real estate transactions to paying taxes is substantially faster. Allows Estonia to have a leaner bureuacracy and consequently a much lower tax-to-GDP than peer countries.
  - Starting to be emulated by other countries (see: [India Stack](https://www.tigerfeathers.in/p/the-internet-country))
- [McKinsey projects a 4% GDP boost from widespread adoption of a national digital ID in the US](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/digital-identification-a-key-to-inclusive-growth)
  - Given the painful and protracted REAL ID process, might be hard politically to implement a national ID.
  - State level mobile driver licenses (mDL) might be a test bed. NYC's [MyFile](https://www.newamerica.org/digital-impact-governance-initiative/reports/my-file-proof-of-concept/) is another example.
  - IRS data sharing limitations (section 6103) might limit potential in some public sector contexts

### Increase funding to Federal Statistical System and ensure professional autonomy
- [ASA's report on state of the FSS](https://www.amstat.org/docs/default-source/amstat-documents/the-nation%27s-data-at-risk---report.pdf?v=0321)
  - The 13 FSS agencies need to be granted full professional autonomy in hiring, contracts, staffing levels, etc.
  - Given Trump's meddling in BLS, likely want to insulate them from executive authority. Consolidate agencies in the Fed or Congressional support offices?
  - Evidence Act was supposed to improve data sharing but still many barriers. Additionally, mandating data sharing from state/local agencies as a condition of federal grants could help
  - Response rates are declining, likely requiring bigger incentives & greater coordination with private sector data sources
- Many policymaking data needs are still unmet. Ex: supply chain data, New Immigrant Survey, crime data. [IFP article with more examples](https://ifp.org/sweat-the-small-stuff/).
- BLS, BEA, etc data has massive impact on private sector decision-making. [Exact value hard to estimate](https://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.33.1.131) but probably in the hundreds of billions to trillions per year range.

### End differential privacy at the Census Bureau
- Meant as a privacy protection measure but [harms Census data accuracy far worse than older approaches to disclosure avoidance](https://osf.io/preprints/socarxiv/69mtk_v1)
  - Concern was that older data swapping method would allow microdata to be individually identifiable, DP adds artificial noise to produce "synthetic data" that is harder to identify
  - Outside data sources have made this privacy concern moot. Privacy is largely dead in the digital era anyway.
  - Will also degrade accuracy of ACS
  - Enumerated census is more accurate than administrative data and is a unique advantage of the US over other OECD censuses
- Use of DP is not mandated by law but a legal interpretation of the Census's mandate for disclosure avoidance

## Minor reforms

### Use intercensal data collection as a form of fiscal stimulus/automatic stabilizer
- [State censuses used to be more common, but largely eliminated Special Federal Census](https://medium.com/migration-issues/state-censuses-and-the-jobs-guarantee-1c5dacfc9a4a)
- Not a fan of jobs guarantee/fiscal stimulus in most contexts but this would have greater ROI than many low value infrastructure projects that get approved during recessions
