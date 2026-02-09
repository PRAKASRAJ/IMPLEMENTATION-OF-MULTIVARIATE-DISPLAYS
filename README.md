Experiment 6: Implementation of Multivariate Displays
Introduction Multivariate data visualization plays a crucial role in AI analytics by enabling the analysis of relationships among multiple variables simultaneously. Unlike simple two-dimensional plots, multivariate displays help uncover complex patterns, correlations, and trends that are not easily observable otherwise.
This experiment focuses on implementing key multivariate visualization techniques using R to analyze retail business data.
Objective
To understand the importance of multivariate displays in data analysis
To visualize relationships among Sales, Profit, Discount, Region, and Customer Segment
To interpret insights from different visualization techniques
 
Tools Used
R Programming
RStudio
ggplot2
GGally
dplyr
 
Dataset Overview The dataset contains retail transaction information with the following variables:
Order_ID – Unique order identifier
Region – Geographic region of sales
Product_Category – Category of the product
Sales – Sales amount
Profit – Profit earned
Discount – Discount applied
Customer_Segment – Type of customer
Visualization Techniques Implemented
Parallel Coordinates Plot This plot was used to visualize multiple numerical variables together. Each data record is represented as a line crossing parallel axes. It helps in identifying inverse relationships, trends, and outliers across customer segments.
Bubble Chart (Sales vs Profit) A bubble chart was used to represent Sales and Profit, with bubble size indicating Discount and color representing Region. This visualization helps in understanding how discount levels impact profitability across regions.
Trellis Display (Faceted Scatter Plots) Trellis displays were created by faceting Sales vs Profit plots based on Region. This method simplifies complex data by breaking it into smaller, comparable subsets, making regional performance patterns easier to observe.
Observations and Insights
Higher discount levels generally showed a negative impact on profit
Sales and Profit relationships varied significantly across regions
Customer segments behaved differently under similar sales conditions
Faceting helped isolate and compare regional trends effectively
Limitations
Overlapping points in dense regions reduce clarity
Bubble size comparison is visually less precise
Interpreting multiple variables simultaneously requires higher cognitive effort
Conclusion Multivariate displays provide powerful insights into complex datasets by allowing simultaneous analysis of multiple variables. The techniques implemented in this experiment are highly useful in exploratory data analysis, AI model evaluation, and decision-making processes.
Repository Contents
R source code
Retail business dataset
Output visualizations
README.md
 
