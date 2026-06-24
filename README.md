# Austo Motor Company — Customer Segmentation

> **Category:** Machine Learning &nbsp;·&nbsp; **Type:** Jupyter notebook project

## Overview

### Context

In the 21st century, cars are an important mode of transportation that provides us the opportunity for personal control and autonomy. In day-to-day life, people use cars for commuting to work, shopping, visiting family and friends, etc. Research shows that more than 76% of people prevent themselves from traveling somewhere if they don't have a car. Most people tend to buy different types of cars based on their day-to-day necessities and preferences. So, it is essential for automobile companies to analyze the preference of their customers before launching a car model into the market. Austo, a UK-based automobile company aspires to grow its business into the US market after successfully establishing its footprints in the European market.

In order to be familiar with the types of cars preferred by the customers and factors influencing the car purchase behavior in the US market, Austo has contracted a consulting firm. Based on various market surveys, the consulting firm has created a dataset of 3 major types of cars that are extensively used across the US market. They have collected various details of the car owners which can be analyzed to understand the automobile market of the US.

### Objective

Austo's management team wants to understand the demand of the buyers and trends in the US market. They want to build customer profiles based on the analysis to identify new purchase opportunities so that they can manipulate the business strategy and production to meet certain demand levels. Further, the analysis will be a good way for management to understand the dynamics of a new market. Suppose you are a Data Scientist working at the consulting firm that has been contracted by Austo. You are given the task to create buyer's profiles for different types of cars with the available data as well as a set of recommendations for Austo. Perform the data analysis to generate useful insights that will help the automobile company to grow its business.

### Data Description

austo_automobile.csv: The dataset contains buyer's data corresponding to different types of products(cars).

### Data Dictionary

  * Age: Age of the customer
  * Gender: Gender of the customer
  * Profession: Indicates whether the customer is a salaried or business person
  * Marital_status: Marital status of the customer
  * Education: Refers to the highest level of education completed by the customer
  * No_of_dependents: Number of dependents(partner/children/spouse) of the customer
  * Personal_loan: Indicates whether the customer availed a personal loan or not
  * House_loan: Indicates whether the customer availed house loan or not
  * Partner_working: Indicates whether the customer's partner is working or not
  * Salary: Annual Salary of the customer
  * Partner_salary: Annual Salary of the customer's partner
  * Total_salary: Annual household income (Salary + Partner_salary) of the customer's family
  * Price: Price of the car
  * Make: Car type (Hatchback/Sedan/SUV)

**Note** : _After running the above cell, kindly restart the notebook kernel and run all cells sequentially from the start again._

#### Question 1: How many rows and columns are present in the data? [0.5 mark]

## Project deep dive

This repository contains a complete, end-to-end notebook for **Austo Motor Company**.
It walks through the full workflow — from framing the problem and exploring the
data, through modeling and evaluation, to the conclusions and recommendations.

- **19 code steps** of analysis and modeling
- Full outputs, tables, and visualizations preserved in the rendered HTML
- A runnable `notebook.ipynb` so you can re-execute and extend the work

## Tech stack

`matplotlib`, `numpy`, `pandas`, `seaborn`

## What's in this repo

| File | Description |
|------|-------------|
| [`notebook.ipynb`](notebook.ipynb) | The runnable notebook (code recovered from the original export) |
| [`austo-vehicle-segmentation.html`](austo-vehicle-segmentation.html) | Full rendered notebook with **all outputs & plots** preserved |
| `requirements.txt` | Python dependencies inferred from the notebook |

## View the notebook

GitHub renders `.ipynb` files inline — just open [`notebook.ipynb`](notebook.ipynb).
For the fully-rendered version with every saved output and figure:

- **Rendered notebook (nbviewer):** https://nbviewer.org/github/Porche22/austo-vehicle-segmentation/blob/main/notebook.ipynb
- **Rendered HTML export:** https://htmlpreview.github.io/?https://github.com/Porche22/austo-vehicle-segmentation/blob/main/austo-vehicle-segmentation.html

> Replace `Porche22` with your GitHub username after pushing.

## Run it locally

```bash
git clone https://github.com/Porche22/austo-vehicle-segmentation.git
cd austo-vehicle-segmentation
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

<sub>Notebook reconstructed from an nbconvert HTML export; code cells recovered
faithfully, rich outputs are preserved in the accompanying `.html`.</sub>
