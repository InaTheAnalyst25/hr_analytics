# hr_analytics

Salifort Motors seeks to improve employee retention amd answer the following question:
What's likely to make the employee leave the company?

This model helps predict whether an employee will leave and identify which factors are most influential. These insights can help HR make decisions to improve employee retention.

Since the variable we're likely to predict is categorical we could build either a logistic regression or a tree based mashine learning model. The random forest slightly outperform sthe decision-tree model.

In the random forest model above, `last_evaluation`, `tenure`, `number_project`, `overworked`, `salary_low`, and `work_accident` have the highest importance. These variables are most helpful in predicting the outcome variable, `left`.

Based on the analysis the folllowing measures could be proposed:

Cap the number of projects that employees can work on.

Consider promoting employees who have been with the company for at least four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.

Either reward employees for working longer hours, or don't require them to do so.

If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.

Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.

High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort.







