# epl_fantasy_team

Building a fantasy EPL football team, by:
- Scraping xG and xA data from understat
- Combining yearly datasets to create a single data source
- Based on the historical performance, predicting xG and xA data for the upcoming year and relating that prediction to expected fantasy points
- Using PuLP (linear programming library) to build the team that, given the salary cap, most efficiently creates the most expected points
