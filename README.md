# DAV_Project_130
This project involves the analysis of a dataset using the powerful data manipulation and numerical computation libraries in Python: NumPy and Pandas.Data Visualistaion by using Matplotlib.
# Getting Started
Prerequisites
Python 3.x
Numpy (pip install numpy)
Pandas (pip install pandas)
Matplotlib (pip install matplotlib)
Operations
NumPy:

Array Creation: np.array(), np.zeros(), np.ones(), np.arange(), np.linspace()

Array Manipulation: array.shape, array.reshape(), np.concatenate(), np.split()

Mathematical Operations: Element-wise operations (+, -, *, /), np.sin(), np.cos(), np.sqrt()

Linear Algebra: np.dot(), np.linalg.solve(), np.linalg.eig()

Statistical Functions: np.mean(), np.median(), np.std()

Pandas

Inspection: head(), tail(), info(), describe(), dtypes

Selection: df['col'], df[['col1', 'col2']], loc[], iloc[], conditional selection

Cleaning: Handle missing (isnull(), dropna(), fillna()), duplicates (duplicated(), drop_duplicates()), rename columns

Aggregation: mean(), sum(), count(), etc.

Matplotlib:

Basic Plotting: plt.plot(), plt.scatter(), plt.bar()
Customization: plt.title(), plt.xlabel(), plt.ylabel(), plt.legend(), plt.grid()
Subplots: plt.subplot()
Saving Figures: plt.savefig('filename.png')
Showing Plots: plt.show()
# Dataset Description
The IPLPlayerAuctionData.csv dataset provides information about cricketers participating in the IPL auction. It includes various attributes such as:

Player: Name of the cricketer

Role: Player’s playing role (e.g., Batsman, Bowler, All-Rounder, Wicket-Keeper)

Amount: Auction amount the player was sold for

Team: IPL team that bought the player

Year: Year of the auction

Player Origin: Country or origin (India or Overseas)

# Key Findings :
The dataset contains 88 records with 6 columns.

The most frequent role in the dataset is All-Rounder, followed by Bowlers.

The highest auction amount recorded is significantly higher than the average, suggesting a few players command premium values.

Teams like Mumbai Indians, Chennai Super Kings, and Royal Challengers Bangalore appear multiple times, indicating active participation in auctions.

The majority of players are from India, though some high-value players are from overseas.

There is a noticeable variation in the amount paid based on the player role, with All-Rounders often fetching higher bids.

# Insights from Visualizations :
Bar Plot: Number of Players by Role

Helps identify the demand for different roles during auctions.

Can be used by team managers to spot market saturation or gaps.

Box Plot: Auction Amount by Player Role

Shows median and outliers in bidding for each player type.

Useful to spot undervalued or overvalued roles.

Violin Plot: Amount by Player Origin

Combines distribution and statistics; shows how Indian and Overseas players are priced.

Indicates that Overseas players often have higher variability in auction prices.

Pie Chart: Player Distribution by Team

Shows what percentage of players were bought by each team.

Useful for understanding team strategy.

Line Plot: Average Auction Amount over Years

If multiple years exist in the dataset, this shows trends in auction spending.

Helpful for assessing inflation or investment trends in IPL auctions.

Histogram: Distribution of Auction Amounts

Reveals the spread and skewness in player prices.

Indicates whether most players are in a certain price bracket.
