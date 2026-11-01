# grid-mind

An end-to-end data science and AI project on the Australian electricity market.

## Overview
grid-mind analyses Australia’s National Electricity Market (NEM) using public price and demand data from AEMO. It covers the full pipeline, from data ingestion in Databricks to statistical analysis, machine learning forecasts and an AI agent that answers market questions in plain English. It also includes a benchmark testing how accurately LLMs, RAG and AI agents answer real energy market questions.

## Tech stack
Python, SQL, PySpark, Databricks, Delta Lake, dbt, MLflow, LangGraph, FastAPI, Streamlit, Docker

## Project structure
- data/ - raw and processed data (not tracked in Git)
- notebooks/ - exploration and analysis
- src/grid_mind/ - reusable project code
- tests/ - automated tests
- docs/ - notes and documentation

## Getting started
git clone https://github.com/AnuvratP12/grid-mind.git
cd grid-mind
uv sync

## Status
Week 1 - project setup and data ingestion