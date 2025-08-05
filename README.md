# Movie Analysis Project: 
# Analysing Insights for a New Film Studio

## Overview

A company is interested in entering the movie studio industry. This is based on the performances of films from studios such as Warner Bros, Sony, and Paramount Pictures. They have no background/knowledge of the film industry, but are excited to try it out. They would like an analysis of the movies that have been performing well to make a data-driven decision.

**Key focus points:**

1. Which genre of movies is performing well at the Box Office
2. How much revenue are they making
3. The ratings of the movies and their respective budget
   
The focus points are to guide the company into ensuring the films produced and released are performing well (ratings) at the Box Office, are a good investment, and they work well with the given budget.

**Datasets used:**

- IMDB dataset
- bom.movie_gross dataset
- tn.movie_budgets dataset
  
**Outcome:**

3 or more recommendations for the potential new movie studio. This helps guide the
company to make an appropriate and data-driven decision.

The project explores historical movie data to answer a key business question:

**“Which genre of films perform best at the box office, and how should our new movie studio invest?”**

Using exploratory data analysis (EDA), this project identifies trends, risks, and opportunities in film production by analyzing over a decade of movie performance across budget, genre, studio, and ratings.

---

Insights to study/focus on: 

- What genres succeed commercially
- What budget range is optimal
- Which studios to benchmark

---

## Data Cleaning & Preparation

- Removed duplicates and nulls
- Standardized titles (lowercase)
- Studied and concluded not to drop outliers due to a real-world analysis
- Converted columns to the appropriate data types
- Merged datasets on `title` and `year`
- Final dataset: > 1,000 movies between 2010-2018

---

## Key Columns Used

- `production_budget` – Cost to produce the film
- `worldwide_gross` – Total global revenue
- `genres` – genre (Action, Comedy, etc.)
- `studio` – Producing/distributing studio
- `rating` – IMDb rating
- `year` – Year of release

---

## Highlights from Analysis

### Budget Distribution
- Most films are produced on small budgets, but a few high-budget blockbusters dominate total spend eg, Avengers.

### Box Office Performance
- The box office is skewed: a small number of films earn most of the revenue.

### Top Performing Genres
- Action, Adventure, and Animation consistently generate the highest median worldwide gross.

### Studio Comparison
- Major studios like Disney and Warner Bros show consistent financial success. Which would be potential competitors/teammates in the industry

### Budget vs Gross
- Having a high budget does not guarantee a high return. Therefore, it'll be a huge risk for a potential new studio.

### Ratings vs Revenue
- The high ratings and popularity of a film does not guarantee high returns as well.

---

## Recommendations

1. Focus on the genres that have the highest returns. Adventure, animation, comedy, action, and sci-fi have the highest return at the box office. Over the years, the films that have performed well in specific studios have been family-friendly. Examples would be Avengers, Toy Story 3, which have been blockbusters and highly rated as well.
2. Work with, or learn from, the top studios in the film industry: Warner Bros, Disney, Universal Studios, Fox, and Sony. They have been able to create a name for themselves and remain successful over the many years of releasing movies. As much as they may not always gross highly in all films, they can return a solid average.
3. Monitor the industry. The trends over the years, how the potential competitors are doing, genres that are performing well in that season, the hiccups being faced, and more historical and recent data as well. The current data is just before COVID-19; hence, concluding the performance in the industry is very limited.
4. When it comes to the budget, it is important to look at the risk and reward. There are instances where the company can invest a high amount into the production of a film, and does not gross highly, and vice versa. It is a huge risk. Finding ways to invest not too much into the production, advertise it, and work on the target audience to create popularity towards the film and high ratings, can lead to a high gross.

---
## Tableau 

https://public.tableau.com/app/profile/june.henia/viz/InteractiveDashboard_17512169513430/InteractiveDashboard?publish=yes 

