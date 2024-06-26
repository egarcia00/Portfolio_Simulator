# Portfolio Simulator

**Scope** : creating a tool that shows you historic performance of a given portfolio. And what strategy would've had better returns.

**How to do it?**
- Data Retrieval:
    - Connecting an API of Yahoo Finance.
    - Check Main Companies & Industries with Financial Assets KPI
    - Retrieve Data from Companies

- Data Storage:
    - Setting up a Data Bucket on AWS
    - Setting up the DB Scheme
    - Upload data from companies

- Data Cleaning
    - Time homogenisation (Same days, Backfill in case of blank cases).

- Data Enhancement
    - New Variables
        - Intra day Performance
        - Opening Delta
        - Closing Delta
    - New Dimensions
        - Benchmarks (S&P500, MSCI WORLD)

- Financial Strategy
