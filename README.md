# Launching Microsoft's Movie Studio
-Andrew Choi , Timothy Cleary , Olamide Olayinka
![alt text](https://logos-world.net/wp-content/uploads/2020/09/Microsoft-Logo.png)
 ## Overview
With this project we aim to provide solid analysis and guidance to assist Microsoft in their goal of launching a new movie studio. Through our analysis, we discovered the proper way to enter the industry while avoiding common pitfalls.

-----

 ### Business Understanding
Microsoft is a multinational corporation known for producing software, electronics , computers, video games and so on. Microsoft now plans to venture into film and movie production. Some key questions we answered include: What movie genres bring in maximum earnings? What kind of directors should Microsoft hire? How does Microsoft go about rating the movie and would that affect sales? In our research, we discovered some recent movies that vastly underperfromed their production budgets. According to [Work and Money](https://www.workandmoney.com/s/biggest-box-office-bombs-movie-flops-8225f2e154084d6b), movies such as Black Widow and The Mummy(2017) lost over **half** of their budget cost.

-----

### Data Understanding and Analysis

The data comes from a Rotten Tomatoes dataset. The code for creating the graphs can be found in our included jupyter notebook. This set included movies Box Office number, the rating, the director and genre. With the box office number, it is measured by millions of dollars. We utilized seaborn to plot our graphs. For the following graph we filtered down the dataset to utilize the genre and box office columns. We used a bar graph to show the relationship between specific genres and their box office earnings. We filtered it down to the top twenty however we focus in on the top two, comedy & drama. Comedy brought in a whopping **$1.5 Billion** during our analysis.

Genre & Box Office Relationship
![alt text](https://i.imgur.com/023cjm6.png)


Movie's Rating & Box Office Relationship 
![alt text](https://i.imgur.com/kpg7vcS.png)

Top Directors & Box Office Relationship
![alt text](https://i.imgur.com/tM1MFil.png)

-----

### Conclusion
We believe that with our analysis and model Microsoft would be able to successfully enter the movie industry. Based on the data, comedy movies have returned the biggest box office numbers. This aligns with our goal of helping Microsoft break into the field while retaining maximimum profit. Futhermore we suggest selecting an experinced director. Seasoned directors had higher box office earnings due to their cache and success within the industry and thus we recommend to hire an established director. We were also able to see that Pg-13 or R movies would be an appropriate rating to aim for.


-----

### Repository Structure
├── Data -- master.csv -- rt.movie_info.tsv
├──.gitignore
├──Project 1 Notebook.ipynb
├──-README.md
