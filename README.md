# Project Summary:

**Turtle Games: Customer Segmentation & Sales Optimisation-** 98% final grade.

**Project Focus:** In my third 8 week assignment for LSE  my objective was to investigate customer loyalty and optimise sales performance for Turtle Games,  a global gaming retailer and manufacturer.  I used a comprehensive suite of data analytics techniques with a real focus on several new skills. In particular this assignment really cemented a  significant passion for Natural Language Processing. 

For this assignment I distilled the context down to one business question How can Turtle Games use data to enhance customer loyalty
and sales? Then the core business question is split into two parts:

- Part 1: **Who are Turtle Games' customers and what are their habits?**
    - Customer Insights
    - Customer Segmentation
    - Customer Feedback
- Part 2: **What do sales data reveal about market trends and performance?**
    - Platform Performance
    - Sales Trends & Predictive Modelling

## **Analytical Approach Highlights**:

- **Customer Segmentation**: Leveraging Python and R, I performed multiple linear regression (MLR), K-means clustering, and natural language processing (NLP) on Turtle Games' customer base data. This revealed factors influencing customer loyalty points and facilitated the segmentation of customers into distinct spending behaviour groups for targeted marketing strategies.
    - K means clustering of two variables that showed promising correlation
    - ![image](https://github.com/Wburto/TurtleGames/assets/132344378/31e284e2-c990-4324-9e8f-308415ddc25a)

    - Group 1 - 774 observations 39% - A signifcant amount of total observations that operates around the middle of both variables suggesting arguably the strongest market segment to target. Worth considering other factors to flesh out. This is a high priority and the bread and butter of sales. Worth noting that the income range of this group seems to fit the mean of 48 well. The spending_score range fits the mean of 50 well too.

    - Group 0 - 356 observations 18% - Group 0 offers the golden goose of high income earners who also have a high spending_score. Even though they amount to jsut under half group of group 1 they are spending a relitively high amount so are still a relevant segment who are actively engaging and should be proritised. This is a high priority.

    - Group 2 - 330 observations 17% - Group 2 shows a segement that has potential to earn a higher spending score with more income available. As such, marketing needs to understand and address why this group isn't achiveing it's spending score potential. This is a high priorty to turn those Group 2 customers into Group 3.

    - Group 4 - 271 observations 14% - Group 4 show the least potential of all groups and also only contribute 14% of total observations. While there is always potential Group 4 should be seen as a low priority

    - Group 3 - 269 observations 13% - Group 3 show great potential again and have proven loyalty through their spending score in spite of low income. It is worth considering other factors in Group 3's income to see if there is any future benefit to targeting them. For instance if Group 3 doesn't earn much income because of Age being a contributing factor, working on retaining that base as customers and rewarding loyalty will only serve as positive if they grow older and their salaries grow with them.
   
    - A heatmap of customer information variables
    - ![image](https://github.com/Wburto/TurtleGames/assets/132344378/e6d0aba2-aab2-458f-a73f-261d30438ad3)


A heatmap of customer information variables

- **Sales Data Exploration**: A thorough analysis of sales data, visualised through R, unearthed critical insights into platform performance and sales trends. This identified which gaming platforms contributed most significantly to sales, providing a clear direction for Turtle Games to focus inventory and marketing efforts.
- **Predictive Modelling for Strategic Forecasting**: MLR models were built to accurately predict future sales trends based on regional sales data. This not only showcased the strong relationship between regional and global sales but also equipped Turtle Games with the tools for strategic resource allocation and sales strategy optimisation.
    
    ![A graphic made in R exploring national sales data compared to global sales data..](https://prod-files-secure.s3.us-west-2.amazonaws.com/4394a732-f9f1-4e08-94ea-113fc19ce7c0/7d3af5e5-8d16-46f1-bc98-dbc951812532/Rplot01.png)
    
    A graphic made in R exploring national sales data compared to global sales data..
    

## **Key Insights and Recommendations:**

- I curated a robust predictive model with 97% accuracy, linking regional sales to global sales, underscoring the significant predictive power of NA and EU market performance on global outcomes, suggesting strategic focus areas for market investment and resource allocation. I also created an interactive Shiny App interface, enabling stakeholders to intuitively utilise the predictive model for strategic planning without technical expertise, enhancing decision-making efficiency.
    - Please explore the interactive Plotly plot exploring my MLR model results that is referenced in the video later on.
        
        [MLR Plotly.html](https://prod-files-secure.s3.us-west-2.amazonaws.com/4394a732-f9f1-4e08-94ea-113fc19ce7c0/ac471685-b3a2-4575-af7d-43896323543c/MLR_Plotly.html)
        
- I identified and addressed data challenges including heteroscedasticity and multicollinearity, emphasising the need for precise data handling, further refined data and advanced statistical techniques to refine predictive accuracy.
- I Highlighted the critical role of outliers in skewing sales data, necessitating sophisticated outlier management strategies to ensure model reliability and real-world applicability.
- I discovered key insights into customer feedback using techniques like word clouds. While the report showed an overall positive sentiment, attention needs to be paid to harnessing recommendations from positive/neutral feedback. Also encouraged investing in multilingual NLP tools and proactively investigating negative customer feedback.
    
    ![A word cloud from normalised positive reviews of products using Vader as the model. ](![image](https://github.com/Wburto/TurtleGames/assets/132344378/9a8d9f4c-a961-4b14-8143-16c4ab91bef6)

    
    A word cloud from normalised positive reviews of products using Vader as the model. 
    
- I noted the evolving market dynamics for regions. For instance PlayStation, transitioning from a strong North American preference (41% market share for the original PlayStation compared to Europe's 31%) to a dominant position in Europe for the PlayStation V (45% of sales in Europe and 42% for the rest of the world, compared to North America's 13%).
    - Download the interactive stacked bar chart from the file below that is referenced in the presentation video at the end.
        
        [Platform graphic Plotly.html](https://prod-files-secure.s3.us-west-2.amazonaws.com/4394a732-f9f1-4e08-94ea-113fc19ce7c0/62717405-89d7-41a0-bd32-c33ad6438113/Platform_graphic_Plotly.html)
        

## **Professional Development and Project Impact:**

This project served as a deep dive into the intersection of data analytics and strategic business decision-making. The wide variety of skills and tools used (Python, R, MLR, K-means clustering, and NLP) really allowed me to understand and consolidate several key areas of analysis.
