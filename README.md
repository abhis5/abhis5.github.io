# abhis5.github.io

Personal portfolio of **Abhishek Shukla**, Senior Data Engineer and AI Engineer.

**Live site:** https://abhis5.github.io

## What's here

| File | Purpose |
|---|---|
| `index.html` | The portfolio. HTML, CSS and JavaScript in a single file. |
| `resume.html` | Web version of the résumé, with a Download PDF button. |
| `Abhishek_Shukla_Data_AI_Engineer_5YOE.pdf` | Résumé PDF. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

## The query console

The hero section includes a small console that lets visitors query my career like a database.

- **SQL tab:** a hand-written mini SQL parser over in-page tables (`experience`, `skills`, `projects`, `certifications`, `metrics`). It supports `SELECT ... FROM ... WHERE ... ORDER BY ... LIMIT`, `COUNT(*)`, `SHOW TABLES` and `DESCRIBE`. Try `SHOW TABLES` to start.
- **ASK tab:** a question box backed by a small retrieval corpus. Facts are scored by tag and keyword overlap, and an eval gate withholds the answer when nothing scores high enough. Answers are extractive and cite their source. Retrieval is lexical, not embedding based.
- **Role toggle:** "Start from the data" or "Start from the AI" swaps the example questions and contact copy for that lens, and brings the matching skill group to the front.

## Running locally

There is no build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

GitHub Pages serves the `main` branch from the repository root. A push to `main` is live in about one to two minutes.

## Contact

- LinkedIn and email links are on the [site](https://abhis5.github.io) and in the [résumé](https://abhis5.github.io/resume.html).
- GitHub: [@abhis5](https://github.com/abhis5)
