# Ghost Jobs: measurement and results

[Read the plain-language report](https://hunternbh.github.io/ghost-jobs-results/).

The report explains how applicants’ interview accounts are coded, how the company-year measure is calculated, and what the firm-level tests show. The same aggregate results are used in the local LaTeX manuscript.

These are **provisional results based on automated coding**. Independent human validation is pending. The measure captures perceived recruitment experiences, not verified employer intent or national fake-vacancy prevalence. Confidence intervals condition on the automated labels.

The main linked sample contains 399,200 English interview reviews across 338 companies with USD financial data. Estimation samples vary by outcome and controls. All eligible offer outcomes enter the denominator.

Files include the HTML report, displayed tables, model coefficients and confidence intervals, analysis specification, and statuses for unavailable tests. No raw reviews, private emails, API credentials, or financial microdata are published.

The acquisition-variable reference is Adams et al. (2025), *Post-Acquisition Accounting Integration and M&A Outcomes*, [SSRN 5203945](https://doi.org/10.2139/ssrn.5203945), previously circulated under a longer title. This is cited as a working paper; a Management Science publication has not been established.


The study’s primary focus is identification and validation. Gutiérrez, Lourie, Nekrasov, and Shevlin (2020), DOI 10.1287/mnsc.2019.3450, is the confirmed benchmark. The user-confirmed validation removes or discounts suspected ghost postings and tests whether adjusted postings recover the positive Lourie hiring/performance relations. This signal-recovery comparison has not been estimated because active-posting histories are missing. See validation_protocol.json and classification_stability.json. Existing company-outcome tables remain supplementary.
