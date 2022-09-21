---
title: 'Personalisation: Price Discrimination'
author: Ethics Team, Alan Turing Institute
tags: 'case study' 
---

# Personalisation: Price Discrimination

## 1. Summary


In this case study, we define and discuss the topic of personalisation with respect to algorithmic techniques that engage in price discrimination. 

We will consider a online travel booking company which decides to use an AI system to personalise prices for their customers. That is, it will show different prices based on information it infers from the customer's browsing history, location, past behaviour, among other variables. 

[We start out by...and provide...] We raise the topic of __ and consider __.

## 2. Case Study Details

### Case Study Description
An online travel booking platform decides to implement a flight aggregator that shows customers different prices for the same flight depending on information inferred from their browsing habits and digital fingerprints (e.g. location from IP address, household income based on data extracted from broswer cookies). 

The platform groups users into different buckets, which it uses to estimate their 'willingness to pay'—an inferred category. Customers that have visited sites associated with luxury brands, or who are accessing the platform from more affluent postcodes, are charged a premium compared to other users.

Customers are, typically, not aware or informed that this is happening, but the platform does have a permissive privacy policy in place that can be accessed by users. Furthermore, because the prices of the goods change frequently, consumers do not have a straightforward way of comparing prices among different customers.[^airline] The online retailer is engaging in **price discrimination**, in particular what is known as targeted pricing.

[^airline]: Travel sites have been known to do a version of this. They charge travelers from some countries a premium when they book flights or hotel rooms from specific countries (Rose & Rahman, 2015). Additionally, the prices for flights and hotel rooms fluctuate with relative high frequency, which makes it hard for individual connsumers to keep track of them and compare.


:::info
**What is price discrimination?**

'Price discrimination' refers to different ways of offering "essentially the same product for different prices to different people" (Miller, 2015). Our example focuses on 'targeted pricing' which refers to discrimination in terms of individuals or groups. In particular, targeted pricing refers to charging different prices to consumers based on their willingness to pay for the good or service (FCA, 2018). Another kind of price discrimination is known as 'dynamic pricing', and it refers to prices that are changed frequently over time.

Although they are distinct practices, dynamic pricing can aid taregted pricing insofar as it makes it harder for consumers to compare prices amongst themselves and therefore to realise they are being subjected to targeted pricing.

Price discrimination is a common practice. Some classic examples are student discounts, loyalty discounts, new customer discounts, or discounts for buying in large quantities.

Economists traditionally distinguish between three kinds of price discrimination, depending on how the consumers are being sorted (see Townley et al., 2017).  

1. 1st degree price discrimination: The firm has perfect information about each individual consumers' willingness to pay. This means the firm is able to extract all of the consumer welfare from each individual consumer in the form of a higher price. In practice, this form of price discrimination is almost impossible to actually perform.
2. 2nd degree price discrimination: The firm has no ex ante information about an individual consumers' willingness to pay. However, individual consumers reveal partial information about themselves through their purchasing decisions which is correlated with their willingness to pay. An example would be discounts for buying in large quantities. 
3. 3rd degree price discrimination: The firm has imperfect information about an individuals’ willingness to pay, but can identify different types of consumers. Therefore the firm charges prices to different individual customers (or groups of customers) based on their observed characteristics or behaviour, e.g. discounts to senior citizens, or lower prices to new customers.
:::

In this case study, we will focus on specific forms of targeted prices enhanced by using personalisation in AI. This is also known as algorithmic consumer price discrimination (ACPD) (Townley et al., 2017).

### Category Definition
:::success


In a general sense, personalisation is the targeting or adapting of some behaviour or outcome to a specific person. In the context of AI, personalisation occurs when an algorithm learns about an individual's profile in order to tailor the services or products offered to that person. 

A range of AI techniques can be employed in personalisation, including learning algorithms that create and refine a model of a specific user over time based on the user's behaviour and interaction with the algorithmic system.

Recommendation systems are a well-known application of personalisation. For instance, an algorithm can provide recommendations on what content to watch or listen to based on a consumer's previous browsing or purchase patterns.
:::

### Background


### Key Information
- SIC Classification
    - Section: G
    - Class: All codes which involve retail sales. (list?)
- Stakeholders and Other Affected Individuals:
	- Online shoppers 
	- Retailers
	- System Developer
- Data Types:
    - Digital Fingerptints (e.g. IP Address)
    - Browser Cookies
- Possible Algorithmic Techniques Employed:
    - Unsupervised Learning (e.g. clustering) to segment consumers during market research
    -  Multi-class classification to predict which group a specific user is most closely aligned to
    -  Reinforcement learning to identify and optimise personalised 'willingness to pay'
    
## 3. Regulatory Considerations
    - Specific Issues
    - Existing Regulation or Legislation
    - Gaps in Current Framework
    - Socioeconomic value chains
    - Ethical considerations




<!-- ## Short Summary -->

  
<!-- [to be written] -->

 
<!-- ## Overview -->



### Algorithmic Consumer Price Discrimination (ACPD)

Price discrimination is not a new practice. However, the technological capacities provided by big data and AI allow firms to engage in much more precisely targeted forms of price discrimination that had not been previously possible.

This is done by (1) surveilling and tracking individuals’ online behaviour, (2) using algorthims to learn about individuals’ willingness to pay via the information collected about them, and (3) then using the insights gained to personalise the choice environments of the customers (Burr, Cristianini, Ladyman, 2018). For example, offering a user a specific price or discount catered to their 'willingness to pay' (Townley et al., 2017).

#### ACPD in Practice

Let us now return to our example of the online retailer. They are engaging in ACPD of the third degree, as, as they are sorting consumers into different groups depending on their location and inferred characteristics.[^selfsorting]

[^selfsorting]: This is not second degree price discrimination as for that to be the case individuals need to *self sort* into categories. In these cases, it is the online retailer who decides, (without consumer knowledge), which group they belong to, and therefore, the price they will be charged.

The rationale behind the practice is to charge a higher price to those customers who have a higher **willingness to pay**. However, people can have a high or low willingness to pay for different reasons. 

With location-based discrimination, people who live in more affluent neighbourhoods are charged a higher price. Here, the idea is that those people have a higher willingness to pay for a product because they have a *higher income*. It is debatable whether it is fair to charge someone more for a product simply because they earn more money. For instance, from one perspective, this particular instance of discrimination does not harm those who are at a *disadvantage*.

However, higher willingness to pay can arise from other sources, such as *higher need*. Suppose now that the online retailer sells over-the-counter migraine medicine. People who suffer from migraines need the medicine as they are regularly impaired by these headaches, whereas people who do not usually get migraines might buy them on an ad hoc basis. 

The online reatailer can infer from past consumer shopping behaviour that a customer frequently suffers from migraines or not, and therefore charges more to those who have a higher willingness to pay—albeit one grounded in need.

Many people feel uncomfortable at the idea of charging more money to those in need (FIND CITATION OF EXAMPLES). It can be seen as an exploitation of the consumer (LOOK UP CITATION).

[...]

<!-- This example highlights one of the ethical issues that arise in cases of ACPD; namely, the ethical status of the underlying rationale behind the discrimination. However, there are many other ethical considerations which are relevant when analysing ACPD. These will be dealt with in the benefits and harms section.  -->

<!-- ### EXAMPLES -->
<!-- 2000 - Amazon had sold identical DVDs at different posted prices to different shoppers on its website (Streitfeld, 2000).  -->

<!-- Footnote 34 and footnote 36 of Miller, 2015. -->



 
## Benefits and Harms
    - Human Rights and Democracy
    - Ethical Values and Principles
    
Price discrimination is used by firms in the form of loyalty discounts, bulk discounts, and student discounts, among others. However, personalisation using machine learning allows for a granularity in targeted pricing that was not possible previously. With this is mind, we can ask what are the potential benefits and harms of ACPD?

Some questions that can help evaluate whether the effects of price discrimination are beneficial or harmful are: 

a) who is benefiting from the practice? 
b) are consumers in particular benefiting?, and if they are, 
c) are those benefits distributed *fairly* among consumers? 

Traditionally, first two questions are answered in economic terms; by trying to estimate whether there is an increase in overall welfare and/or in consumer welfare (CMA, XXXX).
Total welfare is the sum of total consumer welfare and total producer welfare.

### Economic considerations

It is usually assumed that producer welfare increases after an instance of price discrimination because it is assumed that a producer engages in price discrimination *because* it is to their advantage (that it, it will increase their total welfare).[^producers] So if firms are going to benefit from engaging in ACPD, what happens to consumers?

[^producers]: In strict terms there can be prisoner-dilemma type situations, where all firms would be better-off charging uniform prices, but collectively end up discriminating nonetheless (CITE). For our purposes, we will ignore these cases and assume a firm only discriminates if it is to their advantage.

Clearly some of them will experience a decline in their welfare via an increase in price (in comparison with uniform pricing). However, some of them may be able to access a good or service that was prohibitedly expensive to them under uniform pricing. They can become consumers via targeted pricing opening up a new sector of the market. Clearly, these consumers are benefiting from targeted pricing.

When the losses incurred by the consumers who are charged a higher price because of uniform pricing are offset by the gains in the aggregate welfare of new consumers who were previously excluded from the market, then it is said that price discrimination increased overall consumer welfare and thus benefited consumers. Note that the latter is only possible when under uniform pricing, people with lower willingness to pay are excluded from the market.

Whether this will be the case or not depends largely on the proprotion of 'high-willingness-to-pay consumers' (H) versus 'low-willingness-to-pay consumers' (L), as well as how elastic or inelastic their demands are. For example, if group H is very small and is very inelastic in its demand, charging a uniform price might exclude the larger and very elastic group L, and therefore the firm might benefit from charging different prices to H and L, allowing L to actually access the good. However, if H is relatively similar to L in size, and they are not that disimilar in elasticities, then maybe the only difference between uniform pricing and targeted pricing will be in terms of how much consumer welfare the firm can extract from its customers. 

This is why the overall economic benefit of price discrimination is not obvious, and a case-by-case approach must be used when evaluating overall as well as consumer welfare to determine whether the values and welafre of producers and consumers are aligned (Burr, Cristianini, Ladyman, 2018).

Nevertheless, there are some problems with this approach. Firstly it does not consider other potentially relevant effects of price discrimination such as whether and how it distorts market competition. 

But secondly, and crucially, because welfare is an aggregate measure it is ill-equiped to assess any questions of fairness (e.g. distributional impact on equitable outcomes) that may arise when price discrimination is used (XXXX). In other words, when measuring increases or decreases in consumer welfare, the precise distribution of said welfare is completely irrelevant.


In summary, in economic terms, the following variables need to be considered (FCA, XXXX):
- **Accessibility**: does price discrimination increase overall consumer welfare by making a good or service available to more customers than it would otherwise be? 
    - *This is the main advantage price discrimination can bring for consumers: allowing some consumers who would have been excluded from the market under uniform pricing to access the good or service.*
- **Prices**: does price discrimination increase or decrease average prices?
    - *Depending on how many consumers pay higher or lower prices, the average price may increase or decrease.*
- **Competition**: how does price discrimination distort competition (e.g. by creating barriers of entry or raising search costs)? 
    - *Depending on the structure of the market, price discrimination may increase or decrease competition (CITE).*

When price discrimination increases overall consumer welfare (e.g. because it decreases average prices paid), allows new customers to enter the market, and/or increases competition, economic theory would evaluate it as positive. However, because total consumer welfare is an aggregate quantity, it gives us no information on how that welfare is distributed. To evaluate whether the distribution of welfare among consumers is acceptable, we need consider additional factors related to fairness and equality.

<!-- How much detail do we want to go into in this section? -->

### Considerations of fairness

There are different ways to think about fairness which sometimes overlap and which are relevant to assess the benefits and harms of price discrimination (Townley et al., 2017).

- Perceived fairness of pricing practices;
- Fair dealing between online retailers and consumers;
- Fairness as a requirement of distributive (or collecitve) justice.

There are many reasons why 

<!-- #### Price discrimination as unfair dealing -->
<!-- Is price discrimination deceptive or unfair? The question does not have a straightforward answer as it depends on social norms that determine equality which are not fixed.  -->


<!-- - Importance of consumers being aware that PD is happening + understands how it works. This goes beyond transparency, quality of disclosure is crucial (OECD- DAF). -->
<!-- - Allows for discriminating based on protected characteristics. -->

    
## Policy and Regulation Considerations
    - Applicable legislation: 
    - Impacted value chains (upstream and downstream)

### Applicable Regulatory Framework

Personalised pricing can have negative or positive effects. There is no direct prohibition against personalised pricing. Instead, its effects will be assessed on a case-by-case basis. As such, there exists multiple pieces of legislation in the UK that are applicable to personalised pricing.

#### Competition Act

First, the Competition and Markets Authority (CMA) will have jurisdiction where personalised pricing contravenes the Competition Act or consumer protection legislation[^CPRs], which protects consumers from commercial practices that are considered unfair, misleading actions, misleading omissions and commercial practices which are aggressive. The CMA has defined personalised pricing as “[...]the use by businesses of information that is observed, volunteered, inferred or collected about individuals’ conduct or characteristics, to set different prices to different consumers (whether an individual or group basis), based on how price sensitive the business perceives them to be.”[^DAF]

[^CPRs]: Consumer Protection from Unfair Trading Regulations 2008 (CPRs), Part 2, Article 6.

[^DAF]: https://one.oecd.org/document/DAF/COMP/WD(2018)127/en/pdf.

From the CMA’s perspective, personalised pricing is more likely to generate concerns where there is *limited competition*, or where consumers are unaware of, do not understand, and/or cannot avoid personalisation. This is a specific concern in the context of algorithmic systems, which are often deployed as part of back-end infrastructure for online platforms, and, therefore, users are often unaware that they are interacting with intellgient sofwtare agents (Burr, Cristianini, Ladyman, 2018). 

In addition, where personalisation is based on particular characteristics of the individual consumer that may be associated with vulnerability, it is more likely to raise concerns. The CMA has noted that online markets increase the scope for personalisation and increases the information asymmetry between consumers and providers.

According to the CMA, where personalisation takes place, it is less likely to be harmful where consumers know it is happening, understand how it works and can exercise effective choice—though it notes that transparency alone will not necessarily adequately address the risk of consumer harm and the quality of disclosure is vital.

With respect to the Competition Act, personalised pricing can potentially distort competition and subsequently breach the Chapter II prohibition of the Competition Act 1998 in circumstances where online traders abuse dominant positions by using algorithms determining the consumer’s maximum willingness to pay. Examples of possible infractions include charging excessively high prices to those customers unable to switch or using personalised pricing to exclude rivals. For instance, by using high prices to ‘trap’ customers and subsidise very low prices to customers more susceptible to competition from new rivals, thus inhibiting new market entry. 

The CMA has noted that:[^DAF] [Replace footnotes with link in text?]

[^DAF]: Ibid (page cite).

> The overall effect on competition and consumers of a given case of personalised pricing is ambiguous, and will depend not only on how those four effects balance out against each other, but also on a range of case specific factors, including, for example, (i) the intensity of competition in the market, (ii) the complexity of price personalisation (and thus how likely consumers are to understand it) and (iii) the cost to the firm of personalising offers.

Because it is not possible to state in advance whether personalised pricing will have positive or negative effects, the CMA must undertake an evidence-based assessment of the market in question.

#### Consumer Protection from Unfair Trading Regulations

With respect to the Consumer Protection from Unfair Trading Regulations, personalised pricing may be ruled unlawful if it is misleading, or if the underlying data about the consumer was obtained unlawfully. Examples of possible infractions include obtaining consumer data without their valid, freely given, specific, informed and active consent, contrary to data protection laws.

Second, personalised pricing may be caught by other pieces of legislation under specific circumstances. For instance, equalities legislation prohibits discrimination based on protected characteristics such as age, disability, pregnancy, gender or sexuality, marital status, race, or religion. Data protection legislation requires that consumers provide informed consent to certain forms of data gathering or when they are subjected to automated decision-making. Local legislation may restrict online retailers from offering different terms for providing the same service to consumers. And advertising and marketing law regulate online behavioural advertising, ie advertising based on a user’s data. 

#### Financial Conduct
 
Third, the Financial Conduct Authority (FCA) will have oversight over personalised pricing in financial markets. The FCA has noted that personalised pricing is not in itself an unfair practice, and that a determination would have to be made on a market-by-market basis.[^2]  The Figure below illustrates the approach that will usually be taken by the FCA in personalised pricing cases to determine if there is a strong case for intervening.

![](https://i.imgur.com/GH6noCB.png)



The FCA sets out a clear framework for identifying, assessing and scaling economic harm. With respect to personalised pricing, these economic considerations will be guided by such questions as:

* Accessibility: Are more consumers able to access a good quality product due to price discrimination?
* Prices: Does price discrimination increase or decrease prices on average?
* Competition: Does price discrimination distort competition (for example by creating barriers to entry) or have other efficiency implications (for search costs for consumers too high)?


#### References

Burr, Cristiani, and Ladyman, 2018
Miller, 2015.
FCA, 2018
Townley et al. 2017.
OCED - DAF
Rose & Rahman, 2015.
Streifeld, 2000 Washington Post