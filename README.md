# Phishing Email Analyzer

Single-file tool for triaging suspicious emails. Paste the raw source of an email (headers + body) and it parses it in the browser and shows what it finds:

- risk score and verdict
- SPF / DKIM / DMARC / ARC checks
- received chain, hop by hop
- extracted URLs and attachments (with hashes)
- IOC list and a short report explaining the verdict

No server, no dependencies, works offline. Open index.html and use it.

Live: https://phishing-analyzer-ui.netlify.app
