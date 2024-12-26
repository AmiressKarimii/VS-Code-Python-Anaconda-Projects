# The Analysis

## What are the most demanded skills for the top three most popular data roles?

To find the most demanded skills for the three most popular data roles. I filtered out those positions by which ones were the most popular, and got the top 5 skills for these top 3 roles.

View my notebook with detailed steps here:
[2_Skills_Count.ipynb](3_Projects/2_Skills_Count.ipynb)

### Visualize data

```python

df_job_title_count = df_US['job_title_short'].value_counts().reset_index(name='jobs_total')

```

### Results
![Visualization of Top Skills for Data Nerds](3_Projects/Images/Skills%20Percent.png)


### Insights

What we learned from this chart : 
- Python and SQL are the most required ones