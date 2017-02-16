XRSM Read Me File

------------------------------------------------------------------------------------------------------------------------------------------
2.16.2017   V1.0.0

This is the first edition of Xinhai's ROI System of Marketing(XRSM).

I'm Yanning Jia, together with Yan Liang we are currently the main developers of this system, and our work is under the fully guidance of Xuxu and Dingqiang. XRSM is proposed at the end of 2016 as a strategic move of Xinhai's operation research, which at the same time an initialling step to fight into the toB marketing service industry. The design of this system is dedicated to quantify the life circle of Xinhai's marketing operation and make the most out of it. Upon building the infrastructure, XRSM aims to normalize(for the warefare of data storage & improve the work efficiency in the long run) and integrate(match**** and organize) data from Xinhai's marketing and sales departments, then visualize all the data in a user-friendly interface. While for decesion making, there'll be built-in functions including ROI calculation, traffic trends, cross comparisons ( other key metrics)to support general marketing decisions. If time allows, we'll work on importing automatic data, mining further insights and exporting automatic suggestions. We expect 4 months to mature this system.

Yan Liang first joined this project and has done a ton of work already. We've now clarified most of the data structures needed for the field inputs, which consists of market segmentation data(geographic level and operation level****, marketing channel data(Online**** from SEM,SEO,SNS,B2B,EDM,Direct Click Through, including investment and traffic. Offline from Exibition and Sales', including investment and engagement), web analytics data(From third-party analytic tools and Business Links, including customer identity features and browsing behavior), convertion data(R&R****, including conversion channel, business need), and sales data(connected via the unique customer characteristic number). We also understand the basic rules and operation relationships within each marketing channel.

As for the next step, we need to make some choices and answer some questions:

****What is the minimium matching unit in the system?
****What is Xinhai's MVPs and Non-MVPs?(Supported by history SEM traffic stats, xlsx)
****Which variables do we need to extract in each marketing channel?
Clarify the needs of Market segmentation & measurement, Customer research & Churn analysis, Department-based normalizing? How to manage their priority? 
Which possible types of conversion are there within each marketing channel, how do we discriminate them?
Which fields need manually input and how much time do they take up, are they originally part of stuff's daily work?
How to visualize the data, how many manifolds do we need? 
