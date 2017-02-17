XRSM Read Me File
----------------------------------------------------------------------------------------------------------------------------------------
2.17.2017   V1.0.1

Marketing Life Cycle: Market-Investment-(Conversion)-Return

1. Market: Nation-Need matrix. How to segment the market needs and "make sense" to decision-making?
The distribution of customer needs can be further segmented, depending on either raising brand & industry awareness or promoting products

2. Investment: Campaign with Cost. How to retrieve and aggregate Market & Return data within each campaign's minimum output unit?
Campaign includes Online(SEM,SEO,SNS,B2B,EDM,Direct Click Through) Offline(Exibition,Sale)
Campaign Feature:  C=Channel, P=Platform, L=Language, O=Ordinal, S=Strategy 
Makeup Data Source:  SEM's      Google      English     #1         Search   account.

3. Conversion: Monitor loop of Campaign's traffic & engagement to Web's traffic & Engagement. 
CT,CE,WT,WE Metrics vary depending on Channel, Platform, and Strategy.

4. Return: Nation-Service enquiry matrix.


------------------Market---------------------|-----------Investment-------------|--------------Conversion--------------|-----Return----|
Nation  Customer Need Segmentation            Campaign     Investment  Currency  (Campaign,Web)'~(Traffic, Engagement)    Enquiry
TGT     Mining Equipment/Machinery            C,P,L,O,S     77,000        CNY       CT      CE      WT       WE            53
TGT     Mineral/Ore Processing/Beneficiation  C,P,L,O,S     56,700        CNY       CT      CE      WT       WE            33
TGT     Brand/Designer/Consultancy            C,P,L,O,S     23,100        CNY       CT      CE      WT       WE            20
TGT     Other Info Policy/Resource/Ore deal   C,P,L,O,S     14,700        CNY       CT      CE      WT       WE            20
TGT     ---------------General--------------- C,P,L,O,S    171,500        CNY       CT      CE      WT       WE           126

Nation  Customer Need Segmentation            Campaign     Investment  Currency  (Campaign,Web)'~(Traffic, Engagement)    Enquiry
TGT     Gold                                  C,P,L,O,S    201,600        CNY       CT      CE      WT       WE           218     
TGT     Copper                                C,P,L,O,S     40,600        CNY       CT      CE      WT       WE            41      
TGT     Iron                                  C,P,L,O,S     38,500        CNY       CT      CE      WT       WE            21      
TGT     Other EPC                             C,P,L,O,S     71,400        CNY       CT      CE      WT       WE            50      
TGT     -----------------EPC----------------- C,P,L,O,S    352,100        CNY       CT      CE      WT       WE           330

Nation  Customer Need Segmentation            Campaign     Investment  Currency  (Campaign,Web)'~(Traffic, Engagement)    Enquiry
TGT     Ball mill                             C,P,L,O,S     60,900        CNY       CT      CE      WT       WE            55
TGT     Gravity/Magnetic Separator            C,P,L,O,S     28,700        CNY       CT      CE      WT       WE            34
TGT     Dewatering Machine/Filter Press       C,P,L,O,S     21,700        CNY       CT      CE      WT       WE            27
TGT     Screening Machine                     C,P,L,O,S      9,800        CNY       CT      CE      WT       WE            19
TGT     Flotation Machine                     C,P,L,O,S      9,100        CNY       CT      CE      WT       WE            15
TGT     Other Products                        C,P,L,O,S     44,800        CNY       CT      CE      WT       WE            25
TGT     ---------------Products-------------- C,P,L,O,S    175,700        CNY       CT      CE      WT       WE           175









----------------------------------------------------------------------------------------------------------------------------------------
2.16.2017   V1.0.0

This is the first edition of Xinhai's ROI System of Marketing(XRSM).

I'm Yanning Jia, together with Yan Liang we are currently the main developers of this system, and our work is under the fully guidance of Xuxu and Dingqiang. XRSM is proposed at the end of 2016 as a strategic move of Xinhai's operation research, which at the same time an initialling step to fight into the toB marketing service industry. The design of this system is dedicated to quantify the life circle of Xinhai's marketing operation and make the most out of it. Upon building the infrastructure, XRSM aims to normalize(for the warefare of data storage & improve the work efficiency in the long run) and integrate(match and organize) data from Xinhai's marketing and sales departments, then visualize all the data in a user-friendly interface. While for decesion making, there'll be built-in functions including ROI calculation, traffic trends, cross comparisons ( other key metrics)to support general marketing decisions. If time allows, we'll work to import automatic data, mine further insights and export automatic suggestions. The expected time to mature this system is 100 days.

Yan Liang first joined this project and has done a ton of work already. We've now clarified most of the data structures needed for the field inputs, which consists of market segmentation data(geographic level and operation level****, marketing channel data(Online**** from SEM,SEO,SNS,B2B,EDM,Direct Click Through, including investment and traffic. Offline from Exibition and Sales', including investment and engagement), web analytics data(another measurement of web traffic, from third-party analytic tools and Business Links, including customer identity features and browsing behavior), convertion data(R&R****, including conversion channel, business need), and sales data(connected via the unique customer characteristic number). We also understand the basic rules and operation relationships within each marketing channel.

As for the next step, we need to make some choices and answer these questions:

****How to segment Xinhai's market?What is Xinhai's MVPs and NVPs? Nation\*Product
****What is the minimum manual labors unit? How to group them and normalize the required settings?
****What is the minimum matching unit or units in the system? 

Clarify the needs of Market segmentation & measurement, Customer research & Churn analysis, Department-based normalizing? How to manage their priority? 
Which possible types of conversion are there within each marketing channel, how do we discriminate them?
Which fields need manually input and how much time do they take up, are they originally part of stuff's daily work?
How to visualize the data, how many manifolds do we need? 
