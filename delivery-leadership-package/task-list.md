# Task List (Reference Shape)

> The real task list lives on your GitHub Project board. This file is the **shape**: what each issue should look like before it leaves your hands. Link to the board from `vision-brief.md`.

## Issue template

```
Title: [AREA] short verb-first description

Who it's for: <user>. What they get: <thing>. Why it matters: <outcome>.

Done criteria
- [ ] Observable thing 1
- [ ] Observable thing 2
- [ ] Observable thing 3

Out of scope
- Anything that is *related* but explicitly not in this issue.

Linked decisions / risks
- (links to decision memos or risk-register rows if applicable)
```

## Suggested starter tasks (you may add, split, or drop)

| # | Title | Area | Priority |
|---|---|---|---|
| 1 | Assemble provided components into App.tsx | FE | P0 |
Done: The QuoteForm, PremiumDisplay, and RecentQuotes components are imported and rendered in App.tsx.
Done: The app runs locally (npm run dev) without errors, and the basic layout is visible.
Done: The premium display updates in real-time as the user interacts with the form inputs.

| 2 | Set product title via .env | CONFIG | P1 |
Done: The main heading on the page displays the title set by VITE_APP_TITLE in the .env file.
Done: The premium.ts file has been updated with the sponsor's approved rates.
Done: The calculated premiums for auto, home, and life coverage are verified to be "believable numbers" as per the project requirements.

| 3 | Apply sponsor rate decision in premium.ts | CONFIG | P0 |
Done: The main heading on the page displays the title set by VITE_APP_TITLE in the .env file.
Done: The premium.ts file has been updated with the sponsor's approved rates.
Done: The calculated premiums for auto, home, and life coverage are verified to be "believable numbers" as per the project requirements.

| 4 | Fix the QA-flagged type error (kit one-line fix) | TYPES | P0 |
Done: The specific line of code causing the type mismatch has been identified.
Done: The type error is resolved by correcting the code to align with the defined TypeScript contracts.
Done: npm run type-check completes successfully with zero errors.

| 5 | Switch recent quotes to the data feed (loading/error visible) | DATA | P0 |
Done: Hardcoded quotes are removed and replaced with a useEffect hook that fetches from /quotes.json.
Done: A "loading..." state is clearly visible to the user while the data is being fetched.
Done: The RecentQuotes component correctly displays the list of quotes received from the data feed.

| 6 | Drop in custom hook + context provider (no behavior change) | REFACTOR | P0 |
Done: The form logic is successfully extracted from QuoteForm into the useQuoteEstimate custom hook.
Done: The QuotesContext is implemented and provides the state for the recent quotes list.
Done: The "Save this quote" button is now functional, adding a new quote to the top of the list via the context.

| 7 | Enable GitHub Actions CI workflow | CI | P0 |
Done: The ci.yml workflow file is present in the .github/workflows directory.
Done: The workflow is automatically triggered on pushes and pull requests to the main branch.
Done: The workflow successfully runs install, type-check, and build steps, resulting in a "green checkmark" on the pull request.

| 8 | Production build passes (npm run build → dist/) | BUILD | P0 |
Done: The npm run build command completes successfully with no errors.
Done: A dist directory containing the optimized, production-ready files is generated in the project root.

| 9 | Open PR from delivery/lead → main | REVIEW | P0 |
Done: A pull request is open, targeting the main branch from your feature branch.
Done: The PR description clearly summarizes the work completed.
Done: All status checks on the PR, including the CI workflow, are passing with a green checkmark.


| 10 | Document one Copilot-assisted assembly + critique | AI | P2 (stretch) |
