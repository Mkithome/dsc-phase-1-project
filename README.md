# Microsoft Movie Studio Investment

**Author**: Martin Kithome

## Overview

I wanted to solve the business problem of optimizing sales performance on behalf of Microsoft company with  data visualization project. Understanding sales patterns, recognizing important growth prospects, and making data-driven decisions were all hurdles for the organization. I compiled a large dataset that comprised transactional information, consumer demographics, product qualities, and website interactions. I studied the data using a number of data visualization approaches, such as bar charts, histogram, scatter plots, and box plot, to glean significant insights. Seasonal changes, popular product categories, and customer behavior patterns were highlighted in the findings. I was able to identify areas of underperformance and offer targeted marketing tactics by displaying sales performance across multiple geographies and marketing channels. Furthermore, interactive dashboards were created to allow for real-time monitoring of important performance indicators.

## Business Problem

Microsoft is eager to venture into the world of original video content creation, inspired by the success of major companies in this domain. They are determined to establish their own movie studio; however, lacking expertise in filmmaking, they seek guidance on the most successful film genres at the box office. As the assigned analyst, my primary task is to explore current box office trends and derive actionable insights for Microsoft's movie studio head. By examining the types of films currently thriving in theaters, I aim to provide valuable guidance for decision-making on the studio's future film projects.

Questions to Consider:

1.What are the business pain points related to this project?
The main pain point for Microsoft's new movie studio is the lack of knowledge and experience in the film industry. Without understanding the current market trends and audience preferences, they risk producing films that may not resonate with the viewers, leading to potential financial losses and missed opportunities to compete with established players in the industry.

2.How did you pick the data analysis question(s) that you did?
To address the business's pain points, I chose the data analysis questions that revolve around identifying the most successful film genres at the box office. By analyzing the box office performance of different movie genres, we can determine which types of films are currently attracting the most audiences and generating substantial revenue. This information will be crucial in guiding Microsoft's movie studio in selecting the right genres to focus on for their initial film projects.

3.Why are these questions important from a business perspective?
From a business perspective, understanding the box office performance of various film genres is vital for Microsoft's movie studio. It helps them make informed decisions and strategic investments in projects that have a higher likelihood of success. By focusing on genres that are currently popular and financially rewarding, they can increase their chances of producing films that will attract a broader audience and generate significant profits. Additionally, this data-driven approach minimizes the risk of producing films that might not resonate with viewers and ensures a more competitive position in the dynamic and highly competitive movie industry.

## Data

The provided data is contained within the folder "zippedData" and includes datasets from various sources, namely Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers. The datasets utilized in this analysis are:

imdb.title.basics: This dataset contains information about movies, including the original title, release year, runtime duration in minutes, genres, and the studio responsible for production.

imdb.title.ratings: This dataset provides movie ratings based on reviews, including the average rating and the number of votes received.

bom.movie_gross: This dataset encompasses details about the box office performance of movies, including domestic and foreign gross revenue figures, and the release date.

Data Description:
The movie datasets offer valuable insights into the film industry, covering essential attributes such as movie titles, release years, genres, runtime durations, average ratings based on reviews, number of votes, production studios, and box office gross revenue figures for both domestic and foreign markets.

Libraries Used:
For the analysis and exploration of the movie datasets, Python serves as the primary programming language. The Pandas library facilitates exploratory data analysis, Seaborn enables data visualization, while NumPy supports numerical computing and data analysis. Lastly, Matplotlib aids in creating visualizations for a more comprehensive understanding of the movie-related insights.

With this rich and diverse collection of data and the robust set of Python libraries utilized, we can explore current box office trends, identify successful film genres, and provide actionable insights to aid Microsoft's new movie studio in making informed decisions about the types of films to create.

### Visual 1
![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/94ae291b-b460-4f37-afc9-e697a0bb1c4e)

### Visual 2
![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/4eb1150d-295d-4766-8bff-7b8645da598f)

A correlaton bellow 0.5 indicates weak correlation, which means a movie could run for over 2 hours and still be rated highly, or have a runtime of below 70 minutes and still be rated highly. From the previous visualizations, remarkable rating could result from the type of genre and also the studio type.
### Visual 3

![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/86ed8204-1c8b-4851-8354-be9e0fc5f074)

### Visual 4

![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/c2078de0-4cee-4828-a6a1-f25c8fa8e960)

### Visual 5

![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/5c150334-2de4-41f2-941c-8046aaa8b3cc)

### Visual 6

![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/cd86de6b-8580-408a-a089-600d26fd66a8)

### Visual 7

![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/4a70cd03-1c1b-4277-9b04-5e8e810dd354)

The reason why some studios are more highly rated than others is because some are complex and multifaceted, and can vary based on the individual studio and film.

### Visual 8
![image](https://github.com/Mkithome/dsc-phase-1-project/assets/133040796/64ed5b6c-1796-4261-9722-1cda85119a13)






## Conclusions
Based on the analysis conducted on the movie datasets, I recommend the following actions for Microsoft's movie studio:
a) Focus on Action Films: Given the positive correlation between the number of votes and domestic gross income for Action movies, Microsoft should prioritize producing action-oriented content. This genre offers a cost-effective way to engage a wide audience and potentially generate substantial revenue.

b) Explore Adventure and Comedy Genres: Adventure movies also show high viewer engagement, as indicated by their significant number of votes. By exploring Adventure genres, Microsoft can tap into an audience that enjoys thrilling and adventurous content. Additionally, venturing into comedy movies offers an opportunity to begin production with relatively lower costs and a chance to attract a diverse audience.

c) Emphasize Drama Films as Starting Point: Drama movies, being cost-effective to produce, can serve as an ideal starting point for Microsoft's movie studio. By focusing on this genre, the studio can build a strong foundation and establish its presence in the market before delving into more elaborate productions.

Limitations of the Analysis:
While the analysis provides valuable insights for Microsoft's movie studio, there are some limitations to consider:
a) Limited Dataset Scope: The datasets used in this analysis represent a specific timeframe and may not encompass all recent movie releases or capture rapidly changing audience preferences. A broader and more up-to-date dataset could yield even more accurate and comprehensive insights.

b) Genre Complexity: The movie genre classification can be subjective and may not fully capture the nuances of each film. Some movies may belong to multiple genres, making the categorization challenging and potentially affecting the analysis results.

c) External Factors: The analysis does not account for external factors, such as marketing campaigns, release timing, or competition, which can significantly impact a movie's performance at the box office.

Future Improvements and Next Steps:
To enhance this project in the future, the following steps could be taken:
a) Incorporate External Data: Integrating additional data sources, such as marketing expenditures, release schedules, and critical reviews, would provide a more comprehensive understanding of the factors influencing movie success.

b) Advanced Analysis Techniques: Utilize advanced machine learning algorithms to predict the potential success of a movie based on various features, helping Microsoft's movie studio make more data-driven decisions.

c) A/B Testing: Conduct A/B testing on selected movie releases to test different marketing strategies and gauge audience reactions, allowing for continuous optimization and learning.

d) Industry Expert Consultation: Seek advice from industry experts or collaborate with experienced filmmakers to gain deeper insights and refine decision-making strategies.

In conclusion, this project offers valuable recommendations for Microsoft's movie studio to strategically enter the movie production industry. Despite some limitations, further improvements and future steps can enhance the accuracy and effectiveness of the analysis. By implementing these recommendations and refining their approach based on continuous learning, Microsoft's movie studio can position itself for success in the competitive film market.


## For More Information

Please review the full analysis in [the Jupyter Notebook]https://github.com/Mkithome/dsc-phase-1-project/blob/master/student.ipynb or the [presentation]https://github.com/Mkithome/dsc-phase-1-project/blob/master/Presentation.pdf.

For any additional questions, please contact **Martin Kithome, martin.kithome@student.moringa.com**
