# Back to the data - duh!

Today we go back to basics, we go back to where we started. The data, the data is the most important part. Every data science group is different and the data groups 
have goals. This of course is not specific enough to be meaningful so lets dive into more detail. Data science groups are only as meaningful as their
insights and they are not standalone. Data science groups are informed by produce managers and executives who have information about the company
and the company priorities. This might sound a bit vague at the moment but it is important for data scientist to be informed about the business model of 
the company they are working for and how the company earns money or what specifically the company finds valuable.

Every year publically traded companies publish annual letters to their shareholders. These letters detail the company strategy and certain
directions the company plans to take to improve and earn more money or provide a better product.

[Take a look](https://s2.q4cdn.com/299287126/files/doc_financials/2020/ar/2019-Shareholder-Letter.pdf?tag=bisafetynet2-20) at this years annual
letter to shareholders to get an idea of what one of those letters looks like/ Here are a few highlights from the letter:

** side note **
I am actually pulling points from the 2019 shareholders blog post because it is hosted on the web on the Amazon Day 1 blog. You can read this post
[here](https://blog.aboutamazon.com/company-news/2019-letter-to-shareholders), I might also encourage you to read some of the other blog posts on the site to get a better
understanding of how the company is planning world domination. hehe
I use Microsoft edge's web accessibility tools to read aloud the text from web pages so that I can take notes in a different screen while I "read" and the 
2020 shareholders letter is not hosted on the blog yet.

** Side Note 2 **
![alt text](https://github.com/amblount/datasciencesummerprogram/blob/master/amazon-letter-to-shareholderrs.png)

Looks like the letter for shareholders hosted on the site is actually from 2020. As I started listening to the letter I heard information about COVID-19, this is definitely happening in 2020. 
COVID was not a thing in 2019. Check title on the letter, 

> "2019-letter-to-shareholders"

It is even published in the URL. Clearly someone is not validating the data being pushed to the blog. Isn't it weird that a company as wealthy
as Amazon makes mistakes like this? I feel like they have enough people on staff to fix errors like these, but I guess not. Students, take a moment
to think about this and learn from this moment in time. Even when there is someone is charge of validating data and ensuring that it is correct,
this does not mean they actually do their job correctly. I will iterate ** AGAIN ** there are a LOT of data scientists and really people in general
in really highly paid positions who are not detail oriented and who make critical errors all the time. When you do not have a system in place to check
for errors it is likely that something will go wrong and when it does, you might not have a clue. You might assume that the data you are using for a model
has a particular meaning but something goes wrong in the pipeline and it breaks. There might be some days when data is not being collected 
you need some way to check whether this is happening and debug it. You need to go check why you got the results that you have and what exactly broke in the pipeline.
I wouls assume from this error that the blog post for 2019 is missing and the critical COVID-19 shareholder letter for 2020 is not hosted anywhere on the site.
I wonder whose job it is to fix this? I wonder what produce manager is in charge of that site and missed this. Shareholder letters are really important,
so there are many investors who do care about going back to read the letter and need to know they are reading the correct letter.

Anyway, back to the mislabeled letter...

** Full Stop **
![alt text](https://github.com/amblount/datasciencesummerprogram/blob/master/shareholder%20letter.PNG)
What is a shareholder letter anyhow? In the business world when does a shareholder letter come out and what time frame does it cover? I did a google search to figure it out and I found the [investopedia](https://www.investopedia.com/terms/s/shareholder-letter.asp) definition from the website useful. It seems to me like the shareholder report is supposed to summarize all of the learnings from the last fiscal year.

> Q: ** How is this company defining a fiscal year **
> Q: ** If this is a shareholder report from 2019, why are the COVID-19 updates in this report? ** 
I realize the pandemic has changed everything, but shouldn't all of the updates for 2020 be in the 2020 shareholder letter that comes out in 2021? If something changed shouldn't they create a new type of report that would take into account these changes? It would seem like a good idea to have a mandatory inevstor meeting to review all of the new changes to the supply chain because of COVID-19. Given these changes will likely affect the supply chain for the forseable future, wouldn't there need to be new processes put into place to start to detail these important company changes to shareholders?

These are just some of the questions I have because if there were a model in production analyzing shareholder meetings by year and the 2019 year in review report included major company shifts that occured in 2020, this would overshadow the company strategy and growth that happened in 2019, which is also important to think about when recommending a stratefy for 2020 or even 2021. COVID changes everything I guess even Models. 

- Demand for essential products has spiked (What are essential products?)
- There was little warning of the spike so there was not enough time to plan
- Major challenges for suppliers and delivery network
- Stocking and delivery of critical products
- Whole Foods Markets remain open
- Closed parts of business that don't sell essential products
- Health and well being of employees
- 150 process changes in operations network
- Daily audits of measures put into place
- Social distancing measures in place
- Information sharing to bulleton boards
- Adjusted for hiring processes to account for social distancing
- Moved Program Managers and Engineers to testing measures
- Support for employees
- Paying associates overtime
- Wage increases for overtime will cost over $500 million dollars through the month of April
- Amazon relief fund - independent delivery drivers
- 100,000 new jobs across fulfillment and delivery network + 75,000 workers to help with customer support
- Some people rely on amazon to meet their critical needs (How do you determine who those people are?)
- Amazon is looking to protect customers who could potentially be exploited by bad actors during a time of crisis
- Removed over half a million offers due to price gouging and suspended accounts for violating fair pricing policies
- Academic institutions are transitioning to online learning and using AWS to help with this
- AWS public data lake to analyze COVID related information
- Last year co-founded the climate pledge, which commits Amazon to meet the goals of the Paris agreement 10 years early and be net zero carbon by 2040
- Amazon has extensive physical infrastructure to deliver more than 10 billion items per year
- Purchased 100,000 electric vehicle vans and are looking companies who can build new technologies that can help make the carbon neutral 
idea a reality
- Frustration free packaging program which encourages distributors to create 100% recyclable packaging

> Amazon’s sustainability scientists have spent more than three years developing the models, tools, and metrics to measure our carbon footprint. Their detailed analysis has found that shopping online consistently generates less carbon than driving to a store, since a single delivery van trip can take approximately 100 roundtrip car journeys off the road on average. Our scientists developed a model to compare the carbon intensity of ordering Whole Foods Market groceries online versus driving to your nearest Whole Foods Market store. The study found that, averaged across all basket sizes, online grocery deliveries generate 43% lower carbon emissions per item compared to shopping in stores. Smaller basket sizes generate even greater carbon savings.

> Over the last decade, no company has created more jobs than Amazon. Amazon directly employs 840,000 workers worldwide, including over 590,000 in the U.S., 115,000 in Europe, and 95,000 in Asia. In total, Amazon directly and indirectly supports 2 million jobs in the U.S., including 680,000-plus jobs created by Amazon’s investments in areas like construction, logistics, and professional services, plus another 830,000 jobs created by small and medium-sized businesses selling on Amazon. Globally, we support nearly 4 million jobs. 

- . That's why we’re spending $700 million to provide more than 100,000 Amazonians access to training programs, at their places of work, in high-demand fields such as healthcare, cloud computing, and machine learning

There is so much information to pull out of the shareholder letter that does seem to be specific to changes the company is mkaing to deal with COVID-19. Each one of the bullet points listed above could turn into it's own data science project. Each one of these areas has a lot of unanswered questions and these questions need be explored to think about what data could be used to create meaningful progress towards any one of the company goals. 

Something to think about, lads. Lots to think about. This seems like a great place to take one of those areas and really dive in.

### The data science life cycle
![alt text](http://sudeep.co/images/post_images/2018-02-09-Understanding-the-Data-Science-Lifecycle/chart.png)

Take a good look at this image and what the different phases of the cycle mean. Lets walk through them here breifly:

1. Business Understanding
Ask relevant questions and define objectives for the problem that needs to be solved. We took a deep dive into business understanding by exploring the shareholder report for 2019. This report describes what is valuable for the company and you can use this to guide your North Star goals. It is just as important to talk to your product manager or team lead to understand how your team fits in with these goals. Organizations are large and there are many moving pieces and you need to understand where you fit in. If you are working at Amazon for instance and you are working on supply chain management in Redmond WA during the time of COVID-19 everything has changed for you, but in ways that are different from the change for most other places. Redmond, WA for example is the Head Quarters for Microsoft Corportaion and many of the companies employees live in that city. Much of the investment in the citys infrastructure comes from taxes or grants from the company and its employees. Redmond has a great public education system and great public utilities available for the citys inhabitants. It would be very easy to rollout delivery robots in a city like Redmond because unpaved roads are not a problem that the city faces. The high housing cost in the city and great infrastructure creates a city with very little poverty. It could be that there are many social workers in the city who offer lower skilled people with fewer resources relocation options that help them move into more affordable places. This is just one example of an exploration of one possible team project and how that team could create solutions to target the population they are serving. Data science is specific and it is contextual. Every model is not going to work for every population or every situation. One general dataset might not serve all of the needs of every niche hypothesis you set out to test. It is ok if you don't have the data you need up front. You can take the time to find the data that you need to serve your purpose.

2. Data Mining
Gather and scrape the data necessary for the project
Once you have your project scope clearly defined you should take time to think about the data you need. Let's go back to our supply chain example because reading about Amazon and the new COVID-19 has peaked my interest.

We are going to dive into the challenges that might be present for suppliers and the delivery network. I think it is important to note whether we are thinking about the developing world or the US specifically. Amazon operates globally and the challenges that the company is facing in America are very different than the challenges the company is facing in India and Sub-Saharan Africa. In the developing world many of the emerging middle class workers have been laid off due to businesses shutting down via COVID-19 and the shelter in place mandates. These businesses might not be able to open back up ever and the services these businesses did provide might be critical for the people in those geographic areas. 

If we are focused on North America and suppliers here are a few things I might explore in further depth:
- Many American consumers are brand aware meaning they do not purchase off brand
- Most Amazon customers use Prime shipping considerations when making purchasing decisions
- Product reviews are important when making purchase decisions 
- Many users are informed shoppers, meaning they are familiar with a similar product before they purchase it and are shopping for a replacement or a new user experience
- Mom and Pop shops in America have transitioned their retail operations online and most likely through an amazon storefront - I am unsure of what the business model looks like for store owners who are selling on amazon in terms of warehousing and distrbution. We could check out the day 1 blog to understand what this process looks like to make more clear recommendatios as to how to improve this
- The suppliers who are offering products considered essential need to stock up becasue more customers are going purchase the products. There are not many manufacturing plants in the USA because the cost of labor is expensive but overseas the cost to operate a plant is lower. It is more challenging to move products around the world right now due to COVID-19, so even if the manufacturing plant was able to create more product, that does not mean that the products would get to American customers during the pandemic. Some international relations policies have prohibited or inhibited international trade during lock-down and because of the spike in the number of COVID-19 cases in the US some countries do not want to put their workers at risk to infection from American workers. There is a lot to unpack in this bullet point particularly but I think that at the heart of the supply chain conversations in question these are the issues companies like Amazon are facing. They did mention a research team working to improve some of these problems and I am sure that their research blog might detail some of them.

We could go through the same thought process for the delivery network but I will save that for another post.

Amazon created AWS as a layer of infrastructure to manage data internally across teams at Amazon so it is clear that amazon has a lot of data that you could pull from. If I owned a project like this I would spend a week reviewing all of my assumptions about the global supply chain and read as much internal documentaion as I could about what those teams are working on and where that data is stored. Unlike a start-up project where you are responsible for collecting data at a large organization you are responsible to clustering the data relevant to your project. Data engineers are your friends!

> "DATA ENGINEERS ARE YOUR FRIENDS!" - Alivia Quote #2017
Data engineers are responsible for creating pipelines and warehouses from the data the company collects and set up new collections mechanisms when data scientists or product managers explain that it is needed for some reason. Data engineers can describe to you ways to aggregate data that might be useful for you and specific to you. Searching for data in the enterprise is like searching for a needle in a haystack. I have definitely given a technical talk about this topic. [Data @ Intel]() #hotmess

3. Data Cleaning
Fix the inconsistencies within the data and handle the missing values


4. Data Exploration
Form hypothesis about your defined problem by visually analyzing the data

5. Feature Engineering
Select important features and construct more meaningful ones using the raw data you have

6. Predictive Modeling
Train machine leaning models, evaluate their performance and use them to make predictions

7. Data Visualization
Communicate the findings with key stakeholders using plots and interactive visualizations


