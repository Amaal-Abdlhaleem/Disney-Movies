# **Analyse Disney Movies**

#### This report contain exploring, cleaning and visualizing Disney movies data to answer some questions.

![dashboard](https://user-images.githubusercontent.com/65326291/137313234-fbe9f21d-34ab-45f8-8738-ec33b01e44c6.png)

###### Disney Movies Dashboard

## **Introduction:**
This project seeks to explore and analyse Disney movies data. Disney data contains 5 files:
- disney_characters.
- disney_director.
- disney_movies_total_gross.
- disney_revenue_1991_2016.
- disney_voice_actors.

But we access (disney_movies_total_gross) file because it has our scope of answers.
(disney_movies_total_gross) file contains 6 columns:
- movie_title.
- release_date.
- genre.
- mpaa_rating.
- total_gross.
- inflation_adjusted_gross.

In this report, We answered some questions:

- What is the number of total gross?
- What is the number of totall movies?
- What is the number of movies per MPAA rating?
- What is the top 10 movies which have huge total gross?
- What is the number of movies per genre?
- Show the total gross along years.

## **Methodology:**
The data was cleaned and specific it to the small target to analyse. Starting with some important analytic numbers to Disney movies:

1. Total gross.
2. Total number of movies.

![1](https://user-images.githubusercontent.com/65326291/137313296-3614c536-2d22-466d-8332-d4adc6613f29.png)

### **Number of movies by MPAA rating:**
- PG    --> Parental Guidance Suggested  --> (Parent Guidance)
- PG-13 --> Parents Strongly Cautioned   --> (+13 & Parent Guidance)
- R     --> Restricted Under 17 requires accompanying parent or adult guardian --> (-17 & Parent Guidance)
- G     --> General Audiences --> (All)
- Not Rated

![rating](https://user-images.githubusercontent.com/65326291/137313429-75021a7f-4590-4dd3-a041-48e23abc7464.png)

The chart show that large number of Disney movies suggested to watch with parental guidance.

### **Top 10 movies:**

![top10](https://user-images.githubusercontent.com/65326291/137313347-8dd37c73-6c02-424a-b662-387f98db0dab.png)

This shows top 10 total gross movies.
As "Star Wars Ep.VII: The Force Awakens" movie was the largest total gross with 936,662,225$.

### **Number of Movies by Genre:**
Disney have 12 genre:
- Comedy.
- Adventure.
- Drama.
- Action.
- Thriller/Suspense.
- Romantic Comedy.
- Musical.
- Documentary.
- Western.
- Horror.
- Black Comedy.
- Concert/Performance.

![genre](https://user-images.githubusercontent.com/65326291/137313309-cbb6aa32-577a-4dc3-a232-1d07d10480ed.png)

The chart shows that Disney interested more about comedy movies because it produced 162 comedy movies of  the total movies.


### **Total gross by year:**

![year](https://user-images.githubusercontent.com/65326291/137313326-1b09d0de-e7b7-4f45-8614-4429b9ad6d8d.png)

The chart shows that Disney earned the largest total gross on 2016 by 287,339,3105$

## **Resources:**

[Disney Movies dataset](https://data.world/kgarrett/disney-character-success-00-16).

