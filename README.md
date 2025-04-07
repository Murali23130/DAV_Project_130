# DAV_Project_130

This project involves the analysis of a dataset using the powerful data manipulation and numerical computation libraries in Python: **NumPy**, **Pandas**, and **Matplotlib** for data visualization.

---

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x  
- Numpy (`pip install numpy`)  
- Pandas (`pip install pandas`)  
- Matplotlib (`pip install matplotlib`)  

---

## Operations Performed

### NumPy

- **Array Creation**: `np.array()`, `np.zeros()`, `np.ones()`, `np.arange()`, `np.linspace()`
- **Array Manipulation**: `.shape`, `.reshape()`, `np.concatenate()`, `np.split()`
- **Mathematical Operations**: Element-wise operations (`+`, `-`, `*`, `/`), `np.sin()`, `np.cos()`, `np.sqrt()`
- **Linear Algebra**: `np.dot()`, `np.linalg.solve()`, `np.linalg.eig()`
- **Statistical Functions**: `np.mean()`, `np.median()`, `np.std()`

### Pandas

- **Inspection**: `head()`, `tail()`, `info()`, `describe()`, `dtypes`
- **Selection**: `df['col']`, `df[['col1', 'col2']]`, `.loc[]`, `.iloc[]`, conditional selection
- **Cleaning**: Handle missing values (`isnull()`, `dropna()`, `fillna()`), duplicates (`duplicated()`, `drop_duplicates()`), column renaming
- **Aggregation**: `mean()`, `sum()`, `count()`, etc.

### Matplotlib

- **Basic Plotting**: `plt.plot()`, `plt.scatter()`, `plt.bar()`
- **Customization**: `plt.title()`, `plt.xlabel()`, `plt.ylabel()`, `plt.legend()`, `plt.grid()`
- **Subplots**: `plt.subplot()`
- **Saving Figures**: `plt.savefig('filename.png')`
- **Showing Plots**: `plt.show()`

---

## Dataset Description

The `IPLPlayerAuctionData.csv` dataset provides information about cricketers participating in the IPL auction. It includes the following attributes:

- **Player**: Name of the cricketer  
- **Role**: Player’s role (e.g., Batsman, Bowler, All-Rounder, Wicket-Keeper)  
- **Amount**: Auction amount the player was sold for  
- **Team**: IPL team that bought the player  
- **Year**: Year of the auction  
- **Player Origin**: Country or origin (India or Overseas)  

---

## Key Findings

- The dataset contains **88 records** with **6 columns**.
- The most frequent role is **All-Rounder**, followed by **Bowlers**.
- Some players command **significantly higher auction amounts**, skewing the average.
- Teams like **Mumbai Indians**, **Chennai Super Kings**, and **Royal Challengers Bangalore** frequently appear.
- The **majority of players are from India**, but **high-value players are often from overseas**.
- **All-Rounders often fetch higher bids** compared to other roles.

---

## Insights from Visualizations

- **Bar Plot**: Number of Players by Role  
  - Highlights role demand and team strategy.

- **Box Plot**: Auction Amount by Player Role  
  - Visualizes median and outliers for each player type.

- **Violin Plot**: Amount by Player Origin  
  - Shows distribution and spread; overseas players show higher price variance.

- **Pie Chart**: Player Distribution by Team  
  - Illustrates team-wise player acquisition share.

- **Line Plot**: Average Auction Amount over Years  
  - Reveals spending trends if multi-year data is available.

- **Histogram**: Distribution of Auction Amounts  
  - Displays skewness and most common price brackets.
