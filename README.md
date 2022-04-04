# Kickstarting with Excel

## ***Overview of Project***

### **Purpose**
Give Louise an analysis with a detailed insight of trends of the different campaigns fared in relation to their launch dates and their funding goals. In order to make her aware of some crucial data to be considered for a future fundraising, or to grab this analysis an understand the "why?" her actual campaign didn't accomplish her funding goal.

## ***Analysis and Challenges***

### **Analysis of Outcomes Based on Launch Date**

The next graph is comparing **Theater Outcomes vs. Launch** of the category: *Theater*. The outcomes that were taken in mind for the graph are the *successful*, *failed*, and *canceled* outcomes based on their launch date. Also, the graph is showing the behavior in the months through the years contained in the database of the 3 selected outcomes.

![This is an image](Theater_Outcomes_vs_Launch.png)

    As a first instance conclusion, we can observe that the 'successful' and 'failed' outcomes have a similar behaviour in the graph. Just the fluctuation in the 'failed' outcome is more subtle. 

### **Analysis of Outcomes Based on Goals**

The next graph is comparing **Outcomes vs. Goals** of the whole categories and subcategories, but also taking in mind only the *successful*, *failed*, and *canceled* outcomes. As well, for a better understanding of the information, it is presented into percentages to show the trends of a prestablished ranges of money outcomes per campaign. (The money ranges were established with a diference of 4,999 USD, except less than 1,000 USD and more than 50,000 USD; for example, 1,000 to 4,999 - 5,000 to 9,999 - 10,000 to 14,999 - etc.)

![This is an image](Outcomes_vs_Goals.png)

    As a first instance conclusion, we can observe that the percentages line charts of the 3 outcomes behave quite different one from another. There's no similarity between them.

### **Challenges and Difficulties Encountered**

- A good example that was a difficulty and a challenge was the 'Deadline' and 'Launched At' dates. First, the difficulty was that as an initial view the information is not quite understandable, and besides that, you need some kind of know-how to catch that it is an 'epoch reference'. As challenge, initially is to find that is an epoch timestamp but the biggest challenge is to translate this data into a readable date (human at least). To overcome the timestamp situation, we need a simple formula that could change the timestamp could into a date with Day/Month/Year.

- In a technical matter, a difficulty was the integration of the images in the analysis. When I was inserting them, at the 'Preview' I noticed they weren't displayed, this because I was pasting the 'https' link from GitHub after the [This is an image] text. At the end, it was only needed to be indicated with the name that it was saved at the repository.

- As a personal challenge, this is the first time I am doing an 'Overview of Project' since I finish my bachelor, so I review it and change it a lot of times. Hoping it is correct, but waiting to see the feedback.

## ***Results***

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  - The Theater category have a great number of successful projects that were funded. From a total of 1,369 campaigns, 839 requests were successful. This is more than the half of the total selected outcomes.

  - As well, we can see the best months to launch a Theater campaign are *May*, *June*, or *July* (in that order); as can be seen in the graph, compared to other months, these three have more than 80 succesful campaigns per month. In addition as a recomendation, *December* shouldn't be considered to launch a campaign, because apart from the fact that it is the lowest of the success rate, it is almost equal to the results of failed outcomes; in terms of numbers the outcomes in December were '37 (succesful) vs. 35 (failed)' - only a difference of 2 campaigns between those outcomes.

- What can you conclude about the Outcomes based on Goals?

  - For the selected outcomes based on goals, we can see that even we chose 3 outcomes (successful, failed, and cancelled), the percentages were divided between 'succesful' and 'failed'. The tendecy for each line chart is quite different, we can even say that they could be inversely proportional.
  
  - Also, there's no "safe" amount to ensure the campaign goal is going to be reached. The trend in both line charts are not showing that the money amount is directly proportional to the successfulness, in other words, a small amount of money doesn't ensure you'll get the money, and big amounts don't mean that you will be rejected.

- What are some limitations of this dataset?

  - Inferring that the information is required for a campaign for 2022, the data is quite outdated. The database is from 2009 to 2017.

  - There's some data that the meaning is not quite clear and hence the information is not certain to be helpful for a better analysis, for example, 'staff_pick'.

- What are some other possible tables and/or graphs that we could create?

  - A table/graph to check the range days between Deadline date and Launch date, the reason is to check if there's a correlation between the successful campaigns and that range.

  - A table/graph of the subcategories from the Theater and outcomes to check which ones are more successful.

  - A table/graph between the outcomes and the countries to see which country has better percentages at the successfulness outcomes.

  - A table/graph to compare the tendency of the average donation based on goal/pledged, to check if there's a significant relation.