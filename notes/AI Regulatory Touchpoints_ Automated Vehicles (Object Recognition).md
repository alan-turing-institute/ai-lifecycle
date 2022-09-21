# AI Regulatory Touchpoints: Automated Vehicles (Object Recognition)
###### tags: `regulatory touchpoint`

## AI Project Lifecycle: AVs

Specific regulatory touchpoints for automated vehicles (AVs)

A company is building a vehicle with self-driving capabilities.

[The Law Commission of England and Wales & the Scottish Law Commission have set out the applicable regulatory framework](https://s3-eu-west-2.amazonaws.com/lawcom-prod-storage-11jsxou24uy7q/uploads/2022/01/Automated-vehicles-joint-report-cvr-03-02-22.pdf):

> "AV regulation involves making decisions about both the design of vehicles and how they discharge driver responsibilities. It must therefore fit within both legal systems...decisions affecting driver responsibilities should be taken at domestic level, in a way which reflects Britain’s high level of road safety, laws on driving and unique road environment."

### 1. Project Planning 

**Licensing requirements (p 69)**
>  To place an AV onto the market a manufacturer may choose to obtain systems type approval at international (UNECE) level. Alternatively, a manufacturer or developer could also apply under a domestic AV technical scheme. In both cases, the vehicle as a whole will then need to receive GB whole vehicle approval (which will soon be required for most new motor vehicles registered for use on GB roads).
>  
Figure out regulatory parameters, ie to which specifications must the product be built?

Will this be a self-driving vehicle or a driver assisted vehicle?

> Before the vehicle can then legally drive itself it will need to undergo a separate “authorisation” stage. Authorisation will be needed in order for the individual in the driving seat to acquire the status of a user-in-charge when using a self-driving feature and to divert their attention from the road. It would also be needed for a no user-in- charge (NUIC) vehicle to be used without a responsible person on board.
> 
> To obtain authorisation, the vehicle manufacturer or developer would submit its vehicle to the British authorisation authority. The authorisation authority would assess each of the vehicle’s ADS features.
> 
> In addition, the authorisation authority must assess whether the entity putting the vehicle forward for authorisation has the reputation and financial standing required to be an Authorised Self-Driving Entity (ASDE). 
 
### 2. Problem Formulation 

**Safety and security**

A safe (considerably safer than human-driven vehicles), self-driving vehicle.


**Explainability**

How to balance technical specifications with social acceptance and explainability?

**Value chain expansion**

Is there an opportunity to meet the needs of an underserved population? (page 28-29)

> At present, disabled people travel less than the rest of the population... AVs should not disadvantage people by reason of disability. However, it is also about seizing the opportunity. One of the main advantages of AVs is their potential to make life better for those with disabilities. They provide hope to people currently unable to drive that they may be able to own a car. They also have the potential to offer new forms of on-demand services


**Equality (page 27)**
> One concern about AVs is that they may redistribute risk from one group of road users to another. Even if AVs are safer overall, and lead to lower risk for some users (such as car occupants) the fear is that they might lead to higher risks for others (such as cyclists and pedestrians)


Overarching themes (page 27): equality, accessibility and data

 
### 3. Data Extraction and Procurement 
**GDPR**

What types of data can be extracted and for how long can it be stored? Can it be shared with third parties? Must it be shared, eg in the case of an accident?

> 
**Data protection and privacy (page 31)
**
> the police will need to know whether an ADS was engaged at the time of any incident involving an AV. Similarly, insurers need to know whether the vehicle was present at the alleged time and place, whether the ADS was engaged and how the incident occurred. 

> AVs generate huge quantities of data - so considerable data may be recorded. However, under current EU and UNECE initiatives, very little data must be recorded.

**Data protection and privacy (page 32)**
>  ASDEs should be under a legal duty to disclose information to insurers that is necessary to decide claims fairly and accurately. 

**Equality (page 28)**
> Several consultees mentioned the need for regulators to establish a database of scenarios for testing...
> 
> This database could include data that helps ensure all groups are treated equally, e.g. by documenting types of religious or cultural clothing that AV developers may otherwise have been unaware of, or how road crossing behaviour of visually-impaired people aided by guide dogs may differ from 'typical' behaviour, such that these permutations are engineered for.

**Data quality (page 32)**

>  the DSSAD (or other data storage system) would need to record location data.

**Current data extraction obligations are insufficient to establish cause of collision and will likely expand (page 32)**

> if an AV collided with a pedestrian in the absence of human witnesses, there would be no clear way of establishing what had happened...A study for British Standards Institute recommended that AVs should record “digital commentary driving” (DCD) data streams. Following an incident this would allow investigators to understand (among other things) what the ADS “saw”, how the object was classified, and what predictions the system made about its movements
>  
### 4. Data Analysis 

**Data quality (page 31)**

> As from July 2022, both conventional and automated vehicles sold in the EU will need to be equipped with event data recorders (EDRs). EDRs aim to provide data to help analyse patterns of collisions. However, under the current state of technology, EDRs will not record collisions between a vehicle and something of much lower mass, such as a motorcycle or pedestrian. Furthermore, as currently conceived, EDRs will not record details of individual vehicles. They cannot be used to investigate individual incidents.


**Safety (page 31)**

>AVs will need to store more data than are captured by EDRs alone. They will therefore need a second system of data capture. UN Regulation 157 on Automated Lane Keeping Systems (the ALKS Regulation) refers to this as a Data Storage System for Automated Vehicles (or DSSAD). The ALKS Regulation sets requirements for what a DSSAD must record. It must record each time an ALKS is activated or deactivated or issues a transition demand (together with a date and time stamp). It must also record when the vehicle is involved in a detected collision.

**Equality Impact Assessment (page 32)**

>  Initially, collision detection systems in ALKS are likely to be similar to those in conventional cars, so may not record collisions with vulnerable road users.

This may result in systematic forms of discrimination or inequality if it turns out that some AVs are worse at identifying specific groups of vulnerable people (e.g. elderly pedestrians, users of mobility devices). 

 
### 5. Preprocessing and Feature Engineering 

**Equality (page 27)**
> The Equality Act 2010 prohibits imposing detriment on people on the basis of protected characteristics in various circumstances. Furthermore, regulators of AVs (as public authorities) are subject to the public sector equality duty. They must have due regard to eliminating discrimination and advancing equality of opportunity between persons who share a protected characteristic and persons who do not share it

(page 29)

> self-driving features should be designed to be used by people with hearing impairments and other disabilities

(page 31)

> transition demands should including haptic as well as auditory signals

(page 27)

> Air bags save many lives, but the first generation of air bags posed risks to smaller passengers, such as women of small stature, the elderly, and children
 
 
### 6. Model Selection and Training 

Safety and security
 Comment

A safe (considerably safer than human-driven vehicles), self-driving vehicle.

What is safe enough? What rate of incidents will the public accept?

Will the vehicle be safe to pedestrians, cyclists, other drivers, etc?

Will it be secure against hacking?

**Equality (page 28)**

> Current facial recognition software may also exhibit a bias towards white, male faces. For non-white and non-male faces, the accuracy of facial recognition systems may decline significantly

> Systems may not have been trained to deal with the full variety of wheelchairs and mobility scooters; or they may struggle to recognise certain road user groups. These issues may be exacerbated if designers are drawn predominantly from one demographic group

> [Vehicles must identify] individuals of all races and ethnicities in different daylight conditions, individuals wearing robes and skirts (if the system works by identifying leg movements) and individuals in different kinds of wheelchairs and mobility scooters


**Competition issues**

Are spare parts compatible across cars? 

 
### 7. Model Testing and Validation 

**Safety and security** -- see above

**Equality (page 28)** -- see above

**Data collection**

**Meeting regulatory standards**

**Quality checks**
 
### 8. Model Reporting 

**Duty of Candour**

A duty of candour regarding any incidents would be in place, making it a criminal offence to (1) fail to provide information to the regulator or (2) provide information to the regulator that is false or misleading.

Data collection, protection and privacy (page 33)

> There is considerable work still to be done in developing standards for data collection concerning collisions and other incidents. 

**Data protection and privacy (page 31)**

> the police will need to know whether an ADS was engaged at the time of any incident involving an AV. Similarly, insurers need to know whether the vehicle was present at the alleged time and place, whether the ADS was engaged and how the incident occurred. 

**Safety and security** -- see above
 
### 9. Model Productionalisation 
Should this name be changed to make it more accessible for regulators (e.g., ‘model implementation’)? Or should we keep to the more technically accurate terminology? 

**Meeting regulatory standards**

**Ensuring Accurate Marketing** (page 123)

Marketing must not mislead consumers into thinking vehicles have self-driving capabilities greater than they are in reality.

Consumers should not be given the misleading impression that they have no responsibilities in an AV.

> Misleading marketing of AVs is a live issue that has arisen in other jurisdictions. Regulators around the world are adopting a range of approaches to regulate AV marketing.
> 
> 
> California has adopted targeted regulation directed specifically at misleading advertisements of AVs...In China, a fatal accident led to calls for standardised terms in the marketing of vehicles with driver assist functions. In Germany, the issue has been approached as a matter of unfair competition.304 In the US, consumer rights groups have also urged the Federal Trade Commission to investigate whether the name “autopilot” is misleading.
> 
**Safety and security** -- see above
 
### 10. User Training 
**Ensuring Accurate Marketing** (page 49)

Users must be made aware of what the limitations of the car. They must not drink or sleep if they are the user-in-charge. They must learn how to respond in the event of a transition demand.

 
### 11. System Use and Monitoring 

**Ensuring that conditions have not considerably changed from when the model was designed**

The operational design domain (ODD) is the conditions for which AVs are designed, such as the type of road, speed, or weather in which they function. Has the ODD fundamentally changed?

**Safety and security** -- see above

 
### 12. Model Updating and Deprovisioning 
**Equality (page 28)** -- see above

**Competition issues**

Are spare parts compatible across cars? 


## Value Chains

ASDE equality impact assessment (page 29)

The Authorised Self-Driving Entity (ASDE) is the firm that seeks AVs for its authorisation and takes legal responsibility for their actions

> an ASDE will be required to submit an equality impact assessment alongside their safety case

Is there an opportunity to meet the needs of an underserved population? (page 28-29)

> One of the main advantages of AVs is their potential to make life better for those with disabilities. They provide hope to people currently unable to drive that they may be able to own a car. They also have the potential to offer new forms of on-demand services

Insurers

Certifying companies

Marketing companies

User education companies

The issuance of “interim passenger permits”  would allow passenger service providers to have conditional operational approval of AVs pending further evidence on how AVs interact with passenger safety and accessibility

Other impacted industries -- providers of vehicles such as bicycles, motorcycles, scooters, etc.

