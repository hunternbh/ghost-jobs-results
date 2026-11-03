# Ghost Jobs: measurement and results

[Read the plain-language report](https://hunternbh.github.io/ghost-jobs-results/).

The report explains how applicantsÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ interview accounts are coded, how the company-year measure is calculated, and what the firm-level tests show. The same aggregate results are used in the local LaTeX manuscript.

These are **provisional results based on automated coding**. Independent human validation is pending. The measure captures perceived recruitment experiences, not verified employer intent or national fake-vacancy prevalence. Confidence intervals condition on the automated labels.

The main linked sample contains 399,200 English interview reviews across 338 companies with USD financial data. Estimation samples vary by outcome and controls. All eligible offer outcomes enter the denominator.

Files include the HTML report, displayed tables, model coefficients and confidence intervals, analysis specification, and statuses for unavailable tests. No raw reviews, private emails, API credentials, or financial microdata are published.

The acquisition-variable reference is Adams et al. (2025), *Post-Acquisition Accounting Integration and M&A Outcomes*, [SSRN 5203945](https://doi.org/10.2139/ssrn.5203945), previously circulated under a longer title. This is cited as a working paper; a Management Science publication has not been established.


The studyÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢s primary focus is identification and validation. GutiÃƒÆ’Ã‚Â©rrez, Lourie, Nekrasov, and Shevlin (2020), DOI 10.1287/mnsc.2019.3450, is the confirmed benchmark. The design distinguishes broader posting-to-hire and interview-stage ghost proxies. It replicates the positive Lourie posting/future-operations relation, then tests negative posting interactions with each ghost proxy. The broader measure and benchmark/interactions remain unestimated because posting and hiring histories are missing. Posting counts are not mechanically discounted with interview shares. See validation_protocol.json and classification_stability.json. Existing company-outcome tables remain supplementary.


Posting tests audited October 31, 2026: 96 corrected fits in `posting_test_results.json`; company links, fiscal timing and sample attrition in `posting_test_methods.json` and `posting_audit_results.json`. Broad employment, spending and sales relationships are positive; the primary original-review interactions remain inconclusive. All 72 earlier restricted-sample fits remain in `posting_test_results_initial.json`. Original review labels and scores are unchanged. Worker-start data are still needed for the posting-to-hiring measure.


Revelio interview-review posting interactions now use the completed user-authorized GPT-6 Luna Batch classification. All 80 fits are in `loujaina_posting_results.json`; methods, sample coverage and the $15 budget summary are separate downloads. The main tests do not establish the expected weakening of the posting-to-growth relationship at higher ghost scores. Earlier original-sample tables and classified-subset estimates are retained.


A measurement follow-up retains 288 additional diagnostic fits in `measurement_followup_results.json`, with no significant negative interactions. A fixed separate-review check in the broader Revelio data shows higher direct-unavailability report rates at higher training scores in both directions; all 12 adjusted comparisons, including inconclusive within-company estimates, are in `broader_review_agreement_results.json`. This supports recurring applicant reports and does not establish the Lourie attenuation prediction. No additional API calls were made.


## November 3 update

The current page reports original-score posting/earnings comparisons and the first determinant analysis. The previous report and all its tables are preserved in `report-before-2026-11-03.html`; previous JSON files remain unchanged. New aggregate outputs are `first_score_comparison.json`, `first_score_stability.json`, `determinants_results.json`, `recruitment_role_results.json`, and `current_study_methods.json`. `study_framework.svg` maps identification, operating checks, three potential determinants and the worker-start extension. No new paid API calls.


The separate-review accepted-offer check is in `accepted_offer_results.json` and `accepted_offer_methods.json`: all 32 fixed-menu models are retained. Raw accepted-offer rates decline at higher scores; adding scoring-review offer composition reverses the relationship. Accepted outcomes do not verify worker starts. No paid API calls.
