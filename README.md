# What are the most optimal skills for a data nerd? 🤓
Using ChatGPT, I was able to uncover the most optimal skills to learn as a data nerd based on real-time data science job posting data from [datanerd.tech](https://www.datanerd.tech)

## The Findings
The most optimal skills were determined by developing a metric, termed "Skill Multiplier", that aggregates both the normalized demand and normalized salary of a given skill for a job title. 

### Normalized Value Formula

The normalized value for each skill within a job title is calculated as:

$$
\text{Normalized Value} = \frac{\text{Value} - \text{Min Value within Job Title}}{\text{Max Value within Job Title} - \text{Min Value within Job Title}}
$$

### Skill Multiplier Formula

The skill multiplier, which combines the normalized skill count and normalized median salary, is calculated as:

$$
\text{Skill Multiplier} = \text{Normalized Skill Count} \times \text{Normalized Median Salary}
$$

### Results for Top 3 Jobs
Below, the top jobs in data science are displayed and showcasing that Python and SQL are two of the most optimal skills across these roles.  

![](images/optimal_skills_3.png)