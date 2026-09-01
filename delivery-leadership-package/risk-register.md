# Risk Register

> Copy to `delivery-leadership-package/risk-register.md`. At least 5 rows. **No boilerplate**; your peers will grade you on whether these are real.

| # | Risk | Owner | Likelihood (L/M/H) | Impact (L/M/H) | Mitigation | Trigger to escalate |
|---|---|---|---|---|---|---|
|Risk # 1: The development server (npm run dev) successfully runs code that the stricter production build process (npm run build) will reject due to type errors, leading to a failed CI pipeline and last-minute build issues
Likelihood: Medium
Impact: High
Mitigation:  Instruct all developers to run npm run type-check and npm run build locally before pushing code

|Risk # 2: A team member pushes code directly to the main branch or struggles to resolve a merge conflict, leading to a broken build, lost work, and delays.
Likelihood: Medium
Impact: HIgh
Mitigation: Encourage pair-programming for resolving complex merge conflicts to treat them as a learning opportunity.

|Risk # 3: A team member pushes code directly to the main branch or struggles to resolve a merge conflict, leading to a broken build, lost work, and delays.
Likelihood: Medium
Impact: HIgh
Mitigation: Encourage pair-programming for resolving complex merge conflicts to treat them as a learning opportunity.

|Risk # 4:  A team member reflexively upgrades a library or toolchain dependency (e.g., Vite, TypeScript) mid-week, causing unforeseen breaking changes and build failures.
Likelihood: Low
Impact: HIgh
Mitigation:  At project kickoff, get team agreement that all toolchain versions are pinned and will not be upgraded without a formal go/no-go decision.

|Risk # 5:The team is pressured to add a "small" feature that is explicitly out of scope (e.g., saving quotes to a database), which distracts from the primary goal and threatens the deadline.
Likelihood: MEdium
Impact: MEdium
Mitigation: At the project kickoff, review the "What is explicitly out of scope" section with the team and key stakeholders to set clear boundaries. 
## How I'll use this register

_One short paragraph. When will you re-read it? Who else can see it? What's the cadence?_
