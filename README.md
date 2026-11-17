# n8n proof sample

One workflow from a set of 1,260 builds, published as evidence of the error
handling and run logging described on the page.

- `index.html` - the page (no analytics, no external requests)
- `sample-workflow.json` - the workflow, credentials stripped
- `run-log-example.csv` - sample Run Log rows, synthetic data

The published workflow carries a Run Log receipt, a failure branch to Slack,
and retries on HTTP calls. Only one build is published; the rest are not.
