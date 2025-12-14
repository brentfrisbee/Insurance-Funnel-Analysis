# Executive Summary:
This project uses mock data to analyze an insurance application funnel from initial submission through policy issuance. The objective is to identify where applicants drop off disproportionately and provide data-driven recommendations to improve conversion rates.

The analysis simulates a realistic business scenario in which an insurance company has strong lead volume but a weak application-to-policy conversion rate.

# Business Problem:
* High volume of submitted applications

* Low overall conversion rate (~3%) from application to issued policy

* Business suspects friction within the application process but lacks visibility into where it occurs

Goal: Identify key drop‑off points and recommend improvements to increase conversion.

# Skills:
* SQL: SELECTs, CTEs, window functions, aggregations

* Analytics: Funnel analysis, conversion rates, drop‑off analysis

# Findings:
* The funnel is not symmetrical—drop‑offs are concentrated at specific stages.

Major Drop‑Offs:

* ~25% drop‑off from Application Started → Personal Info Completed

  * Indicates early‑stage friction or poor UX

* ~25% drop‑off from Policy Approved → Policy Issued

  * Suggests late‑stage filtering (pricing, payment, competitor selection, or documentation friction)

# Recommendations:
Immediate Actions

* Simplify the first application step (fewer fields, clearer copy)

* Review mobile experience and form usability

Follow‑Up Analysis

* Investigate the approval‑to‑issue step for pricing or payment friction

* Compare approved‑but‑not‑issued policies to issued policies for pattern detection

# Next Steps

* Validate findings using real production data

* Segment the funnel by product, channel, or applicant attributes

* Add time‑to‑complete metrics and build a simple monitoring dashboard
