## Rubén Ortiz

Mobile tech lead on a 700K-MAU consumer fitness app: Flutter, app performance, LLM agents, and the teams that ship them.

Founding Engineer at **[Symmetry](https://symmetry.club)**, a gamified fitness app ("Strava for the gym") with 700K+ monthly active users and 3M+ installs in 2026. I've led mobile across several squads, own Symmetry's AI coach and sit in the founders' leadership meeting.

I joined in January 2026 as a Junior Engineer, after freelance and open-source work going back to 2019. Since then I've been promoted five times in nine months: Mobile Engineer → Senior & Squad Lead → Tech Lead → Frontend Architect → Founding Engineer (October 2026). In 2026 I did more code reviews (142) and merged more PRs (465) than anyone else at the company.

Remote, Spain · [rubenortiz.tech](https://rubenortiz.tech) · [LinkedIn](https://linkedin.com/in/rubenortz) · [rortmarb@gmail.com](mailto:rortmarb@gmail.com)

### Impact at Symmetry

- **Leading mobile: ~2.4× throughput without growing the team.** While I was Tech Lead, merged mobile PRs per month rose ~2.4× (Jan–May vs Jun–Sep 2026), and engineers I mentored were promoted to Senior.
- **AI coach, end to end (Python + Flutter): 79K users, 690K+ messages in its first four months.** It's free for every user. Planner/executor routing cut latency by 60–77%, and consolidating 9 tools into 4 composable ones cut the agent loop rate from 65% to 13%. The backend and the app share a schema-first AsyncAPI contract.
- **Cold start: 7.4 s → 294 ms (25×).** I rebuilt app startup as a cache-first, four-phase init and deleted 4,000+ lines of dead code.
- **Social feed: used by 1.5M+ people in 2026.** I built it from scratch, then rebuilt it. Since January, likes have grown 3× and interacting users 5×.
- **CI/CD: test suite 828 s → 197 s (~4×).** I built CI/CD from scratch on self-hosted runners, with automated versioning and TestFlight releases. I also created a Debt Score metric: live debt fell 36% (591 → 381) in six weeks.
- **Architecture for humans and AI agents.** I led the move to a modular Flutter architecture (packages around a shared core), guarded by custom CI linters, contracts and tests, so AI agents can work autonomously under human review. The team kept shipping throughout the migration.

### Side project: [Nuvi](https://nuviapp.org)

A native iOS app I built solo and launched on the App Store in September 2026, in English and Spanish. You scan a grocery barcode and get a yes or no for *your* fitness goal. It's built with Swift/SwiftUI, a Go + Elixir backend (Redis, ScyllaDB, AWS), App Attest and RevenueCat. It also has a 75-rule custom architecture linter that checks the whole repo in 4 s, and an LLM chat tested against a 119-scenario eval suite.

### Earlier work and open source

- **Quimify** (freelance, 2023–24): Flutter + Spring Boot. Moving data to a local database cut server load by 30%.
- **[NodeBot](https://github.com/Node-Estudios/NodeBot)**: a Node.js Discord bot I co-built (2019–22). It reached 2M+ users across 20K+ servers.
- **[Electrics-App](https://github.com/rubenOrtz/Electrics-App)**: an offline Flutter app for designing and validating low- and high-voltage installations on site under Spanish regulations (REBT/RAT). It draws single-line diagrams and exports PDFs.

*Most of my work is private: 2,600+ of my 2,800+ contributions in the last year.*

### Stack

Flutter · Dart · BLoC/Cubit · Clean Architecture · Swift/SwiftUI · Python · Go · Elixir · TypeScript/Next.js · Postgres/pgvector · ScyllaDB · Redis · AWS · Docker · GitHub Actions · RevenueCat · Stripe · Datadog · LLM agents and evals
