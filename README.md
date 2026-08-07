# Nathan Beyene

I build developer tools that measure things people usually guess at.

Most CI advice is folklore — "this job feels slow," "that vendor seems cheaper."
I keep building the thing that replaces the guess with a number: what your CI
actually costs, what a change actually saves, what the pipeline actually does.

Minerva University, class of 2029. Previously taught at Yale Young Global
Scholars. Currently in San Francisco.

## What I'm building

| Project | What it does |
| --- | --- |
| [ci-cost](https://github.com/NWelde/ci-cost) | Samples a repo's real GitHub Actions run history, prices it against a versioned rate catalog, then replays the same usage through 8 other vendors' pricing models. Packaged as an installable agent skill. Python, 413 tests. |
| [shadow-runner](https://github.com/NWelde/shadow-runner) | Finds CI jobs waiting on each other for no real reason, then proves the fix by running both versions on live GitHub Actions infrastructure and measuring the difference. It doesn't say "this should be faster" — it says "we ran it, and it was." |
| [better-ci](https://github.com/NWelde/better-ci) | A CI engine with pipelines defined in Python instead of YAML: DAG execution, content-hashed caching, and git-diff job selection so only affected jobs run. 119 tests. |

A thing I care about in all three: they fail loudly instead of guessing. `ci-cost`
refuses to price a runner label it doesn't recognize rather than quietly
estimating one, because a confident wrong number is worse than an error.

## Research

I work with Minerva's IMPACT Lab on droplet impact physics — specifically drop
rebound at low Weber number, where surface tension dominates momentum and a
slow, tiny drop bounces almost perfectly elastically. Counterintuitive result:
it bounces cleaner than a fast one.

The experimental problem is that contact-line friction contaminated every
measurement in this regime, so we validate against a reduced-order kinematic
match model. Paper in preparation, in collaboration with Carlos Galeano-Ríos.

## Teaching

I taught three seminars in the Innovations in Science and Technology track at
Yale Young Global Scholars across summer 2026:

- **Pandora's Code** — AI biosecurity and dual-use dilemmas
- **How Prediction Markets Work** — Bayesian reasoning, automated market makers, Brier scoring
- **The Question Scientists Forget to Ask** — Al-Ghazali and Hume on the limits of induction

## The thread

Nearly everything I work on is the same question wearing different clothes:
**what justifies a belief, and what happens when a system optimizes for the
wrong signal?**

Forecasting and calibration. Goodhart's law — in CI metrics, ML evals, and
academic publishing alike. Prompt injection and adversarial robustness. Poker as
a laboratory for Bayesian updating under incomplete information. Prediction
markets as epistemic infrastructure, and why we built the most honest
forecasting tool ever made and filled it with sports bets.

The forecaster's discipline is the part I actually try to live by: being wrong
isn't failure as long as you got signal to update on. The update is the win.

## Outside the terminal

Ethiopian Orthodox Tewahedo — studying Ge'ez and the liturgy toward becoming a
deacon. Ethiopian music theory, especially how Saint Yared's system underlies
the masinqo repertoire. Ethiopian history after 1960, currently reading
ዳኛው ማነው?. Poker, though I'd argue that one belongs in the section above.

## Reach me

- GitHub: [@NWelde](https://github.com/NWelde)
- Open to summer 2027 internships in developer infrastructure, systems, and quantitative research.
