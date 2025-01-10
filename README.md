<h1>Forecasting Sockeye Salmon runs with Kolmogorov Arnold Networks</h1>
<a href  = "https://www.garrettstreit.com/white-paper"> Project White Paper</a>

# Code

<p>GetData.ipynb: retrieves water temperature and tide data for Nikiski, Alaska.

MLP.ipynb: trains a basic MLP on the explanatory factors and fits model to fish inflows for most recent year of 2024.

KAN.ipynb: trains a variant of the most optimal KAN architecture and fits model to fish inflows for the most recent year of 2024.

Results.ipynb: builds approximately 300 KANs and MLPs using a stochastic process. Trains each model and stores results in Results.csv.

resultAnalysis.Rmd: Provides summary statistics and regression analysis on Results.csv file. </p>
# Data
<p>
TempData.csv: Water temperature data for Nikiski, Alaska. obtained from NOAA.

TideData.csv: Tide data for Nikkiski, Alaska. obtained from NOAA.

FishCountsKenai.csv: Daily fish count data for the Kenai River. Obtained from the Alaska Department of Fish and Game.

FishCounts.xls: Daily fish count data for the Kasillof River. Obtained from the Alaska Department of Fish and Game. 

MergedData.csv: The merged data from TempData.csv, TideData.csv, FishCountsKenai.csv, and FishCounts.xls

mlpData.csv: Same as the merged data but includes lagged variables, and time invariant fixed effects.

Results.csv: includes data on each trained models architecture, and its error. Generated from Results.ipynb. 
</p>
