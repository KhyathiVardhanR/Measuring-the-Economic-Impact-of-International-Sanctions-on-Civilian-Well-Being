## Assessing the Civilian Impact of International Sanctions on Economic and Social Well-Being

Heilmeier Catechism – Project Overview


Research Question:
How are international sanctions associated with changes in civilian economic and social well-being, including inflation, unemployment, trade flows, poverty, and child health outcomes?


1. What are you trying to do?

This project aims to measure how international sanctions affect civilian well-being over time. Rather than focusing only on GDP or inflation, the analysis examines a multidimensional set of indicators including macroeconomic conditions, trade in essential goods, poverty, inequality, and social outcomes such as child mortality.

The goal is to build a country-year panel dataset that connects sanction activity with measurable civilian economic and social indicators.


2. How is it done today, and what are the limits of current practice?

Sanctions are often evaluated based on political effectiveness (for example, regime change or compliance), while civilian economic impacts are studied separately using macroeconomic indicators.

Current limitations include:

Heavy reliance on GDP and inflation alone
Limited integration of trade and household-level data
Difficulty linking sanction timing directly to civilian outcomes
Limited attention to heterogeneous and lagged effects

This project addresses these gaps by integrating sanctions data with macroeconomic, trade, and social indicators within a structured country-year panel dataset.


Milestone 1

This repository contains the foundational work for analyzing the civilian impact of international sanctions.

Milestone 1 includes:

Refinement of the research question and scope
Acquisition of sanctions, macroeconomic, trade, and social datasets
Construction of a relational SQLite database structured by country and year
Exploratory data analysis to identify patterns and data limitations
Development of a comprehensive data dictionary

The analysis at this stage focuses on identifying descriptive patterns and preparing the dataset for formal econometric modeling in future milestones.


Repository Structure

data/raw/ – Raw datasets (sanctions, macroeconomic, trade, social indicators)
data/processed/ – Cleaned and structured panel datasets
notebooks/ – Jupyter notebooks for data acquisition, database creation, and exploration
database/ – SQLite database files and schema
diary/ – Milestone documentation, reflections, and data dictionary

This repository provides a transparent and reproducible framework for studying the civilian economic consequences of international sanctions.
