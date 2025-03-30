# NBA_Outlier_Analysis

In the following analysis, I attempted to find the outlying performances of players in the modern NBA. To do so, I have used the following methods/algorithms:
- Elliptic Envelope
- Local Outlier Factor
- SVM
- Isolation Forest

I tried to find outliers in the following feature combinations:
- Effective field goal percentage (eFG%)  => following feature combinations that will be analyzed (FG vs eFG%) & (PTS vs eFG%)
- True shooting percentage (TS%) => following feature combinations that will be analyzed (FG% vs TS%) & (PTS vs TS%)
- Player efficiency rating (PER) => following feature combinations that will be analyzed (G vs PER) & (GS vs PER)
- Field Goal & PTS => (FG vs 2P) & (FG vs 3P)
- After update => dimension reduction applied to all features, only offence features and only defence features to detect outliers on a larger scale

The data was gathered from FBref with the pandas HTML function and a web scrapper, which I created. 
