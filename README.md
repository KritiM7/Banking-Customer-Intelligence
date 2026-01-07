# Banking Customer Intelligence

Modern banks don't just store money, they manage relationships. The goal of this analysis was to move beyond basic demographics and understand the financial "DNA" of a customer base. I wanted to find out how income, occupation, and nationality influence the adoption of high-value products like credit cards and business lending.

The Analytical Workflow:
I structured the analysis to mirror a real-world business intelligence task:

Financial Feature Engineering: I categorized  "Income Band" into Low, Medium, and High bands using custom bins to create more readable segments for marketing teams.

Customer Tiering: I analyzed the distribution of Loyalty Classifications to understand the concentration of high-net-worth individuals.

Bivariate Exploration: I conducted in-depth analyses to examine the correlation between occupation and nationality and the number of credit cards a customer holds, identifying which demographics are considered "heavy users".

Correlation Mapping: I generated a 10x10 heat map to identify strong relationships between different financial products, such as the high correlation (0.84) between Bank Deposits and Checking Accounts.

Executive Insights
Skewed Financial Distribution: Univariate analysis revealed that most customer financial products (Savings, Loans, Business Lending) are heavily right-skewed, meaning a small percentage of "power users" drive the majority of the bank's volume.

The "Associate Professor" & "Account Coordinator" Segments: My analysis of the top 5 occupations showed that while Associate Professors have a high frequency of holding 1 card, Human Resource Managers showed a unique propensity for holding 3 cards simultaneously.

Regional Product Affinity: European customers showed the highest density of card ownership, while Asian and American groups represent significant "growth opportunities" based on their current distribution.

Technical Toolkit:
Python: Used for the heavy lifting of data cleaning and binning.

Pandas & NumPy: For complex data manipulation and statistical summaries.

Seaborn & Matplotlib: Created custom Countplots, Histograms, and Heatmaps to turn raw numbers into visual stories.
