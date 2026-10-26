---
name: budget-check
description: Compare this month's spending against budgets and flag anything over or near its cap.
---

Use this when the user asks how spending sits against their budgets.

1. Call get_my_budgets and get_my_financial_summary.
2. Compare month-to-date spending against each budget cap. Flag anything over budget or above 80 percent of its cap.
3. If has_budgets is false, say no budgets are set yet. Do not invent budget numbers.
4. Use the numbers exactly as returned. Nothing moves money.
