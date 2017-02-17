XRSM Read Me File
----------------------------------------------------------------------------------------------------------------------------------------
2.17.2017   V1.0.1

Marketing Life Cycle: Market-Investment-(Conversion)-Return

1. Market: Nation-Segmentation Strategy matrix. How to segment the market needs and "make sense" to decision-making?
The distribution of customer needs can be further segmented, depending on either raising brand & industry awareness or promoting products.

2. Investment: Campaign with Cost. How to retrieve and aggregate Market & Return data within each campaign's minimum output unit?
Channel includes Online(SEM,SEO,SNS,B2B,EDM,Direct Click Through) Offline(Exibition,Sale)
Campaign Feature:  Ch=Channel, P=Platform, L=Language, O=Ordinal, T=Type， G=Group 
Data Source Example:  SEM's      Google      English     #1         Search   account.

3. Conversion: Monitor loop of Platform's traffic & engagement to Web's traffic & Engagement on different device in different nations
PT,PE,WT,WE Metrics vary depending on Channel, Platform, and Strategy.

4. Return: Nation-Material-Need-Capacity enquiry number


------------------Market---------------------|-------Investment------|------------------Conversion--------------------|-----Return-----|
Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Platform,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Mining Equipment/Machinery            Ch,P,L,O,T,G   77,000      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   53
Na      Mineral/Ore Processing/Beneficiation  Ch,P,L,O,T,G   56,700      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   33
Na      Brand/Company/Consultancy             Ch,P,L,O,T,G   23,100      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   20
Na      Other Info Policy/Resource/Ore deal   Ch,P,L,O,T,G   14,700      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   20
Na      ---------------General--------------- Ch,P,L,O,T,G  171,500      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca  126
                               
Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Campaign,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Gold                                  Ch,P,L,O,T,G  201,600      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca  218
Na      Copper                                Ch,P,L,O,T,G   40,600      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   41
Na      Iron                                  Ch,P,L,O,T,G   38,500      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   21 
Na      Other EPC                             Ch,P,L,O,T,G   71,400      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   50 
Na      -----------------EPC----------------- Ch,P,L,O,T,G  352,100      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca  330

Nation  Segmentation Strategy                 Campaign     Investment  Feature   (Campaign,Web)'~(Traffic, Engagement)    Enquiry(Smplf)
Na      Ball mill                             Ch,P,L,O,T,G   60,900      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   55
Na      Gravity/Magnetic Separator            Ch,P,L,O,T,G   28,700      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   34
Na      Dewatering Machine/Filter Press       Ch,P,L,O,T,G   21,700      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   27
Na      Screening Machine                     Ch,P,L,O,T,G    9,800      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   19
Na      Flotation Machine                     Ch,P,L,O,T,G    9,100      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   15
Na      Other Products                        Ch,P,L,O,T,G   44,800      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca   25
Na      ---------------Products-------------- Ch,P,L,O,T,G  175,700      Na,D        PT     PE      WT       WE         Na,M,Ne,Ca  175

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
