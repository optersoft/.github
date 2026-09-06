## Optersoft, S.L.

A software consultancy in Barcelona: we help companies start on new
technology, train the teams that will own it, and build web applications in
pure Python — and we prove it on products we run ourselves. What we do and who
we are is at [optersoft.com](https://optersoft.com); the course material we
teach from is at [academy.optersoft.com](https://academy.optersoft.com).

### Why this organization exists

Our code lives in three places, and each one is a deliberate choice:

| Where | What | Why |
|---|---|---|
| **GitHub** — here | Our **Python** tools, all open source | Public tooling needs what only a public forge offers: anonymous browsing, issues and pull requests from anyone, and CI that runs on a stranger's contribution. Every package here publishes to PyPI straight from GitHub Actions through OIDC trusted publishing, with no long-lived credentials anywhere. |
| **[GitLab](https://gitlab.com/optersoft)** | **Academy** — the project repositories behind [academy.optersoft.com](https://academy.optersoft.com) | The runnable code for every lesson: clone it, run it, read the write-up. Grouped by track (Python, Rust, Kotlin, TypeScript, Linux, cloud, data, AI, bio). |
| **Private forge** | Our products — **Rust**, fullstack | Internal code stays internal. Nothing of it is meant to be consumed outside our own fleet, so it lives on our own self-hosted forge. |

So, if it is Python and you can `pip install` it, it is here. If it is a lesson,
it is on GitLab. Everything else is ours.
