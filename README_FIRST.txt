I WRITE WHAT I LIKELIHOOD — ZIOP ARTICLE PACKAGE

WHAT IS INCLUDED
posts/ziop.qmd                         Complete technical journal article
posts/figures/severity_distribution_original.png
posts/figures/severity_by_lighting_original.png
posts/figures/ziop_process_original.png
posts/figures/aic_bic_comparison_from_tables.png

HOW TO ADD IT TO YOUR QUARTO JOURNAL
1. Open your existing i-write-what-i-likelihood VS Code project.
2. Extract this archive directly into that project's ROOT folder.
   If Windows asks to merge the existing 'posts' directory, merge it.
   The files should appear under posts/ and posts/figures/.
3. In research.qmd add this Markdown link beneath your ZIOP description:
   [Read the full ZIOP investigation](posts/ziop.qmd)
4. Save, open your terminal in the project folder and run:
   quarto preview

ABOUT THE EVIDENCE
* The three original figures are extracted from the user's 2023 dissertation PDF.
* The fourth chart is regenerated from the AIC/BIC values in the reported tables.
* Counts, coefficients, p-values, marginal effects and fit statistics are transcribed from the source research.
* No models were rerun on STATS19, and no new numerical simulation was carried out.
* Exact computational replication will require the original cleaned-data construction rules,
  STATS19 archived extracts and original estimation/evaluation code.
* The article flags a parameter-count mismatch in the earlier comparison tables.

THE ARTICLE IS INDEPENDENT RESEARCH WRITING
There is no university framing in the article. A references section transparently
acknowledges the source of the empirical numbers and charts.
