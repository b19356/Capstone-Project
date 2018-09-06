## *“Introduction to Data Science”* Capstone Project Proposal

### Background

Under President Obama, the federal government initiated an effort to unveil the secrecy behind health-care charges.  Specifically, the Centers for Medicare and Medicaid Services (CMS) has published information about inpatient hospital charges and associated reimbursements for Medicare beneficiaries spanning fiscal years 2011 – 2016.  The data shows wildly different hospital charges for the same procedures, even in similar geographic regions, further amplifying the confusion ([1](https://www.huffingtonpost.com/2013/05/08/hospital-prices-cost-differences_n_3232678.html),[2]( http://www.modernhealthcare.com/article/20170831/NEWS/170839968)).  Some public sources have developed guides to help consumers identify the most cost-effective route for treatment based on CMS reports ([3](http://archive.nytimes.com/www.nytimes.com/interactive/2013/05/08/business/how-much-hospitals-charge.html)).

Although the data reflect charges after claim resolution, the American Hospital Association (AHA) has protested that the charges do not accurately reveal what consumers are charged because they do not contain updated information after further negotiations with insurance companies ([2]( http://www.modernhealthcare.com/article/20170831/NEWS/170839968)).  The government, however, is not privy to insurance information, nor is it shared among hospitals.  Assuming the AHA is correct, then the consumer guides stemming from CMS reports are misleading.

Like the government, the AHA states they are committed to providing greater transparency and want to publish accurate information about their charges ([4](https://www.aha.org/issue-brief/2018-05-04-hospital-price-transparency)).  One of the primary challenges is that insurance companies do not want to reveal their charges and reimbursements.

### Problem

The current procedure for reporting Medicare-eligible, inpatient hospital charges hinders the ability to accurately forecast and reconcile internal hospital financials.  Specifically, the inaccurate, disparate gap between reported charges and reimbursements has a ripple effect on other hospital financial records.  In addition, the inability of even hospitals themselves to explain the huge charges and variations fosters a negative public image that hospitals willy-nilly gouge consumers when they are at their most vulnerable.

### Client

This project was commissioned by the AHA to analyze the gap between charges and reimbursements in order to recommend changes to the current reporting process.  The project will provide recommendations for handling specific treatments to ultimately improve internal financial record keeping.  If implemented, the recommendations may also serve to mend negative public perceptions.

### Approach

Compare 2011 hospital bills (Average Covered Charges) across the various treatments and compare to the reimbursement amounts (Average Total Payments) in order to identify the biggest discrepancies ([5](https://data.cms.gov/browse?q=IPPS%202011&sortBy=relevance)):

* Examine geographical region, type of treatments, and number of cases as potential factors
* Refine the examples to the most inexplicable cases
* Develop recommendations

If time permits, repeat the analysis for the most recent 2016 data to see if anything has changed since the information was first made public.
