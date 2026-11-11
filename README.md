# HR Recruitment Funnel Analysis

A planned People Analytics project focused on understanding candidate progression through recruitment stages, identifying process bottlenecks and improving the evidence available to HR Operations and hiring teams.

> **Business context:** A recruitment process can lose candidates through delays, unclear communication or unnecessary process steps. Without consistent funnel measures, it is difficult to identify where the process is underperforming.

## Business problem

At which stages do candidates progress, withdraw or drop out, and where could process changes improve the candidate journey and hiring efficiency?

## Project objectives

Once the source files have been validated, the project will:

- Build a consistent view of the candidate journey across recruitment stages.
- Measure stage-to-stage conversion and candidate drop-off.
- Identify delays and time spent waiting at each stage.
- Compare process outcomes by role, department or application source where supported by the data.
- Present findings that could help HR Operations prioritise process improvements.

## Planned data and approach

The project is awaiting the five source CSV files and validation of their fields. The planned workflow is:

1. Profile each file and identify candidate, application and stage identifiers.
2. Check missing values, duplicates, inconsistent stage labels and date quality.
3. Map stage records into a consistent recruitment journey.
4. Define funnel metrics and denominators before calculating conversion.
5. Use SQL and Python to analyse progression and time in stage.
6. Present the results in Excel and/or Tableau.

## Measures to be developed

- Applications received.
- Candidates reaching each stage.
- Stage-to-stage conversion rate.
- Application-to-hire conversion.
- Withdrawal and drop-off rates.
- Time in stage and time to hire.
- Source effectiveness, where source data is sufficiently complete.

A candidate and an application may not be the same unit of analysis. The final methodology will document the chosen unit, denominator and treatment of repeat applications to avoid double-counting.

## Potential business application

Once completed, the analysis could help a People Operations team identify where candidates experience delays, which stages have the greatest drop-off and whether process outcomes differ across roles or sources. Any recommendation would be based on validated results rather than assumed causes.

## Current status and limitations

This repository is a **project plan**, not a completed analysis. The source files have not yet been added and no findings or performance results are being claimed. Metrics, joins and recommendations will be finalised only after the source data has been inspected.

## Business value

The intended outcome is a practical recruitment-process reporting tool that helps HR teams understand funnel performance and focus improvement work on evidenced bottlenecks.

**Planned skills:** HR operations · process analytics · data quality · SQL joins · Python · funnel metrics · Excel · dashboard reporting

---
*Portfolio project by K96-max.*
