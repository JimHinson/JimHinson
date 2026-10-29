# Jim Hinson

**30+ years making software prove it works. Now I make AI prove it.**

30+ years of enterprise engineering experience: leading teams of up to 20 at Microsoft, Panzura, and Victra, cutting hot-patch delivery time 75% and automation failures 50%. The problem was always the same — deciding what counts as evidence. AI just made it urgent.

**Elsewhere:** https://www.gauntletscore.com · [LinkedIn](https://www.linkedin.com/in/jimhinson/) · [X](https://twitter.com/JimHinson6)

## Genstrata
Co-founder & CTO at Genstrata where we're building [the Gauntlet](https://www.gauntletscore.com) — adversarial verification that checks AI output against primary sources before anyone acts on it.
- Replaced the GauntletScore LLM debate engine with a deterministic evidence ledger: on a locked 200 - 300-claim scorecard across 4 domains, zero filings called false and confident errors under 2%.
- Stood up the engineering foundation from scratch: CI with tests on every PR, branch protection, AI-assisted code review gates, incident postmortems, SOC 2 readiness.
- Hired and onboarded the first engineer
- set test-automation strategy (two-tier smoke/nightly suite as a release gate, doubling as production monitoring).

## Public work

- [agentic-ai-patterns](https://github.com/JimHinson/agentic-ai-patterns) — working implementations of 20 agentic design patterns in Python
- [ai-engineering-unpacked](https://github.com/JimHinson/ai-engineering-unpacked) — notebooks from working through applied LLM engineering

## Before Genstrata

- Built the SQA roadmap — objectives, scope, standards, KPIs — that aligned QA with cross-functional delivery.
- Led 20 domestic and international engineers, moving testing to shared team ownership with peer test reviews and automation code reviews.
- Cut legacy automation failures 50%, reducing sprint hardening time 20%.

<details>
<summary><strong>How I think about quality</strong> — the test-automation playbook</summary>

### Automated test attributes
1. **Idempotent** — the environment is unchanged once the test completes.
2. **Independent** — the test runs on its own.
3. **Autonomous** — the test affects no other test.

### Best practices
1. Use control IDs or other unique locators for UI tests.
2. Work closely with development to keep tests in sync with the code.
3. Keep tests in the same repository as application code when possible.
4. Push tests down the pyramid. From least to most reliable: UI/E2E → API → contract → unit.
5. Maintain clear logging and reporting for quick failure analysis.
6. Never ship code with broken tests.
7. Use data-driven tests to cover a broader set of scenarios with less test code.

### Test code design
1. Modular design that supports easy reuse.
2. Keep test logic separate from action logic, and both separate from app-interaction code. One pattern that works: Page Objects → Action Objects → Test Objects.

### Automation priority
1. Critical functionality
2. Commonly used functionality
3. High-risk functionality
4. High-visibility functionality
5. Bug concentrations
6. Time-consuming manual tests
7. Data-driven cases

### Shared ownership
Quality Engineering owns *quality*; the whole team owns *testing*. Building quality in from the outset eliminates context switching and rework.

In practice: design the Definition of Done with the team. At story start, hold a Three Amigos meeting (coder, tester, product) — outline the implementation, decide how each feature gets tested, and leave with a sketch of the code, a sketch of the test plan, and confidence the story satisfies the business need. During coding, flesh out as much or as little of the test plan as the story warrants.

</details>
