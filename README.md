# Hardware Upgrade Performance & Failure Mitigation Analysis - SQL Queries


## Overview
The repository contains queries to evaluate the effectiveness of hardware upgrades and revisions by tracking failure occurrences before and after upgrades. This is to help determine whether hardware improvements successfully mitigate targeted failures.


These queries provide insights into:
* How different hardware versions (PDB, Motors, Modems) perform over time
* Failure trends before and after hardware upgrades
* The effectiveness of mitigations in reducing preflight, mission, and flight failures
* Failure rates for selected periods

These queries are structured for scalability, performance optimization, and seamless integration with BI tools such as Power BI, Tableau, and MODE.

It also conatains a parameter code in liquid that provides a form-based filtering mechanism for analyzing hardware failure exceptions by allowing users to select specific hardware, exceptions, and deployment dates dynamically. It is particularly useful for interactive dashboards and BI tools.

## KEY METRICS AND INSIGHTS
### Metric	          Description
* total_flights:	Total flights for a given hardware version
* total_flight_failures:	Total flight failures recorded for the hardware
* total_preflight_failures:	Total preflight failures recorded
* total_mission_failures:	Total mission failures recorded
* flight_failure_rate:	Flight failures per 100 flights
* preflight_failure_rate:	Preflight failures to total flights within the period
* mission_failure_rate:	Mission failures to total flights within period

## FUNCTIONALITIES/APPLICATIONS

* Tracks effectiveness of hardware upgrades by analyzing failure rates across different versions
* Compares new vs. legacy hardware in reducing failures
* Provides rolling failure rates to ensure consistent evaluation
* Facilitates data-driven decision-making for future hardware improvements
* Supports predictive maintenance and proactive engineering strategies
