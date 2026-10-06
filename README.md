## DataBrief: Automated Report Analysis Pipeline (JavaScript)

Built a [browser-based analysis tool](https://data-mohammed-databrief-2026.netlify.app) that turns a recurring CSV or Excel report into a cleaned dataset, statistical findings, and a plain-language summary, with all processing done locally in the browser. The pipeline detects identifier and date columns, scores data quality, flags outliers (IQR fences and z-scores), and tests relationships with Pearson correlation and one-way ANOVA. Results are adjusted with Benjamini-Hochberg false-discovery-rate correction, so weak findings are labeled tentative instead of overstated. Charts (correlation heatmap, distributions with box plots, scatter and trend fits) are hand-drawn as SVG, and the summary is template-generated from the computed statistics, with no server, API, or AI model involved.

[Live Demo](https://data-mohammed-databrief-2026.netlify.app)
