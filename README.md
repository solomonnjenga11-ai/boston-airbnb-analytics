Boston Airbnb Strategic Analytics (Python)

Turning Boston Airbnb Data Into Strategic Insight
📌 Project Overview
This project analyzes 4,419 Airbnb listings in Boston to uncover the key drivers of price, revenue, occupancy, and guest experience. Using Python and statistical modeling, the analysis identifies which listing features matter most for host success — and where hosts lose value through poor configuration, calendar mismanagement, or guest experience gaps.

This work was completed for ISOM 835 under Prof. Hasan Arslan and later recognized for its analytical depth and clarity.

📂 Data Source
The dataset comes from Inside Airbnb (public data):

“The study adopted data of 4419 listings within Boston, as sourced from Inside Airbnb… associated with 79 columns.”

After preprocessing, the dataset was reduced from 79 to 53 columns, with new engineered features such as:

price_per_person

occupancy_vs_availability

revenue_per_day

host_tenure_years

🛠 Methods
The analysis uses both descriptive and inferential statistics:

Descriptive
Bar charts for neighborhood comparisons

Boxplots for superhost vs non‑superhost

Correlation heatmaps for top 20 predictors

“The main descriptive statistics… mean, graphs, and correlation… boxplots and bar graphs.”

Inferential
OLS regression models for:

Price

Price per person

Revenue per day

Review scores value

Occupancy vs availability

“OLS regressions were adopted to establish features that had a significant relationship with the selected five targets.”

📊 Key Findings
1. Neighborhood Effects
Longwood Medical Area and Bay Village lead in revenue per day and price per person.

Downtown shows the highest occupancy.

“Longwood Medical Area and Bay Village record more than $250 per day… Downtown shows the highest occupancy.”

2. Superhost Dynamics
Superhosts earn higher daily revenue (~$80 vs ~$70).

But superhost status reduces price and value scores slightly — possibly due to higher guest expectations.

“Superhosts are associated with higher average daily revenue… superhost (-0.027) slightly lowers perceived value.”

3. Pricing Power
Strongest positive predictors of price:

Bathrooms (+486)

Accommodates (+214)

Negative predictors:

Instant bookable (-258)

Beds (-221)

Superhost (-154)

“Bathrooms (+486), accommodates (+214)… instant_bookable (-258), beds (-221), superhost (-154).”

4. Occupancy Drivers
Boost occupancy:

Availability_30

Availability_60

Reduce occupancy:

Availability_90

Availability_365

“Availability_30 (+0.055) and availability_60 (+0.069) support occupancy… availability_90 (-0.107) and availability_365 (-0.013) hurt occupancy.”

5. Guest Experience
Value scores are driven by:

Overall rating

Communication

Cleanliness

Accuracy

Location

“Review_scores_value: driven by overall rating (+0.51), communication (+0.18), cleanliness (+0.16), accuracy (+0.13), location (+0.11).”

💡 Recommendations
1. Feature Optimization
Increase bathrooms or capacity where possible

Reduce instant‑book listings to support higher pricing

“Configure the property effectively… reduce instant book listings to encourage higher pricing.”

2. Calendar Strategy
Avoid overexposure (90–365 days open)

Focus on short‑term availability (30–60 days)

Align availability with local events

“Identify excessive availability… keep calendars open in the short term during major local events.”

3. Experience Coaching
Improve communication and cleanliness

Ensure listing descriptions match reality

Manage guest expectations, especially for superhosts

“Customers find value… based on communication and cleanliness… ensure superhosts manage expectations effectively.”

🧠 Reflection
This project strengthened:

AI literacy (clean → correlate → regress → interpret)

Social intelligence (translating coefficients into host actions)

Inquiry (challenging assumptions about superhosts)

Leadership (providing actionable tools for hosts)

“A structured workflow… challenged the assumption that superhost/tenure always improves monetization.”