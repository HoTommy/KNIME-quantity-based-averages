# knime-workflow-hub
contains Knime Workflows and Components to realize data operations for businesses

# project overview
## 01 aggregated weight-based year average features
by connecting two or more data tables features (i.e. quantities in good receipts) can be assigned to a meta data entity by matching keys. on base of every entry aggregated values for the features can be calculated. finally, for the meta data entity (weight-based) averages for specific time slots can be calculated
{workflow with test data (csv) // table export // no visualization)

## 02 illustrating outlier calculation mathematically
using the k-parameterized R InterQuartil Range (IQR) (first-third quartil)
R = [Q1 - k(IQR), Q3 + k(IQR)] with IQR = Q3 - Q1	and k >= 0
outliers in small data sets are hard to detect. Implementing another approach with a k=3 k-Means cluster helps to resolve this "issue".
