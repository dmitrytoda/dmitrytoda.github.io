---
layout: single
permalink: /pm/
sidebar:
  - nav: sidebar-pm
---

# Career overview

I dedicated over a decade of my life to project management, starting from 2011. That includes 4 years in Russia, 2 in Chile and 4 in Canada, spanning finance, consulting, e-commerce and online gaming industries. I led dream teams of up to 20 software engineers, business analysts, architects, designers and QA, with annual budgets reaching $4 million and timelines from one month to one and half years. My management style is often a mix of classic waterfall with Agile approaches.

Before that, I worked as business analyst and analysis team leader for another 5 years, doing consulting for investement management at Accenture and OSS (operation support systems) for Tier-1 telecommunication providers at NetCracker.

I hold PSM (Professional Scrum Master) and PMP (Project Management Professional) certifications. Giving back to the PM community, I take part in PMP exam development workshops as volunteer SME (subject matter expert).

# Portfolio

## Demand prediction and visualization for lululemon

### Business problem

The retail brand needs to know how many units of women's yoga pants of such model, size and colour will be sold in such store on such date. This spans several thousand SKUs, 400+ physical stores and multiple e-commerce selling points, and due to fashion industry reality, the forecast is needed for a year and a half into the future (such is the seasonal "design - manufacture - deliver from China - sell - rebuy" product lifecycle). The prediction is needed both in-season (for items with sales history) and pre-season (for items that have never been sold before: need to make something out of nothing).

Once the prediction is in place, business needs to know how accurate it is, and it has to be presented as a Data Science Workbench via Plotly Dash charts, comparing the forecast and actual sales using MAPE (mean absolute percentage error).

### Project summary

* Duration: 5 months (March - July 2021)
* Teams: 
    * Demand prediction: 3 data engineers, 2 business analysts, 3 QA, product owner
	* Forecast visualization: technology manager, 3 more data engineers
	* Collaboration with: data science, devops, architecture, reporting, DBA, integration
* Part of a larger 6 track data flow program, managed in SAFe methodology with 4 week sprints and 3 sprint program increments
* Technology stack: AWS (S3, Glue, Athena, EKS, EC2), Python, PySpark, Kafka, AirFlow, Plotly Dash, PostgreSQL, PowerBI
* Underlying data science: 
	* linear regression model using weighed recursive least squares
	* econometric prediction explaining the demand in terms of base sales rates and demand factors
	* model coefficients taking into account seasonality and holiday effects
	* data sets of 13 Gb per quarter with multiple quarters used for prediction
* PM tools: Jira Agile, Confluence, SharePoint, ServiceNow

## ForgeRock upgrade for Scotiabank
<p align="center">
<img src="/assets/images/logos/scotia.png"  height="100">
</p>
### Business problem

ForgeRock is an identity and access management platform. 

1. Scotiabank was running an outdated version of ForgeRock that was out of vendor support and had known vulnerabilities
2. Over the last year, there were two major incidents with system becoming unavailable due to unexpected traffic surge from on of the client channels
3. The goal of the project was to upgrade the three main ForgeRock modules (OpenDJ, IDM and OpenAM) to new versions, bringing the system back under vendor support, and to implement additional resilience features to prevent any channel from accidentally taking the system down.

### Project summary

* Duration: 14 months (September 2020 - October 2021)
* Team: 13 full-time engineers + part-time business analyst and QA
* Scope: upgrading the platform, developing new features, installing extra servers in UAT and production, deployment, and business acceptance by channels
* Stakeholders: GIAM (Global Identity and Access Management) department, PLATO (PLATform Organization - technical owner of the system), ForgeRock (the system vendor), PMO, ECCO (procurement department), DBA
* Technology: ForgeRock, Oracle
* PM tools: Jira, Confluence, MS Project, CA PPM

### Results

* Authentication and provisioning performance improvement and surge protection for 6 client channels with a total of 11 million end users.
* Project completed under budget.

## Pennsylvania regulated gambling market
<p align="center">
<img src="/assets/images/logos/pokerstars.jpg"  height="100">
</p>
### Business problem

1. After the [Black Friday](https://www.poker-king.com/dictionary/black-friday/) of 2011, online poker became illegal in the United States.
2. In 2013, New Jersey became the first state to allow online gamling again, and PokerStars were promtly the first to enter this market.
3. Pennsylvania became the second state to legalize online poker. As global market leader, PokerStars, known by then as The Stars Group, decided to follow its strategy of being the first company to have a real money offering. An agreement was reached with Fox Bet to launch a co-branded product.

### Challenge

The project had an unmovable launch date of Nov 4, 2019, in order to not only be the first company on the market, but also to offer a product on the very first day it was legal to do so.

### Project summary

* Duration: 8 months (March - November 2019)
* Team: over 20 software developers, QA, graphical artists, DBA and DevOps
* Scope: implementing all regulatory requirements (legal age, self-exclusion, information disclosure, information storage etc) for online poker, casino and sports betting on desktop, mobile and web
* External stakeholders: PGCB (Pennsylvania Gaming Control Board)
* Technology: C, Java, DB2, Android, iOS, Jenkins
* PM tools: Jira, Confluence (you'd be surprised how much you can do with just these two)

### Results

Real money offering successfully launched on Nov 4, 2019, making PokerStars the first company to enter this new regulated market.

## Credential management for Falabella

<p align="center">
<img src="/assets/images/logos/falabella.png"  height="100">
</p>

2015-16. Integration of new credentials managements system into banking IT landscape using Service-Oriented Architecture (SOA).

### Technology

Oracle Service Bus middleware, VU security platfrom. 

### Results

Security enhancement due to new user authentication mechanism. False-positive rate reduction (precision raised by 12%).

## Business intelligence for a Top-10 Russian bank

2014. Implementation of business intelligence and financial analytics system, including building of ETL, data warehouse and reporting engine. 

### Results

50% decrease in manual labor preparing regulatory financial reports.

## Compliance for General Electric

<p align="center">
<img src="/assets/images/logos/ge.png"  height="100" width="100">
</p>

2012-13. Automation of compliance division business processes by delivery of Alfresco BPM (Business Process Management). 

### Results

Slashed deal approval processing time by 20%. “Best project of the year” corporate award in 2013.

## Collateral management for Raiffeisen bank

<p align="center">
<img src="/assets/images/logos/raiffeisen.png"  height="100">
</p>

2012-13. Delivery of Loxon Collateral Management System.  

### Results

Improvement of the efficiency of capital allocation through up-to-date, better quality data for decisions.

## CRM for Deutsche bank

<p align="center">
<img src="/assets/images/logos/deutsche.jpg"  height="100">
</p>

2009-11. Development of a CRM (Customer Relationship Management system) for Corporate Finance division.

### Technology

Java, Oracle 

### Results

Successful implementation of a real-time CRM system providing a 360° view of customer information to over 9000 users.

