# Client Brief

A university student wants a simple program to keep track of their spending.

They'd like to:
- Add expenses 
- View all expenses 
- Search expenses 
- Filter by category 
- View statistics 
- Save 
- Load

1. Design an Expense class
    Contains:
    - description
    - amount
    - category
    - date
    - maybe more?
2. Design an ExpenseManager
    Methods:
   - What methods do I need?

- Need to use floats/decimals 

- Statistics
  - total spent
  - average purchase
  - highest purchase
  - lowest purchase

- Filtering
  - instead of searching by name:
    - Show Food expenses 
    - Show Travel expenses

- Reports
  - Something like:
  
  Monthly Summary 
  Food 
  £120

  Transport
  £85

  Entertainment
  £34
------------------
  Total
  £239
  
GIT
- Lots of branches
  - Merge every feature
  - Delete every feature branch
e.g. 
  - main -> feature/add-expense -> feature/search -> feature/statistics -> feature/json -> feature/reports


- Stretch Goals - can do after everything is complete
  - Sort by amount 
  - Sort by date 
  - Sort by category 
  - Export CSV 
  - Monthly reports 
  - Pie chart (later)