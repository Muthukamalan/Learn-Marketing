# Intro to Marketing

History of Marketing has always been recognized that this optimization problem can be approached in a scientific way and that rigorous mathematical methods can be applied to a wide range of marketing applications


traditional challenges related to 
    incompleteness of data, 
    complexity of real life marketing settings, 
    inflexibility of business processes, and 
    software limitations
    
With digital world, we experiences, personalized experiences for millions and we able to track one or other form of it.
    Targeted sales promotions,
    dynamic pricing in brick-and-mortar and 
    online stores, 
    e-Commerce search and 
    recommendation services, 
    online advertising
    etc..
  
  with comes with it's own challenges
  
the problem of marketing automation can be studied from different perspectives, including 
    economics, 
    management, 
    statistics, and 
    engineering
    all are implemented in software to achieve the business objectives
    
    
    
    
One of the traditional definitions of marketing describes it as the activity of
    defining products and 
    services offered by a company and 
    communicating them to existing or potential customers 
**4P**

**Product**   – analysis of marketing opportunities, planning of product lines and product features, assortment planning.
**Promotion** – all methods of communication between the company and its customers: advertisements, recommendations, customer care, and others.
**Price**     – pricing strategies, including posted prices, price discounts, and price changes over time.
**Place**     – historically, this refers to the process of making a product or service available to the end user through various distribution channels. More recent interpretations emphasize the role of product discovery and convenience to buy, with the argument that distribution is becoming less relevant with the rise of digitalmarketing channels

This categorization is known as __marketing mix__ and each compenent studied from different perpectives.



Algorithmic marketing can be better understood by 2 strategy: **strategy** and **process**


For example, 
**Retailer** 
    - It has to define its target market, customer services, and product lines as parts of the business strategy. 
    - The process is an implementation of the strategy that focuses on tactical decisions that support continuous functioning of the company.

the scope of neither strategy nor tactical processes can be rigorously defined. but strategy more focused on 
    - exploration
    - analysis
    - planning involving human judgement
process side more focused on 
    - execution
    - micro decisio
    - automation


# Algorithmic Marketing
It mainly concerns the process that found in 4 area of MMX and automate process using data driven and automating process
e.g) 
    - acquistion of new customers
    - revenue maximization
    - advertisement campaign
    - price adjustment

![Conceptual View]('./pics/conceptual_view_algorithmic_marketing_ecosystem.png')


## Business Cases
Following TWO are generic examples

`Services and Exchanges`: Online Advertising
Terminology:
    - CPM  ( Cost-per-Thousand Impressions Model )
    - PPC  ( per pay click )
    - CTR  ( Click Through Rate )
       
          revenue = bid_price * CTR
    - RTB  ( Real Time Bidding ) be achievable by ability to collect data the behaviour of internet users by DMP and DSP
    - DMP  ( Advertisers Data Management Platforms )
    - DSP  ( Demand Side Platforms )

    Success of RTB leads favourable to independent party like __Advertsing services__ and __Data Service__

    - Advertising services advertiser to run advert. campaigns using publisher resources.
    - Data Services that collect info about consumers.

    Now a days it's going far beyond advertising leads to overwhelning complexity of data and operational decisions and programmatic methods are probably the only way to tackle it.

`Revenue Management`    : Airline

    Not online advertising is the only way

Scenario:
    
PeopleExpress, which started in 1981 and offered fares about 70% lower than the major airlines. this threads to Established Airlines because it's open up and enlarge small business.  American Airlines found solution and make their unsold tickets sold at low price to compete. Optimal allocation acheived by using Dynamic Optimization call (DINAMO)

they won with people_express and profit increase upto 47.8%

Terminology:
    Revenue Management consider as counterpart of
        - Supply-chain management
        - Demand chain management

![RevenueManagement_Counterpart]('./pics/counterpart_revenue_management.png')







`Marketing Science`:

    earlier it was mainly focused on the descriptive analysis of pro-
duction and distribution processes

    In 1960s, the idea that marketing decisions could be supported by mathematical modeling and
optimization methods
    
    this is how the concept of the marketing mix appeared in 1960

    more modern frameworks developed to collect data and implement data anlaysis and optimization algo using advanced probabilistic and optimzation technique

`Programmatic Services` 

    4 factors can be controlled by a company to influence consumer purhase decisions:
        - product
        - promotion
        - price
        - place
    this is very board categorization

    so far we seen one or more functional services that implement in certain business process like price or promotion management

We define SIX major business model of a **functional services** that are relevant for wide range of B2C verticals:

         - promotion
         - advertisments
         - search
         - recommendations
         - pricing
         - assortment

`objective`:  review these relationships and some common design guideline


# Relation btwn Framework and Business
The relationships between the six services we have defined, as well as their connections to the marketing mix, can be established as follows:

1. The primary purpose of promotion and advertisement services is to match customers with offerings and convey the right message to them.

`sarcasm`: e.g) apple means privacy at same line care about Linux

2. The search and recommendation services solve the problem of finding the right products for a given customer, which naturally complements the previous service group

`sarcasm`: chatgpt corrupt Google when it's pollute with sponsers

3. The goal of pricing and assortment services is to determine and optimize the set of offerings and their properties, including price

`sarcasm`:

![Framework_Relationship]('./pics/programatic serivce framework.png')



# Design Framework

![Design]('./pics/framework of programmatic services.png')