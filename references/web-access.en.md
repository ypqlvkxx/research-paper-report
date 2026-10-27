# Retrieving papers from webpages and Zotero links

Read this reference only when input requires network retrieval. Obtain sufficient full text and figures for close reading without turning access problems into extended troubleshooting.

## Parse and choose a source

1. Identify the title, DOI, and entry URL from the user's link or Zotero citation. Treat an ordinary URL dragged from Zotero as a paper webpage; connecting to or traversing the entire library is unnecessary.
2. Read the entry page and extract actual links labeled PDF, View PDF, supplementary material, or author version. Prefer the published version. Label preprints when used and avoid mixing values or figure numbers across versions.
3. Choose PDF or complete HTML based on completeness and retrieval speed. Verify that downloaded content is actually a PDF, and check the first-page title, authors, and DOI rather than relying on its extension. For HTML, confirm that methods, experiments, and figures are present, not just an abstract.
4. Retrieve supplements or official code only as needed for the analysis. If the main paper is complete, missing nonessential attachments do not block the report; disclose the scope of reading.

## Stop clearly and avoid repeated failures

- After the initial normal access attempt, a transient timeout may justify one short retry or an attempt through a known direct open-access link. Do not enumerate guessed PDF endpoints, traverse mirrors, or keep changing browsers.
- For HTTP 403, access denial, login, payment, or human-verification barriers, state the obstacle directly. By default, do not attempt bypasses, repeatedly click verification controls, or ask the user to take over the browser. Consider another attempt only if the user subsequently requests one, and follow the applicable instructions.
- Stop retrieval after approximately two minutes without substantive progress. Switching tools does not reset that budget. A normal download with continuing progress may reasonably take longer; do not interrupt successful transfer merely to meet the time guideline.
- For genuinely slow large PDFs, a small number of concurrent byte-range requests may help if the server supports them. Use this only for an actual transfer bottleneck; do not keep multiple full downloads or retry indefinitely.
- A newly opened automated browser is usually separate from the user's existing session. Do not claim to inherit login state or verification results, or to control the user's window, unless the tools actually support this and it has been confirmed.

## What to report when retrieval fails

Briefly identify the paper, attempted entry point, actual error, and whether an abstract, metadata, or no content was obtained. Explain why a full-paper report cannot be produced for that item. Continue with other papers in a batch and include failed items with their reasons in the final delivery. You may say that a local PDF or readable full-text link would allow work to resume. Do not repeatedly ask for confirmation of the same attempt or generate an empty report that appears complete.

If only a Zotero internal item ID or `zotero://` link is available without an accessible attachment or external URL, explain that the link alone does not provide readable full text. Do not interpret this as evidence that the paper does not exist.
