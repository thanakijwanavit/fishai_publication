
# Business plan and financial projection for Deepvision

## 1. Executive Summary

### 1.1 Concept
Deepvision brings AI to the infrared spectrometer in a modern way
where both the training and classification service is done totally online.
This means the classifier is always the latest and best-trained version.
The smart sensors are integrated with a high speed 4G data module which minimize the latency.
<br>
<br>
### 1.2 Not just cloud but container based
The benefits of moving the architecture to the cloud is numerous.
For instance, the sensor will enjoy the latest supercomputer level performance without investing in any hardware.
However, Traditional cloud system relies on expensive rental of cloud server and their maintainace.
Deepvision will use the modern standard of Kubernetes managed container system where server will be deployed across multiple cloud server in order to garuntee a near 100% availability.
<br>
<br>
### 1.3 AI system
The advantage of using an AI based system instead of traditional non-AI classification has been demonstrated in many application such as Google image classifier, Nvidia AI enhanced GPU rendering.
The reason AI classifier has such a significantly higher performance than traditional classifier is that AI is able to accept a very large number of inputs and learn from its mistake.
Unlike traditional system, AI performance increases over usage.
As an AI specialist company, Deepvision focuses on developing the best learning algorithm to minimize the amount of samples required before the performance reaches a satisfactory level.
It has been forcasted that AI classifier will replace all traditional classifier software in the near futur
The AI framework that Datavision will use include Tensorflow, Pytorch, and our inhouse framework. These will continuously be benchmarked against each other to provide the best performace for our customer.
<br>
<br>
### 1.4 Datavision Values
The core value of Datavision system lies within quality training data, trained neural network, optimization calibration of hardware and learning algorithm.
We believe that these factors are appropriate benchmarks for the company to persue.


## 2. Product plan



### 2.1 Hardware
>We are planning to launch the AI Infrared reader hardware with our own modification including:
1. AI resolution enhancer. The AI will be integrated in the firmware API caller.
2. hardware modification to enhance both the range and resolution


### Major hardware product versions are planned by following schedule
|Date|Hardware Version| Enhancement| resolution|range|
|:----|:----------------|------------|-----------|-----|
|June 2019|1.0|hardware|5nm|1500nm|
|Dec 2019|2.0|hardware,AI|2nm|2000nm|
|June 2020|3.0|hardware,AI|1nm|3000nm|
|Dec 2020|4.0|hardware,AI|0.5nm|3000nm|

### 2.2 Software
> We plan to experiment with new training algorithm of AI to enhance both the functions and accuracy every quarter. The major update categories are:
1. GPU parralelization optimization for training
2. optimization of deep learning nodes depth and width
3. optimization of learning algorithm convergence
4. Our algorithms will be periodically against the state of art opensourced framework including Tensorflow and Pytorch. This will give us a choice to either use part of their libraries, and to further integrate our framework to theirs.

### Major software version are planned according the following schedule

| Date      | Version | Data trained(sets) | Chemicals supported | models tested | Training method variations tested |
|-----------|---------|--------------------|---------------------|---------------|-----------------------------------|
| June 2019 | 1.0     | 100                | 5                   | 2             | 1                                 |
| Dec 2019  | 2.0     | 20000              | 8                   | 10            | 10                                |
| June 2020 | 3.0     | 1000000            | 20                  | 100           | 20                                |
| Dec 2020  | 4.0     | 10000000           | 100                 | 200           | 50                                |

## 3. Business plan
### 3.1 Product and Services
income will arise from 2 major sources
* Hardware sales
	* Full stack
	* Calibrated sensor
* Service fee
	* Calibrated sensor enhancement API
	* Classification API calls
	* Maintainance




#### 3.1.1 Hardware
2 hardware categories are in the pipeline:

<b>1. Full stack hardware</b> 

These are the hardwares that doesn't require any input or modification from the users. We provide full service and charge the full service fee. 
Users of this service are aimed at non-technical end users who has no development team for computing service.

<b>2. Calibrated sensor modules</b>

These are the sensors that we develop in order to service developers both in corporate environment or individual hobbyists. The sensors will have enhanced accuracy due to both the calibration and AI enhancement. 

#### 3.1.2 Services

3 services categories in the pipeline

<b>1. Calibrated sensor enhancement API</b><br>

API calls to the server for the enhancement of Infrared accuracy. These will be paid as a subscription service.<br> The data out put is the enhanced accuracy infrared spectrum. This can be used in any application that require a high data accuracy.<br><br>

<b>2. Classification API calls</b>

API calls to the server for  the classification service. This is used to determine the concentration of the compounds that we support

<b>3. Maintainance</b>

This is a subscription for customers that purchase the full stack hardware who require a full support on keeping the system running. The service fee will be charged per year.

## 4 Financial Projection

### 4.1  Revenue generation

<b>1. Hardware sales</b>

![](https://github.com/thanakijwanavit/fishaicharts/blob/master/full_stack_sales.png?raw=true)
*full stack hardware sales*

>Full stack hardware will be the company's first source of revenue and will remain the main source of cashflow for the first 30 months.
> However, we expect the sales of calibrated sensor to overtake near the 30th month when we have more developers as business partners. We expect the high growth due to the wider variety of application which include the ones that our AI dont support.




![fig 4.1.1 calibrated sensor sales](https://github.com/thanakijwanavit/fishaicharts/blob/master/calibrated_sensor_sales.png?raw=true)

> Comparing the 2 Products, The calibrated sensor require very little investment and is highly scalable



<b>2. Service</b><br>

Service revenue arise from 2 sources:
* Maintainance fee
> Maintaince fee is charged to the customer who purchased the full stack hardware. Although there is a high potential for revenue, it involves using a large labour force which leads to high cost.

!['fig 4.1.2 Revenue from Maintainace fee'](https://github.com/thanakijwanavit/fishaicharts/blob/master/profitability_of_maintainace.png?raw=true)



* API calls
> API calls is charged to users using our trained AI. The user will pay per use with both training data and cash. We will charge per API call to cover our cloud maintainace cost. 
> Ultimately this will be our main source of income and value.


!['fig 4.1.3 Revenue from API calls'](https://github.com/thanakijwanavit/fishaicharts/blob/master/profitability_of_api_calls.png?raw=true)


<b>Source of income comparison</b>

Although sales is the main driver of revenue, the service business will become more profitable and sustainable due to the fact that the running cost is a fixed cost and does not increse significantly as the demand increase.


!['fig 4.1.4 service vs hardware revenue'](https://github.com/thanakijwanavit/fishaicharts/blob/master/hardware_vs_service_revenue.png?raw=true)
!['fig 4.1.5 service vs hardware profit'](https://github.com/thanakijwanavit/fishaicharts/blob/master/hardware_vs_service_profit.png?raw=true)


<i>The forcasted revenue generated from hardware vs service over 30 months</i>
### 4.2 Costs
1. Full stack hardware
	* Cost of goods sold include standalone sensor module, casing, and other consumables
	* Fixed cost include labour, system maintainance, rent, and other monthly costs.
2. Standalone sensors
	* Cost of goods sold include sensor, modification hardware, and consumables
consumables

![fig 4.2.1 Summary of expense](https://github.com/thanakijwanavit/fishaicharts/blob/master/expense.png?raw=true)

### 4.3 Cash flow

Cash flow will be negative in the first 20 months due to the high cost of semi-complete modules.  However, we aim to achieve breakevn by the month 22 as the cost decreases and we use a cheaper alternative due to the advancement of the AI.
The business model only takes into account the core business. If we are able to get more cashflow into the company, we aim to use at least 50% on obtaining the training data. 
Training data is one of the most important factor that determines how fast and accurate the AI will perform.

![fig 4.3.1 cash flow](https://github.com/thanakijwanavit/fishaicharts/blob/master/cashflow.png?raw=true)

in case that we have more investment than the minimum required, the forecasted cash flow will look like the one below.


![fig 4.3.2 cash flow including development](https://github.com/thanakijwanavit/fishaicharts/blob/master/cashflow_including_development.png?raw=true)

## 5 Valuation

### 5.1 Valuation by DCF

#### Growth
Valuation of the company can be calculated from the projected cash flow assuming a conservative terminal growth after 30 months of 15% per year.

#### Discount rate
Discount rate is calculated at 20% due to the high uncertainty of the newly established company. This is considered conservative given that the world market average growth rate is well under 10% per annum.

#### Valuation
Valuation is done by calculating the perceptual discounted cash flow at the rate agreed in previous section. This gives a conservative valuation of approximately 3 million USD.
Note that this assume a constand 15% growth rate which in reality we are aiming for it to be more exponential as per the nature of a scalable software business.


![fig 5.4.1 valuation by DCF](https://github.com/thanakijwanavit/fishaicharts/blob/master/valuation_by_DCF.png?raw=true)

### 5.2 Valuation by comparison to the market(P/E, Revenue, and growth rate)

#### Period of valuation
The company aims  to complete a series C which indicates a pseudo maturity at approximately 30 months.
This is the timeline which can be used for profit comparison with the market.

#### Comparison to market P/E
The market average P/E of software business sector is [some numbers](). This is referenced from().

#### Valuation

Searting in 30 months, the company is expected to have an annual earning of approximately 300K which translates to the valuation of 12-24 million USD. The valuation over the 15 years period is forcasted as per the chart below.

![fig 5.2.1 valuation by PE](https://github.com/thanakijwanavit/fishaicharts/blob/master/valuation_by_PE.png?raw=true)

### 5.3 Summary of valuation
It is apparent that the valuation using PE ratio gives a much higher value than the discounted cashflow approach. This is mostly due to an oversimplified DCF earning growth model which is kept constant at 15%. Meanwhile the PE valuation expects a market rate of growth as the company mature which is usually expected to be much higher than 15%. 
Note that the market valuation using PE is more realistic for a technological startup due to the variable growth rate. DCF is usually a suitable index for valuing a mature company.

## 6 Appendix





## 7. Reference

