# Analysing Public Perception of Mr. Beast's Controversial Video on YouTube Through Text Mining

## Abstract
1. Social media enables direct connections among consumers, influencers, and companies. Influencers such as Mr Beast may have a significant impact by increasing awareness about social issues and charity. However, some have criticised their actions, accusing them of exploiting those in need or promoting prejudices.
2. The research found a positive public attitude toward Mr Beast's charity initiatives in Africa. However, we also found more negative sentiment in topics discussing saviours and complaints about Mr Beast's behaviour in assisting people. From the correlation among topics, there are two leading groups in discussion. One is Mr. Beast's behaviour in charity. The other is ethical concerns and social-political issues in Africa. Compared with previous campaigns, which also utilised portrayal of poverty for fundraising, such as Kony 2012 and Benefit Street, despite the success of these attempts to increase awareness. The study emphasises the need to provide accurate representations and find long-term solutions.

## Methods
![flowchart drawio](https://github.com/user-attachments/assets/e39a5ea1-d6d3-4892-b763-5d6756e0fc01)

1. Over 30,000 comments were gathered using Mozdeh and the YouTube API. The NLTK toolbox in Python was used for text pre-pressing.
2. We implemented the NMF model to conduct Topic modelling. Subsequently, we combined the topics with sentiment analysis by VADER.
3. Lastly, we also performed dimensionality reduction using the t-SNE model to uncover correlations between themes and discuss them with previous literature.
   
## Data Exploration Analysis

![TOP_20words](https://github.com/user-attachments/assets/8b909931-a692-4a0d-8fcf-f26d05ad9e10)
1. Word cloud of Top 20 words in comments:
* This Figure uncovers the top 20 significant words. Mr Beast stands out as the most used word in the comments, suggesting that the YouTuber was the primary topic of discussion. Additionally, “People” and “Africa” are prominent. The word "Well" is most likely about the wells built in the video.



![bi-gram](https://github.com/user-attachments/assets/fc749e6d-28c5-427a-80f9-04bee2a473cf)
2. Word cloud of Top 15 words(bi-gram) in comments:
* In this Figure, the most common bigram is “mr beast” followed by “help people” and “clean water”. Additionally, terms like “white savior” and “black people”, which appear less frequently, likely relate to the controversy surrounding Mr Beast.

## Topic Modelling 

* Topic 0: people, help, helping, mad, need, dont, hate, want, complaining, like, helped
* Topic 1: beast, mr, love, thank, god, ha, bless, like, hate, hater, cancel
* Topic 2: good, thing, deed, unpunished, bad, world, doe, hate, person, man, work
* Topic 3: water, clean, drinking, access, drink, care, dont, need, kid, wa, giving
* Topic 4: white, black, racist, man, savior, guy, wa, person, racism, complex, calling
* Topic 5: money, video, make, like, wa, charity, doe, making, mrbeast, ha, view
* Topic 6: africa, african, country, government, ha, dont, poor, need, help, problem, corrupt

1. According to the weights of words in each group and give a name. 
![weight](https://github.com/user-attachments/assets/4b53a6a8-e72d-447c-8d45-478f289dd80d)

2. Topics and counts of comments. 
![output](https://github.com/user-attachments/assets/6bf36db4-b50b-4d27-ab9d-e406f0e1633c)



## Sentiment Analysis
1. Sentiment of total comments
![total_Sentiments](https://github.com/user-attachments/assets/8927036f-59ae-4ba3-bbf6-acd0a43b0d03)


2. Topics and sentiments

![NvsP2](https://github.com/user-attachments/assets/8a11ab05-0b64-44c8-a83f-e5f54359a646)

## t-SNE(t-Distributed Stochastic Neighbor Embedding)
![conclusion](https://github.com/user-attachments/assets/c5a0a6ec-80c3-4cbe-b5f6-1388541087b8)
