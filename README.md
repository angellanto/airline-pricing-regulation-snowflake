# Strategic Analysis for Airline Pricing Regulation
## Snowflake Dashboard: https://app.snowflake.com/sfedu02/xob39151/#/airline-pricing-analysis-d68VpYGaF
## Slide Deck: https://www.canva.com/design/DAGlWurasTw/sbGWMh8_X5yQw3vjaRgSWw/view?utm_content=DAGlWurasTw&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h89b5248fe2
### Business Challenge III | Team Assignment Grade:
### Professor Comment: 
Thank you Team4 for your submission, well done!
Overall, very strong submission, although lacking a bit of details on the intervention strategy part. Unique slide design with clear structure of the challenge, well done. You clearly considered the user experience (UX) of the developed streamlit dashboard, great! Excellent initiative in requesting write access in Snowflake to build the streamlit dashboard, shows ownership and problem-solving. 
Areas for improvement
- The solution should highlight more clearer the intervention strategy part, clearly grounded in the insights derived from your analysis
 - Well developed dashboard, great work on that one, a few reflections:
1. What key decisions can stakeholders make based on this dashboard? Who is using it and how?
2. For the daily pricing alert trends, how should users interpret and respond to this information?
3. The Longitudinal Alert Tracking is a valuable addition, what specific value does it provide in practice?
- The Vulnerability Hotspots visualization is clear and impactful—great work.
- In the Market Structure Impact slide (correlating competition levels with flagged activity), the approach is interesting. Consider: clarifying in the title that “> 100 flights” is a selection criterion.  Improving the legend terms like “competing carrier” could be clearer.
Thank you Team4, great job!
### Assignment Instructions: 
Description of Assignment:
Strategic Analysis for Airline Pricing Regulation
You are working as part of a consulting team in a leading international consulting firm, advising an aviation authority on how to monitor and respond to unfair airline pricing practices. Your client is preparing to develop a policy framework and needs strong, data-backed insights to support interventions.
You’ve been given access to a large-scale flight dataset with over 80 million rows, including detailed fare, seat availability, route, timing, and airline information. Your goal is to uncover patterns, detect potential pricing anomalies, and formulate an intervention strategy that could inform future regulation.
Airline Perspective – Understanding Dynamic Pricing Models
From the perspective of the airline, you are encouraged to identify and better understand pricing models that may include (but are not limited to):
• Last-minute pricing: Are prices increasing when time between search and flight is low?
• Demand-based pricing: Do fares rise when SEATSREMAINING is low?
• Route-based pricing: Are some airports or routes consistently more expensive due to limited availability or popularity?
Put yourself in the shoes of airline revenue managers — what pricing logic might they be applying? What would be a reasonable dynamic pricing model? What patterns would you expect from a well-functioning system, and what might indicate unfair or manipulative behavior?
Aviation Authority Perspective – Monitoring, Dashboard & Strategy
From the regulatory side, your task is to:
• Investigate pricing anomalies, such as cases where TOTALFARE is significantly higher than BASEFARE without clear justification
• Examine pricing progression over time, especially looking at SEARCHDATE vs FLIGHTDATE
• Identify routes or airlines with high variance or sharp pricing spikes
• Develop a monitoring dashboard (e.g., in Tableau, Looker Studio, or Power BI) that shows:
• Pricing changes by airline over time
• Base fare vs. total fare differences
• Search behavior patterns and demand indicators
• Sudden fare spikes, low seat availability, or last-minute anomalies
• Use insights to propose targeted intervention strategies, such as transparency requirements, audit triggers, or pricing fairness thresholds
• Reflect on the practical limitations of airline regulation (e.g., data access, jurisdiction, airline autonomy) and what kinds of intervention are realistically feasible
4) Presentation:

Prepare a 10-minute presentation that includes:

An overview of the business problem and its importance
A walkthrough of the core insights from both perspectives aviation authority and airline perspective
Introduction of key elements of the target intervention strategies
Allocate 5 minutes for Q&A with the audience
