# Portfolio guide

Target direction: GenAI / Applied AI Engineering, supported by retail finance,
data engineering and evaluated NLP work. Professional experience is distinct from
independent public portfolio projects.

## Applied AI and NLP

1. [Retail Finance Evidence Copilot](https://github.com/Ashik-Mohammed-S/Project):
   local prototype combining synthetic finance data, allowlisted SQL, retrieval,
   source-linked evidence and abstention. The optional local LLM adapter is
   contract-tested but live generation is not evaluated. The small evaluation
   suite is author-written, not an independent benchmark.
2. [Review Compass](https://github.com/Ashik-Mohammed-S/Sentiment_Based_Product_Recommendation_System):
   sentiment classification, cold-start-aware recommendation evaluation, Flask
   serving, browser inference parity and repository-owned health checks. Gmail
   delivery needs account/secrets activation; the code alone does not establish it.
3. [Complaint Product Classification](https://github.com/Ashik-Mohammed-S/Automatic_Ticket_Classifier):
   supervised source-product labels instead of arbitrary topic IDs; deduplicated
   text and per-class results.
4. [Healthcare Entity Extraction](https://github.com/Ashik-Mohammed-S/Identifying-Entities-in-Healthcare-Data):
   original train/test corpora, aligned tokenization, CRF and exact span metrics.

## Retail finance and Power BI

**[MarginLens](https://github.com/Ashik-Mohammed-S/Marginlens)** connects retail finance reporting with auditable data checks and a native Power BI report.

- [Public web dashboard](https://marginlens-retail-finance.swoonysnipe19.chatgpt.site/): synthetic retail performance, margin bridge, contract exceptions, forecasts and data trust.
- [Power BI screenshot](https://github.com/Ashik-Mohammed-S/Marginlens#power-bi-dashboard-preview): pharmacy economics and coverage/reconciliation pages, validated in Desktop. The report uses aggregates derived from 11,960,653 accepted public Medicaid state records; it does not embed all raw rows.
- Historical source coverage: 2007, 2010, 2018 and Q1–Q2 2024. Suppressed amounts are excluded; reimbursements are not pharmacy profit.
- The screenshot is publicly viewable. The finished PBIX was delivered locally; Power BI Service publication and scheduled cloud refresh are pending.

## Analytical foundations

| Project | Decision or method to inspect |
| --- | --- |
| [Telecom Churn](https://github.com/Ashik-Mohammed-S/Telecom_Churn_prediction) | PR-AUC, recall and train-only preprocessing for an imbalanced target |
| [Lead Conversion](https://github.com/Ashik-Mohammed-S/Lead_score) | Feature availability, excluded outcome-proxy fields and explicit timestamp limitations |
| [Credit Risk EDA](https://github.com/Ashik-Mohammed-S/Credit_EDA_Assignment) | Applicant-level aggregation before joining 1.67M previous applications |
| [Campaign Response EDA](https://github.com/Ashik-Mohammed-S/EDA) | Target rates with segment denominators and post-contact feature caveats |
| [Media View Forecasting](https://github.com/Ashik-Mohammed-S/Media_Company_Data_set) | Available lag features, chronological holdout and persistence comparison |
| [Bitcoin Forecasting](https://github.com/Ashik-Mohammed-S/Bitcoin-Price-Timeforecasting) | Persistence wins; avoid interpreting high price-level R² as forecasting skill |
| [Heart Disease Research](https://github.com/Ashik-Mohammed-S/Heart_disease_prediction) | Modest small-sample metrics reported transparently; no clinical claim |

DataScienceEcosystem and EDA_analysis are learning exercises. They are not featured
as production or flagship AI work. Earlier notebooks remain under historical/ in
the analytical repositories, with the current entry point described in each README.

## Review a project quickly

Read its README, inspect the evaluation or model card, run the documented command,
then inspect one failure case and one automated check. Reported performance is
specific to its dataset and split, not a claim of deployed business impact.
