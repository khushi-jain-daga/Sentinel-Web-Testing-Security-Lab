# Sentinel — Application Quality & Security Lab
Experiment 14 | Khushi Jain Daga | 23bcon1665 | JECRC University

Run `npm start`, then manually open http://localhost:8012/. No dependencies or API keys required. Run `npm test` for HTTP integration checks. Click Execute test suite to make real local HTTP requests and export the results.

## Debugging record
- Exact URL matching can reject query parameters; route matching now uses URL.pathname. Regression test included.
- Invalid input types and markup are rejected before processing. The UI renders results using textContent rather than HTML injection.
- Unknown routes and malformed JSON return controlled errors. Security headers restrict framing and content loading.

These checks are intentionally limited to a local demonstration; there is no database, authentication, or claim of comprehensive security coverage. No external targets are tested. Browser screenshots should be captured after local execution.
