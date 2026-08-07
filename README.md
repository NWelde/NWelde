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

## Teaching

I taught three seminars in the Innovations in Science and Technology track at
Yale Young Global Scholars across summer 2026:

- **Pandora's Code** — AI biosecurity and dual-use dilemmas
- **How Prediction Markets Work** — Bayesian reasoning, automated market makers, Brier scoring
- **The Question Scientists Forget to Ask** — Al-Ghazali and Hume on the limits of induction
