# A²-Bench project website

A static Salesforce AI Research website explaining the benchmark setting, motivation, evaluation, and findings.

## Run locally

No installation or build is required. From this directory, run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open [http://localhost:4173](http://localhost:4173).

## Files

- `index.html` — interactive project website and root homepage.
- `project.html` — redirects older project links to the root homepage.
- `research.html` — redirects older analysis links to the relevant homepage section.
- `assets/` — local styles, scripts, fonts, and images.
- `transcripts/` — seven readable transcripts and their interactive viewers.

The benchmark implementation is maintained in [SalesforceAIResearch/a2-bench](https://github.com/SalesforceAIResearch/a2-bench).
