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
> Q: ** If this is a shareholder report from 2019, why are the COVID-19 updates in this report? ** I realize the pandemic has changed everything, but shouldn't all of the updates for 2020 be in the 2020 shareholder letter that comes out in 2021? If something changed shouldn't they create a new type of report that would take into account these changes? It would seem like a good idea to have a mandatory inevstor meeting to review all of the new changes to the supply chain because of COVID-19. Given these changes will likely affect the supply chain for the forseable future, wouldn't there need to be new processes put into place to start to detail these important company changes to shareholders?

These are just some of the questions I have because if there were a model in production analyzing shareholder meetings by year and the 2019 year in review report included major company shifts that occured in 2020, this would overshadow the company strategy and growth that happened in 2019, which is also important to think about when recommending a stratefy for 2020 or even 2021. COVID changes everything I guess even Models. 

- Demand for essential products has spiked
- There was little warning of the spike so there was not enough time to plan

![alt text](http://sudeep.co/images/post_images/2018-02-09-Understanding-the-Data-Science-Lifecycle/chart.png)

