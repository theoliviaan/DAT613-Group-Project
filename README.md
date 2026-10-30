# DAT 613 - Group 2: NumPy Pipeline for Ingredient Planning

MamaPut Express runs 12 branches in Lagos and Abuja. Managers order
ingredients by guesswork, so some branches waste rice and others run out
of chicken. This project turns 12 weeks of raw sales data into a
data-driven daily order for each branch, and finds when each branch is
busiest.

## What the notebook does

1. Reshapes the flat sales array into (branches, days, slots, items)
2. Finds and fixes three data problems:
   - two menu item columns swapped at one branch
   - one recipe ingredient recorded in kilograms instead of grams
   - closed days stored as zero sales
3. Multiplies portions by the recipe to get ingredient use in kg
4. Answers the two business questions, with charts

## How to run it

1. Open `DAT 613 GROUP 2 ASSIGNMENT.ipynb` in Google Colab or Jupyter Notebook
2. Upload the `.npz` data file using the folder icon on the left
3. Set `DATA_PATH` in the second cell to your file name
4. Runtime → Run all

`run_pipeline(path)` runs every stage on any data file of this type.

Requires NumPy and Matplotlib only. Both are pre-installed in Colab and Jupyter.

## Group members

- Olivia Akabogu — data and structure
- Name — data problems
- Name — analysis
- Name — business answers and charts
- Name — integration and report
