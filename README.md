# BENCH 
## Machine Learning with Business One Group

### Introduction
The engagement with UNSW aims to provide some real world experience to students from UNSW by engaging with business partners in the community (eg) Bench.

### Project Aim
The aim for the project is to use machine learning to:
1. Inspect past Bench campaigns to generate actionable insights
2. Provide recommendations for changes for current or future campaigns

### Background
Bench runs digital marketing campaigns for customers using our platform to manage the setup and reporting on the campaigns. Campaigns are run for multiple purposes (eg improving brand awareness, building leads etc), with clearly defined goals agreed up front with clients.

Traditionally marketing campaigns have been run with very little feedback on the results of campaigns. The campaigns are set up well in advance, often running for months, without any change to the campaigns as they continue. This often generates significant wastage, as people who do not match the product see the ads, or see the same ads multiple times.

Bench has pioneered the concept of agile marketing, where campaigns are constantly tweaked to deliver the most efficient campaigns. In this case, efficiency means achieving the aims of the campaign at the lowest possible cost. This is possible by running campaigns that target very specific audiences and constantly track the performance of those campaigns. Campaigns are constantly adjusted to maximise the efficiency of the campaigns.

### Specific Insights
While Bench runs multiple different sorts of campaigns, we’re looking to improve one specific area of campaigns. The most measurable campaigns are based on Acquisition, as they track a specific action a customer performs (eg buying a product).

Acquisition can be an element of any campaign. The key measure of Acquisition based campaigns is the cost to add new customers, or CPA. You can improve the CPA on campaigns by decreasing the ratio of Cost : Acquisitions:
1. Decreasing the cost while maintaining the same rate of acquisition
2. Increasing the rate of acquisition while maintaining the cost
3. Both

We’re looking for practical, actionable insights we can apply to current and future campaigns. In order for insights to be useful, they need to be something that can be changed on a campaign. Not all aspects of a campaign can be easily changed, or clearly identified.

### Adjusting Campaigns
Multiple parameters can be adjusted at the same time for campaigns. Adjusting any single one of these may change the results of the campaign, changing more than one at a time could produce unpredictable results, or may result in some of the changes cancelling each other out.

Some parameters are more easily adjusted than others. See the notes on each of the parameters below:

| Parameters        | Ease of Adjustment           | Notes  |
| ------------- |:-------------:| -----:|
| Audience     | Low | $1600 | this is one of the most powerful and least flexible parameters. Audiences can be quite complex, built up from multiple parameters (gender, geography, age, interests, income etc). Audiences are also often quite specific to campaigns, so it difficult to provide actionable insights across multiple campaigns.
| Budget between layers      | High      |   the amount spent per layer |
| Budget between channels | High     |    the amount spent per channel |
| Time of Day      | Medium      |   The time of day when the ad is displayed |
| Day of Week | High     |    The day of the week that the ad is displayed |
| Primary Message      | Medium      |   The primary message for the ad. This might be complex both to process and adjust, as it might require some pre-processing on the primary message to extract keywords. |
| Device | High     |   The device that is used to view the ad. For example: TV, Tablet, mobile |
| Ad version | High     |   The version of the ad displayed to the customer |
| Business vertical of the client | Low     |  The business vertical the customer is operating in (eg financial services). While this isn’t something that can be changed, it could be an important input element in data for campaigns |
| Size of Creative | Medium     |  The dimensions of the ad displayed to customers |
| Publisher | Medium     |  Where the ad is displayed, eg smh.com.au. This could also be a grouping of site (eg Fairfax as a publisher could have ads displayed on SMH, the Age and Domain) |
| Exchange | Medium     |  Where the ad was purchased through |
| Age of Ads | High     |  The length of time the ad has been displayed |
| Image Content | Low     |  This would run some analysis on the images to find some correlation between the content of the images and the results of the campaign. This is a very broad area, but it might find a correlation between a colour (eg green) and results for a specific vertical (eg financial services). Or images that contain faces might perform better. |

### Examples of Actionable Insights
Here are a number of insights that we might expect to see from a campaign. Note: these are examples, intended to provide guidance, rather than dictate specific outcomes.

Example:
1. CPA increases when the same ads are used for 4 weeks only
    - Action: update the creative for ads every 4 weeks to ensure CPA is maintained
2. CPA changes based on the day of week for campaigns for financial companies. CPA is lower for ads displayed from Monday-Friday and higher for ads displayed on Saturday-Sunday.
    - Action: increase spend on weekdays and decrease spend on weekends
3. CPA is higher when we run campaigns across a number of layers. The optimal budget breakdown across layers for the campaign might be: 50% Acquisition, 10% Awareness, 40% Engagement
    - Action: adjust campaigns to use this budget breakdown


### Glossary
This is a list of key terms about Bench and digital marketing.

  - Acquisition - a layer, aimed at acquiring
  - Ad - an advertisement for a product or service
  - Ad set - grouping of Ads by Audience
  - AQ - short for Acquisition
  - Audience - grouping of customers by multiple attributes (eg gender, age, interests)
  - AW - short for Awareness
  - Awareness - a layer, aimed at improving awareness of a product or brand
  - Bid - ads are purchased by a bidding process, similar to ebay
  - Campaign - a collection of advertising, across multiple channels
  - Channel - Where the ads are delivered through (eg Social)
  - CPA - Cost per Acquisition, meaning cost of acquiring a new customer
  - CPC - Cost per Click, meaning cost for each click on the ad
  - CPM - Cost per Mille, meaning cost per 1000 impressions, ads are generally sold as CPM
  - Creative - Graphic used in ad display
  - Direct Response - a layer, aimed at triggering an action on the part of a customer, eg signing up for a mailing list
  - Display Ads - visual advertisements, eg banner ads
  - EN - short for Engagement
  - Engagement - a layer, aimed at improving customer engagement (eg share on social media)
  - Exchange - an exchange lets Bench buy advertising for campaigns
  - Layer - This layer of the sales funnel that campaign targets.
  - LD - short for Lead
  - Leads - a layer, aimed at collecting customer details as new leads
  - Wastage - where ads are presented to people who do not match the product
