# Data Science Project: COVID in Canada

This project aims to understand the discussions currently happening around COVID in Canadian social media, especially about the discussions surrounding vaccine hesitancy, such as but not limited to:
1. The salient topics discussed around COVID and what each topic primarily concerns
2. Relative engagement with those topics
3. How positive/negative the response to the pandemic/vaccination has been.
A quantitative analysis has been conducted and the results have been discussed in the report.

The analysis was drawn on Twitter posts (tweets). To inform the analysis, we have collected 1,000 tweets within a 3 day window. We have set filters such that all 1,000 posts mention either COVID, vaccination, or a name-brand COVID vaccine AND all are in English.

Each tweet in the aggregated dataset was ensured to be unique.
To develop the main topics surrounding the discussions on the social network platform, open coding on 200 tweets was conducted.

Once the main topics have been designed, rest of the 1,000 tweets in our dataset were manually annotated with the topic of discussion and positive/neutral/negative sentiment. The topics were characterized by computing the 10 words in each category with the highest tf-idf scores (inverse document frequency).

You can read the report from [here](https://github.com/beyza-yildirim/Data-Science-Project-COVID-in-Canada/blob/master/COMP_598_Final_Project_Report.pdf).
