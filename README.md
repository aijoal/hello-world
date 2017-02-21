XRSM Read Me File

----------------------------------------------------------------------------------------------------------------------------------------
2.20.2017   V1.0.2

You need to declare all the numerical(integer or float) and catogorical(String) variables and give them names.
Market 
Na: The nation that appears in the campaign's marketing option, including countries all over the world

Investment
Ch: The marketing channel that you put investment in. Including SEM,SEO,SNS,B2B,Direct,EDM,Exibition,Sales
P: The platform within the channel. 
   SEM:Google,Bing,Yandex,Baidu,Sogou,360,Shenma. 
   SEO:Google/Bing/Yahoo/Baidu
   SNS:Facebook/Instgram/Linkedin/Twitter/Youtube/Pinterest
   B2B:Alibaba/Tradekey/Huicong/Zhongguo Zhizao
   Exibition:
La: Language used in this campaign. Including 0.Chinese 1.English 2.Spanish 3.Russian 4.Arabian 5.Other
O: Ordial Number that distinguishes. Representing the administrator
T: Type of ad form used. Including search, display, remarketing, video viewing, post boosting
S: The Strategy that a campaign choose as a method of promotion, including EPC promotions, beneficiation products promotions, and          promotion of general mining needs, promotion of general beneficiation needs, brand awareness promotions, case sharing promotions, and    other policy, market info promotions.(Or categorized simply as EPC,Products,Brand Awareness)
G: Name of Ad Group, represent the minimum budget unit.
CoP: Cost of Promotion, unified to CNY

Conversion
D: Device of Mobile or PC
Pt: Platform Traffic. Including Search engine's impression, Social network's impression, B2B's impression
Pcl: Platform clicks. Including Search engine's clicks, Social network's clicks, likes, replies. B2B platform's clicks
Pd: Platform dialogues
Pm: Platform messages
Pe: Platform emails
Pca: Platform calls
Na: Nation record on web
Wt: Web Traffic of page loads on Business links
Wd: Web dialogues
Wm: Web messages
We: Web emails
Wca: Web calls

Return
Na: Nation where project locates
M: Material that need to be processed, including different segmentation methods
Ne: Service need
Ca: Capacity Range
Le: Level of Overall Rating
NoE: Number of Enquiry

一共15个分类数据，14个数量数据。按顺序这些数据将在推广平台，推广后台（第三方工具），商务通，和富通中产生。下面分部门描述如何得到各部分的数据
----------------------------------------------------------------------------------------------------------------------------------------
2.17.2017   V1.0.1

Marketing Life Cycle: Market-Investment-(Conversion)-Return

1. Market: Nation-Segmentation Strategy matrix. How to segment the market needs and "make sense" to decision-making?
The distribution of customer needs can be further segmented, depending on either raising brand & industry awareness or promoting products.

2. Investment: Cost of Promotion, CoP. How to retrieve and aggregate Market & Return data within each campaign's minimum output unit?
Channel includes Online(SEM,SEO,SNS,B2B,EDM,Direct Click Through) Offline(Exibition,Sale)
Campaign Feature:  Ch=Channel, P=Platform, L=Language, O=Ordinal, T=Type， G=Group 
Data Source Example:  SEM's      Google      English     #1         Search   gold mining    account.

3. Conversion: Monitor loop of Platform's traffic & engagement to Web's traffic & Engagement on different device in different nations
PT,PE,WT,WE Metrics vary depending on Channel, Platform, and Strategy.

4. Return: Nation-Material-Need-Capacity-Level enquiry number NoE. (Further Modeling)


------------------Market---------------------|-------Investment------|------------------Conversion--------------------|-----Return-----|
Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Platform,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Mining Equipment/Machinery            Ch,P,La,O,T,G  77,000      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  53
Na      Mineral/Ore Processing/Beneficiation  Ch,P,La,O,T,G  56,700      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  33
Na      Brand/Company/Consultancy             Ch,P,La,O,T,G  23,100      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  20
Na      Other Info Policy/Resource/Ore deal   Ch,P,La,O,T,G  14,700      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  20
Na      ---------------General--------------- Ch,P,La,O,T,G 171,500      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le 126
                               
Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Platform,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Gold                                  Ch,P,La,O,T,G 201,600      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le 218
Na      Copper                                Ch,P,La,O,T,G  40,600      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  41
Na      Iron                                  Ch,P,La,O,T,G  38,500      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  21 
Na      Other EPC                             Ch,P,La,O,T,G  71,400      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  50 
Na      -----------------EPC----------------- Ch,P,La,O,T,G 352,100      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le 330

Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Campaign,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Ball mill                             Ch,P,La,O,T,G  60,900      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  55
Na      Gravity/Magnetic Separator            Ch,P,La,O,T,G  28,700      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  34
Na      Dewatering Machine/Filter Press       Ch,P,La,O,T,G  21,700      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  27
Na      Screening Machine                     Ch,P,La,O,T,G   9,800      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  19
Na      Flotation Machine                     Ch,P,La,O,T,G   9,100      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  15
Na      Other Products                        Ch,P,La,O,T,G  44,800      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le  25
Na      ---------------Products-------------- Ch,P,La,O,T,G 175,700      Na,D        PT     PE      WT       WE       Na,M,Ne,Ca,Le 175

Note: the node of characteristic is ad Group, matched by URL in the later session, some need manual labor which are also routine work.



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
