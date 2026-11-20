# TaLens - Talent Lens, A Feature Attribution based Job Rejection Calculator

**TaLens - Talent Lens, A Feature Attribution based Job Rejection Calculator** is an explainable screening diagnostics web application styled with an early-2010s enterprise SaaS UI/UX aesthetic. It evaluates candidate resumes and structured metadata signals against target job descriptions (JDs) to explain why an application is likely to be rejected or shortlisted, and lets users simulate actionable counterfactual improvements in real time.

## Author

* **Komal Sai Raj Atmakuri** ([@komalsratmakuri](https://github.com/komalsratmakuri))

## Key Features

* **Early-2010s Enterprise SaaS UI/UX**: Brushed slate-steel top navigation, subtle vertical linear gradients, crisp `1px` borders, tactile segmented controls, inner-shadowed inputs, and glossy action buttons that adapt smoothly across desktop and mobile viewports.
* **Interactive Diverging Attribution Waterfall**: Visualizes positive (shortlist) and negative (rejection) feature contributions around a `0.50` baseline prior against a `65%` shortlist cutoff. Click any feature bar to inspect evidence and rationale.
* **Counterfactual "What-If" Simulator**: Toggle resume or availability fixes (such as reducing notice period, highlighting missing stack keywords, or adding quantified KPIs) to preview live probability recovery.
* **Resume vs. JD Gap Matrix & Annotated Diff View**: Inspect matched, partial, and missing requirements in a structured matrix or view side-by-side highlighted tokens.
* **Model Weight Calibration**: Adjust global importance multipliers for core stack coverage, notice period sensitivity, quantified impact metrics, and domain pedigree.

## Repository Structure

```text
talens/
├── index.html
└── README.md
```
