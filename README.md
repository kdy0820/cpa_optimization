# Project Background
As a B2B technology firm, NexGen Systems relies heavily on strategic outreach to generate qualified leads. Despite a stable marketing budget, the company has recently faced rising Customer Acquisition Costs (CPA) and stagnant ROI. Leadership required a data-driven investigation to determine if our static bidding strategies across various channels (Email, Social Media, YouTube, Search) were failing to account for weekly market fluctuations and audience-specific behaviors.

Acting as a data analyst for NexGen Systems, my objective was to conduct a forensic performance audit using a comprehensive dataset of over 200,000 campaign records spanning two years. By leveraging advanced data engineering and variance modeling in Excel, this project identifies capital inefficiencies and provides a data-backed "Day-Parting" roadmap to optimize marketing spend.

Insights and recommendations are provided on the following key areas:

- **Category 1:** Inefficiency Detection & Friday Spikes
- **Category 2:** Efficiency Opportunities & Day-Parting
- **Category 3:** Audience Segmentation Behavior
- **Category 4:** Strategic Optimization & Reallocation

The complete dataset sourced and the initial data cleaning steps can be found here [link].

The Excel-based variance models and advanced tracking formulas can be found here [link].

An interactive Executive Dashboard used to report and explore multidimensional campaign metrics can be found here [link].


# Data Structure & Initial Checks

The main database structure for this analysis consists of four primary sheets containing a total row count of over 200,000 records. A description of each sheet is as follows:
- **Raw Data:** The foundational dataset containing the unformatted, historical campaign metrics over a two-year period.
- **Cleaned Data:** The transformed dataset utilizing advanced Excel functions (such as XLOOKUP and TEXT) to structure the data relationally, calculate True CPA, and establish CPA Variance benchmarks.
- **Pivot Tables:** The aggregation engine utilizing multidimensional Pivot Tables to isolate performance by Target_Audience, Customer_Segment, and Campaign_Type.
- **Executive Dashboard:** The interactive visual layer utilizing connected Slicers and Pivot Charts to present key findings.


# Executive Summary

### Overview of Findings

Our static bidding strategy is creating severe capital inefficiencies due to daily market fluctuations. We identified a massive "bleed point" on Fridays driven by intense bid competition, alongside a highly underutilized efficiency window on Saturdays. By pivoting to a dynamic "Day-Parting" strategy and shifting 20% of the Friday budget to Saturday, NexGen Systems is projected to reduce its blended CPA by 12% while maintaining our current lead volume.


# Insights Deep Dive
### Category 1: Inefficiency Detection & Friday Spikes

* **Main insight 1:** The audit isolated a significant positive variance (cost increase) systematically occurring on Fridays.
  
* **Main insight 2:** This Friday spike represents an estimated $82,000 per month in suboptimal marketing spend.
  
* **Main insight 3:** The inflated acquisition costs on this day were driven entirely by bid competition rather than an increase in lead quality, as conversion rates did not proportionally increase.
  
* **Main insight 4:** Static bidding across channels failed to mitigate these spikes, blindly spending the allocated daily budget regardless of the inflated CPA.


### Category 2: Efficiency Opportunities & Day-Parting

* **Main insight 1:** Saturday was identified as the single best day for savings and a critical "high-efficiency window."
  
* **Main insight 2:** During the Saturday window, our CPA was trading consistently at 15% below the established historical benchmark.
  
* **Main insight 3:** Despite the favorable CPA, our current campaign structure under-allocates budget to weekend campaigns, leaving highly cost-effective leads on the table.
  
* **Main insight 4:** The disparity between Friday's inflated costs and Saturday's suppressed costs highlights the immediate need for a dynamic day-parting strategy.


### Category 3: Audience Segmentation Behavior

* **Main insight 1:** The Health & Wellness customer segment was identified as the primary driver of the aggressive Friday cost-spike.
  
* **Main insight 2:** Competitor bidding for Health & Wellness audiences peaks at the end of the traditional workweek, driving up the baseline cost per click/impression.
  
* **Main insight 3:** Multi-dimensional drill-downs revealed that this segment behaves uniformly across most channels (Social Media, Search), making channel-switching an ineffective mitigation strategy.
  
* **Main insight 4:** Conversely, Health & Wellness audiences remain active on Saturdays, but competitor bid pressure drops significantly off, creating an arbitrage opportunity.


### Category 4: Strategic Optimization & Reallocation

* **Main insight 1.** A "Day-Parting" reallocation roadmap was modeled to specifically counteract the Friday bleed point.
  
* **Main insight 2.** The model shifts exactly 20% of the allocated Friday budget directly into the Saturday high-efficiency window.
  
* **Main insight 3.** This reallocation is projected to reduce the overall blended CPA for the company by 12%.
  
* **Main insight 4.** Because the Saturday market features less competition, lead volume is projected to remain stable (or slightly increase) despite the lower overall capital expenditure.


# Recommendations:

Based on the insights and findings above, we would recommend the marketing and finance teams to consider the following:

* **High Friday CPA:** Friday campaigns generate $82,000/month in suboptimal spend. Implement strict bid caps on Friday campaigns to prevent overpaying for impressions during peak competition hours.

* **Underutilized Saturday Efficiency:** Saturday CPAs trade 15% below benchmark. Reallocate 20% of the Friday budget to Saturday to capture high-intent leads at a significant discount.

* **Health & Wellness Bid Pressure:** The Health & Wellness segment is the primary driver of the Friday spike. Shift the scheduling for major Health & Wellness email and social pushes away from Friday afternoons to avoid the most congested bidding windows.

* **Static Bidding Inefficiency:** Uniform daily budgets ignore market realities. Transition the ad accounts to a Day-Parting schedule that dynamically weights budgets toward the weekend and tapers off near the end of the workweek.
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* **Assumption 1:** The complete dataset sourced from Kaggle accurately reflects the actual pacing and distribution of NexGen Systems' historical two-year performance.

* **Assumption 2:** The analysis relies on robust lookups (XLOOKUP) and text formatting for variance modeling, deliberately avoiding broader aggregation formulas to ensure precise tracking of the daily anomalies.

* **Assumption 3:** We assumed that moving 20% of the budget to Saturday will not trigger enough new competitor pressure to drastically alter the current 15% below-benchmark discount.
