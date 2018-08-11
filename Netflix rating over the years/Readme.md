## Applying well-known split-apply-combine strategy, on Netflix movie data.

### Project Description

Netflix recently released some user ratings data. A question arises: do Netflix subscribers prefer older or newer movies?

Split-apply-combine strategy :-

**Step 1**: split the data into groups by creating a groupby object from the original DataFrame.

**Step 2**: apply a function, in this case, an aggregation function that computes a summary statistic (Can also transform or filter your data in this step)

**Step 3**: combine the results into a new DataFrame.

Pandas, groupby objects and the principles of split-apply-combine are used to check out how Netflix movie ranges vary as a function of the year they were released.
