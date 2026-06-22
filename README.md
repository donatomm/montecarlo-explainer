# montecarlo-explainer
# Monte Carlo — A Visual Explainer

A single-page, self-contained explainer for the Monte Carlo method: where it came from, how it works, where it's used, and how it serves as an adversarial/epistemic audit tool.

By [Donato Marco Mangialardo](http://www.linkedin.com/in/donatomm).

## Files

- `MONTE-CARLO-EXPLAINER.html` — the whole thing. No build step, no dependencies, no network calls. Open it in any browser.
- `monte-carlo-guys.png` — the frozen-lake "10 Guys" illustration. Must sit next to the HTML (referenced by relative path).

## View it

Open the HTML directly:

```
open MONTE-CARLO-EXPLAINER.html
```

Everything (CSS, the π simulation, the SVG character art) is inline. Keep the PNG in the same folder or the cold-open image breaks.

## What's inside

- **Ten guys testing the ice** — the plain-English intuition (frozen lake + 10 stress-testing robots), plus why this makes Monte Carlo a strong auditing tool.
- **History** — Los Alamos 1946: Ulam, von Neumann, Metropolis, Fermi, and the naming story.
- **The crew** — the five moving parts of a run (RNG, counter, estimator, Law of Large Numbers, variance), personified.
- **Interactive simulation** — a live, honest π estimate by throwing random darts; refresh for different numbers.
- **Why 1/√N matters** — the dimension-independent error rate, and why it conquered finance, physics, graphics, and AI.
- **Applications** — quantitative finance, physical sciences, project management/engineering.
- **The Auditor Angle** — Monte Carlo as an epistemic stress-test: constraint mapping → distribution assignment → simulation → sensitivity analysis.
- **Failure modes** — garbage in, garbage out, and the three habits that keep a model honest.
- **Sources & honesty note** — what's verified vs. interpreted.

## Honesty notes

- The character quotes attributed to the inventors are **interpretations** (illustrative personifications), flagged as such in the page. The only verbatim historical quote is Ulam's solitaire line.
- The π demo runs a real random simulation in-browser — the numbers wobble every refresh by design.
- Primary source (Metropolis, *"The Beginning of the Monte Carlo Method,"* Los Alamos Science, 1987) survives mainly as a scanned PDF; historical claims are corroborated through secondary sources. Full list in the page's Sources section.

## License / use

Personal explainer. Reuse the text and code freely; credit appreciated.
