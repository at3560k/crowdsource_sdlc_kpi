# A collection of industry KPIs around SDLC and processes

- [Code](code.md)
- [Time Spent](time_spent.md)
- [Ticketing Process](ticketing.md)
- [Agility](agility.md)


## Rendering

The below is a rendering of what's included already while bootstrapping this.
The different files were created to make PRs *easier* to send without
conflicts.  Please don't worry about updating anything below "Rendering" at
present.

### Code Metrics

- Complexity
- Build Stability
- Code Coverage
- Crash Frequency
- Defect Leak/Escaped Bugs `(100 * (# defects in UAT) / # Defects before UAT)`
- Defect Density `(# of defects / Module Size)`

### Time Spent In

- Time to release
- Time to release verification
- Time spent executing unit tests
### Ticketing KPIs

- Known Tech Debt `(# Tech Debt Items in Backlog / Size of Backlog)`
    - Other flags?
- Bug fixes per time period
- "Pipeline Stressors"
    - # requests for manual testing
    - # requests for expedited code review

### A collection of KPIs observing agility directly

- Lead time: Concept to Delivery
- Cycle Time: Time from change in source to deploy to to production
- Deployment Frequency
   - Time since last deploy
   - Time since last deploy to TIER (staging/qa)
   - Time to deploy
