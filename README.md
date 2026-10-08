# AI Expense Auditor

[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=111)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000?logo=vercel&logoColor=white)](https://ai-expense-auditor-five.vercel.app/)

An interactive, front-end demonstration of an AI-assisted expense review workflow based on GitLab's publicly available Global Travel & Expense Policy.

**Live demo:** [ai-expense-auditor-five.vercel.app](https://ai-expense-auditor-five.vercel.app/)

## Technology

- **HTML5** for the application structure and accessible workflow views.
- **CSS3** for the responsive light enterprise interface, layout, and audit animations.
- **JavaScript (ES6+)** for scenario state, policy evaluation, risk scoring, uploads, exports, and interactive UI behavior.
- **Vercel** for production hosting and **GitHub** for source control and project documentation.

## What the demo includes

- Three interactive expense-review scenarios: compliant travel, a government-recipient compliance hold, and an outside-Navan exception.
- Simulated document extraction, policy matching, risk scoring, approval routing, and evidence-backed decisions.
- A policy workspace containing 12 executable controls derived from the public policy snapshot.
- Expense-report search, audit history, U.S. tax-evidence views, and downloadable demonstration exports.
- Responsive desktop and mobile layouts.

## Run locally

No build step or API key is required.

```bash
cd dist
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Project structure

```text
dist/
  index.html        # Application markup, data, and interactions
  light-theme.css   # Light enterprise UI theme
```

## Policy source and disclaimer

This independent simulation is based on GitLab's publicly available [Global Travel & Expense Policy](https://handbook.gitlab.com/handbook/finance/expenses/), using a policy snapshot dated September 13, 2026.

This project is not affiliated with, sponsored by, or endorsed by GitLab. GitLab and related marks belong to their respective owners. The demo is illustrative only and does not provide legal, tax, accounting, or compliance advice. Organizations should validate policy interpretations and configure their own approval controls before production use.

## Implementation status

The current release is a presentation-ready prototype. Policy reasoning, OCR results, risk scores, and workflow outcomes are simulated in the browser. It does not yet connect to a production OCR pipeline, language model, vector database, accounting system, or persistent data store.

## License

No license has been granted yet. Add an appropriate open-source license before allowing third-party reuse or redistribution.
