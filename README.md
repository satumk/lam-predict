# Aim of this project:

Show one case of how machine learning predictions handle when the data changes
in a clear way.

# Data

LAM-data gathered from: https://aineistot.vayla.fi/lam/reports/LAM/
Reports from several points were gathered, preprocessed and analysed using 
XX algoritm. First the learning data was jan-march 2020 and the first 2 weeks
of March was predicted. In the next phase the learning data was jan to 
mid-march 2020 and the second half of march datapoints was predicted. A new
prediction was made every two weeks always adding the real data for the 
previously predicted weeks to be part of the learning data and predicting the 
next two weeks. The final prediction was for the last part of May 2020.

# Author

Satu Korhonen
