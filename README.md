## Project Constraints Overview

Hard constraints are strict rules that must never be violated; soft constraints are preferences that should be met if possible but are not mandatory[1][2][3].

### Hard Constraints
- No overlapping (every event/class/slot must be conflict-free)[1].
- Labs must be continuous (lab hours can’t be split across the day)[1].
- Maximum periods per day (clear upper limit to prevent overload; e.g., 6 periods)[1].

### Soft Constraints
- Ensure rest periods for teachers (prefer gaps, but not required)[1].
- Try to balance teacher workloads across days[1][3].
- Favor cost and time efficiency where possible, but not mandatory[1].

*

## Tech Stack

- *Collaboration:* Git for version control
- *Auth tokens:* Redis (stores tokens for quick retrieval)
- *Database:* MongoDB (NoSQL for flexible schedules)
- *Frontend:* React or Server-Side Rendering (SSR) for optimal performance
- *Server:* Prefer Django; Flask is acceptable as an alternative[4][5].

*

## Team Roles

| Role           | Headcount | Tasks                                         |
|----------------|-----------|-----------------------------------------------|
| Documentation  | 2         | Maintain README, technical docs, guides[1]|
| Frontend       | 1         | Develop UI in React, ensure minimalism[6]|
| Backend        | 2         | Server logic (Django/Flask), APIs, DB[4]  |
| Algo Analyzer  | 1         | Validate scheduling algorithms, edge cases[7]|

*

## Development Constraints

- *Naming Conventions:* Use PascalCase for React components and camelCase for variables/functions[4].
- *Code Documentation:* Every function and module should have clear docstrings and comments[4].
- *User-Friendly UI:* Design minimalistic, intuitive interfaces after validating timetable logic[6].



## Requirements & TODOs

- Build a minimalistic frontend: keep it clean, simple, and functional[6].
- Rigorous edge case testing: cover boundary inputs, schedule conflicts, algorithm exceptions[7].
- Derive and document a validity formula for timetabling (clearly state when a schedule is valid)[7].



## Edge Case Testing

1. Identify potential edge cases by reviewing requirements and user stories[7].
2. Develop test cases for boundary and extreme conditions.
3. Automate tests using tools like Selenium or Testsigma when possible.
4. Document and analyze failures to improve system robustness[7].



## Sample Validity Formula

A schedule is valid if:
$$
\text{Valid Schedule} = (\text{No Overlapping}) \land (\text{Labs are Continuous}) \land (\text{Periods per Day} \leq \text{Max Allowed})
$$
[1]



