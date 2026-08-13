Fleet_Idle_Fuel_Efficiency_Analysis_-Lean-_Six-_Sigma-_DMAIC-
A data-driven Lean Six Sigma Green Belt capstone analyzing Samsara telematics and Penske fuel data to reduce vehicle idling, lower operational fuel waste, and establish real-time governance controls.

Lean Six Sigma Green Belt Capstone: Fleet Idle Fuel & Operational Efficiency Reduction

[[Methodology: Six Sigma DMAIC](https://img.shields.io/badge/Methodology-Lean_Six_Sigma_DMAIC-green.svg)](https://www.isixsigma.com/)

Executive Summary: A Lean Six Sigma DMAIC initiative focused on identifying idle-related fuel waste and operational inefficiencies across fleet operations. By leveraging telematics data, targeted driver coaching, and automated real-time alert systems, this project established a measurable baseline to curb excessive vehicle idling, lower operational fuel expenses, and reduce $CO_2$ emissions.

Project Charter & Purpose

Purpose: Identify idle-related fuel waste and operational inefficiencies, establish a measurable performance baseline for fleet idling behavior, and implement scalable, low-capital control solutions.
Core Goal: Minimize excessive vehicle idling across fleet operations to reduce operational costs and environmental emissions.

Primary Operational Data Sources:
Samsara Telematics: GPS tracking, idle event durations, and fuel consumption logs.
Penske Fuel Purchases: Total dollars pumped, average cost per gallon, and purchase location details.
Driver & Route Assignments: Driver frequency, dispatch logs, and route execution stages.

 DMAIC Process Breakdown

1. DEFINE
Problem Scope: Vehicles incurring excessive idle wait times during dispatch, route execution, and staging phases.
Excessive Idle Definition:Any driver repeatedly appearing within high-idle categories across multiple evaluation periods (e.g., Q1 2025 weekly segments).
Process Mapping (SIPOC / Current State):
  $$\text{Vehicle Dispatch} \longrightarrow \text{Route Execution} \longrightarrow \text{Staging / Wait Occurs} \longrightarrow \text{Telematics Alert Captures Event} \longrightarrow \text{Review \& Escalation}$$
[cite: 5]

2. MEASURE
Data Collection Plan: Processed operational telematics and purchasing data using Excel, pivot tables, and Pareto analysis.
Key Metrics & Data Types Collected:
Metric, Description, Data Type,
Idle Fuel Consumption, Estimated fuel cost during idle events, Continuous (Gallons).
Idle Duration, Length of individual idle events, Discrete.
Repeat High-Idle Drivers, Number of recurring high-idle contributors, Discrete (Count/Frequency).
Fleet Fuel Purchases, Total gallons pumped and average cost/gallon, Continuous.

3. ANALYZE
Pareto Analysis: Applied high-idle threshold filters to isolate recurring trends and top repeat contributors to fuel waste.
Hypothesis Testing:
Null Hypothesis: Eliminating non-value-added idle stages or implementing alert-driven coaching has no material effect on fleet fuel consumption.
Alternative Hypothesis: Real-time alerts combined with targeted driver coaching significantly reduces excessive idle frequency and operational waste.
Root Cause Findings: Uncovered operational delays during staging/wait periods and lack of real-time visibility into driver idle habits.

4. IMPROVE
Selected Solutions:
Real-Time Samsara Idle Alerts: Automated notifications triggered when vehicles cross idle thresholds.
Targeted Driver Coaching: Structured feedback sessions using weekly branch scorecards for high-idle contributors.
Key Expected Benefits: Continuous sustainability, scalable operational implementation, minimal capital investment requirement, early trend detection, and lower emissions.

5. CONTROL PLAN & GOVERNANCE
To ensure long-term process capability and prevent performance regression, the following control structure was established:

Control Method, Purpose & Focus, Frequency, Responsible Party

Real-Time Samsara Alerts, Enable real-time interventions when threshold is exceeded, Immediate / Real-Tim, Dispatch / Fleet Supervisors.
Targeted Driver Coaching, Reduce excessive idle wait behavior and driver habits weekly with Fleet Supervisors.
Weekly Idle KPI Reviews, Detect operational trends before escalation, Weekly, Logistics Manager.
Branch Scorecards Monitor high-idle contributors & accountabilities, Weekly / Monthly,Operations Leadership.
Trend Analysis Reporting, Operational idle benchmarking against best standards, Monthly,Project Lead / Operations.

Key Lessons Learned & Lean Reflection

"On most Lean Six Sigma projects, key organizational lessons learned always outshine purely analytical depth. While large amounts of data were available, actionable insights came through leadership accountability and automated controls. Leveraging foundational Lean principles like identifying **Muda (waste)** within a structured DMAIC framework empowers stakeholders to make sustainable, data-backed operational changes."

Repository Structure

├── data/                    # Cleaned Samsara telematics & Penske fuel datasets
├── analysis/                # Excel/Python scripts for Pareto analysis and metric calculations
├── process_maps/            # SIPOC diagrams & Current State VSMs
├── reports/                 # Final Lean Six Sigma Capstone Presentation & Document
└── README.md                # Project documentation
