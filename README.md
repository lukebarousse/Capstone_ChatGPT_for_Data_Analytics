# What are the most optimal skills for a data nerd? 🤓
Using ChatGPT, I was able to uncover the most optimal skills to learn as a data nerd based on real-time data science job posting data from [datanerd.tech](https://www.datanerd.tech)

The most optimal skills were determined by developing a metric that aggregates both the demand and salary of a given skill. 

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

The results of the research are detailed further below, with teh top 3 jobs highlighted here; showing that Python and SQL are not only the highest in demand 📈 but also some of the highest paid 🤑. 
![](images/optimal_skills_3.png)