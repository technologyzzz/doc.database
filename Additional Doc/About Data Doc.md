### Key Insights

* Data analysis progresses through a hierarchy of increasing complexity, cost, and business value, starting with understanding the past (Descriptive, Diagnostic) and moving to shaping the future (Predictive, Prescriptive).
* The four primary types of business analytics answer sequential questions: Descriptive ("What happened?"), Diagnostic ("Why did it happen?"), Predictive ("What is likely to happen?"), and Prescriptive ("What should we do?").
* A critical distinction exists between discovering correlations (Exploratory analysis) and proving true cause-and-effect relationships (Causal analysis), with the latter requiring rigorous, often expensive, experimental methods.
* The implementation cost and technical skill required rise significantly with each successive type of analysis, from as low as $50,000 for basic descriptive reports to over $300,000 for advanced prescriptive systems.

1. **Data analysis is a foundational process for transforming raw data into actionable insights.**
   a. Core definition
   •   Data analysis is an aspect of data science and data analytics that is all about analyzing data for different kinds of purposes.
   •   The process involves inspecting, cleaning, transforming, and modeling data to draw useful insights from it.
   b. Broad applications
   •   With its multiple facets and techniques, data analysis is used in fields like energy, healthcare, and marketing.
   •   It plays a huge role in decision-making, providing a better, faster, and more effective system that minimizes risks and reduces human biases.
2. **Analytics is structured into a hierarchy of increasing complexity and value.**
   a. The value progression
   •   The degree of difficulty and required resources increase for each type of data analysis.
   •   Simultaneously, the level of value-added insight and value increases.
   •   Each type of data analysis is interconnected and dependent on each other to some extent.
   b. Implementation cost overview
   •   The lower cost bracket typically covers 2-5 data sources and batch data processing.
   •   The upper cost bracket covers up to 15 data sources and real-time data processing.
3. **The practice of data analysis falls into two primary functions.**
   a. Hypothesis Generation
   •   This involves looking deeply at the data and combining your domain knowledge to generate hypotheses about why the data behaves the way it does.
   b. Hypothesis Confirmation
   •   This involves using a precise mathematical model to generate falsifiable predictions with statistical sophistication to confirm your prior hypotheses.
4. **Retrospective analysis focuses on understanding past and present events.**
   a. Descriptive analysis: What is happening?
   •   **Purpose:** To describe or summarize a set of data to learn what happened. It is the simplest and most frequently used type of analysis.
   •   **Methodology:** It is the very first analysis performed, generating simple summaries and processing raw data from multiple sources to provide historical insights. It involves common descriptive statistics like measures of central tendency, variability, frequency, and position.
   •   **Output:** The result is a simple presentation of data, such as static reports with KPIs. These findings indicate that something is right or wrong but don't explain why.
   •   **Examples:** Sales volume for the last month; the line graph of COVID-19 statistics on Google; customer satisfaction survey data; monthly income reports; demographic data showing 30% of customers are freelancers.
   •   **Implementation Costs:** $50,000–$150,000.
   b. Diagnostic analysis: Why is it happening?
   •   **Purpose:** To take a more in-depth look at data to uncover subtle patterns and learn why something happened. It digs deeper to find the causes of specific problems.
   •   **Methodology:** It typically comes after descriptive analysis, investigating initial findings to explain anomalies. It may involve analyzing other related data sources, including past data, and creates more connections between data to identify behavioral patterns.
   •   **Output:** Reports with drill-down, slicing, and dicing capabilities.
   •   **Examples:** Determining why sales volume was below the target; a footwear store analyzing website traffic dips by breaking down data by shoe category and seasonality; a freight company investigating the cause of slow shipments in a particular area.
   •   **Implementation Costs:** $30,000–$250,000 (if added on top of descriptive analytics).
   c. Exploratory analysis (EDA): What are the hidden relationships?
   •   **Purpose:** To examine or explore data to find relationships between variables that were previously unknown. It is most useful when formulating hypotheses.
   •   **Methodology:** It helps discover new connections and drives design planning and data collection. It is important to remember that "Correlation doesn’t imply causation."
   •   **Examples:** Analyzing the correlation between the rise in global temperature from 1950-2020 and the increase in industrial activities like the number of factories, cars, and airplane flights.
   d. Inferential analysis: What can a sample tell us about the whole?
   •   **Purpose:** To use a small sample of data to infer information and make generalizations about a larger population.
   •   **Methodology:** The goal of statistical modeling itself is to extrapolate and generalize information. It provides an estimation with a measure of uncertainty or standard deviation.
   •   **Key Dependency:** The accuracy of inference depends heavily on the sampling scheme. If the sample isn’t representative, the generalization will be inaccurate (related to the central limit theorem).
   •   **Examples:** A psychological study of 500 people concluding that seven to nine hours of sleep improves attention for the general population of 7 billion people.
5. **Prospective analysis focuses on forecasting and influencing future outcomes.**
   a. Predictive analysis: What is likely to happen?
   •   **Purpose:** To use historical or current data to find patterns and make predictions about the future. It is about forecasting.
   •   **Methodology:** This type of analysis is more advanced and is often based on machine learning and deep learning. Accuracy depends on input variables and the type of model used.
   •   **Output:** Forecasts, such as the projected sales volume for the next month.
   •   **Important Note:** Using a variable to predict another does not denote a causal relationship.
   •   **Examples:** FiveThirtyEight forecasting the 2016 and 2020 U.S. elections using polling data; an automotive manufacturer estimating the failure rate of a part to recommend service procedures.
   •   **Implementation Costs:** $30,000–$150,000 (if added on top of descriptive analytics).
   b. Prescriptive analysis: What should we do?
   •   **Purpose:** To compile insights from all previous analyses to determine the best course of action and learn what to do to solve a problem or capitalize on a trend.
   •   **Methodology:** This type, sometimes called "propositional" or "recommender" analytics, recommends actions to eliminate a future problem or take advantage of a promising trend. It requires advanced tools like machine learning, business rules, and algorithms.
   •   **Output:** Actionable recommendations.
   •   **Examples:** A recommendation on how to increase sales volume by adjusting loyalty policies; a traffic app recommending the best route home based on current traffic; AI systems from companies like Facebook, TikTok, and Netflix curating content feeds.
   •   **Implementation Costs:** $150,000–$300,000 (if added on top of descriptive, diagnostic, and predictive analytics).
   c. Causal analysis: What is the true cause?
   •   **Purpose:** To look at the cause and effect of relationships between variables, focusing on finding the true cause of a correlation.
   •   **Methodology:** Considered the gold standard in scientific studies, it is applied in randomized studies to identify causation. You must question if observed correlations are valid and look for hidden mechanisms.
   •   **Limitations:** Good data is hard to find and requires expensive research. Results are often average effects from aggregate groups and might not apply to everyone.
   •   **Examples:** A randomized control trial to test if a new drug improves human strength and focus by comparing it against a placebo.
   d. Mechanistic analysis: How does it work exactly?
   •   **Purpose:** To understand the exact, physical, or biological changes in variables that lead to changes in other variables.
   •   **Methodology:** Applied in physical or engineering sciences that require high precision with little room for error (only measurement error). It's designed to understand a biological or behavioral process or the mechanism of action of an intervention.
   •   **Examples:** An experiment to simulate safe and effective nuclear fusion, which requires a precise balance of controlling and manipulating variables with highly accurate measures.
6. **A summary framework provides guidance on applying each type of analysis.**
   a. Application guide
   •   A tutorial on the different types of data analysis is available. | Video: Shiram Vasudevan (Reference to a missing visual video)
   b. Key principles to remember
   •   Correlation doesn’t imply causation.
   •   EDA helps discover new connections and form hypotheses.
   •   Accuracy of inference depends on the sampling scheme.
   •   A good prediction depends on the right input variables.
   •   A simple linear model with enough data usually does the trick.
   •   Using a variable to predict another doesn’t denote causal relationships.
   •   Good data is hard to find and requires expensive research.
   •   Results from studies are done in aggregate, are average effects, and might not apply to everyone.
