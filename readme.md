# Clinic Setup Project  
**CPM + PRA **

## Overview
This project focuses on planning and scheduling the setup of a small medical clinic using **project management techniques**.  
It integrates:

- **Critical Path Method (CPM)** for deterministic scheduling
- **Program Evaluation and Review Technique (PRA / Monte Carlo simulation)** for uncertainty modeling

The project is developed as part of an academic course on **Strategic Programs / Project Management**.

---

## Problem Description
The clinic setup project includes the following activities:

- Selecting a location  
- Obtaining permits  
- Renovating the clinic  
- Purchasing and installing medical equipment  
- Setting up IT and network systems  
- Recruiting and training staff  
- Testing, inspection, and final opening  

Each activity is defined by:
- Duration (deterministic or stochastic)

---

## Objectives
1. **CPM Analysis**
   - Compute ES, EF, LS, LF, Float
   - Identify the critical path
   - Compute total project duration

2. **PRA / Monte Carlo Simulation**
   - Model uncertainty in activity durations
   - Estimate mean project duration
   - Compute the 95th percentile (risk-aware schedule)


---

## Methodology
- Activities are represented as nodes in a directed graph
- Precedence relations are modeled using **NetworkX**
- CPM metrics are computed analytically
- PRA is implemented via Monte Carlo sampling

---


## How to Run

### Install dependencies
```bash
pip install -r requirements.txt

jupyter notebook src/main.ipynb

