# Bank-Market-Strategy

Phone calls are one of the most comment bank marketing strategy. The marketing department makes hundreds of calls every single day, but every call has its cost. Therefore, call the right people at right time will increase the response rate and help the bank decrease the marking expense. To find the 'right people' and 'right time', we explore the dataset from [UCI Machine Learing Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#).

## Business Understanding
This dataset contain three kinds of information: demographic info, contact info and economic info. To make the most efficient call, we can utilize the dataset to answer 3 questions below.

  - What kind of people are more intended to become our customer?
  - Does it worth spending a long time talking with the same people?
  - At which time slot, will marketing calls have a higher success rate?
  
## Data Understanding
UCI proveides detailed descriptions, which in [Data Info Page](https://github.com/jackie-sun7/Bank-Market-Strategy/wiki/Data-Info).

## Prepare Data
Train test split.
<br>Check the null and distribution of data, then use `np.where` or `np.cut` to bin the numerical variable. 
<br>Delete the columns which have risk of information leakage.

## Data Modeling
Use Random forest to fit the model. Check accuracy and feature importance.

## Evaluate the Results

 - Juniors and elders are more inclined to accept market campaigns.
 - Long contact duration and low frequency is a strategy to gain customers.
 - Extreme economic condition is a great marketing opportunity.

All of EDA charts are in output folder and detailed analysis at [Github wiki page](https://github.com/jackie-sun7/Bank-Market-Strategy/wiki/Bank-Market-Strategy-Data-Analysis).

## Package 
`pandas`, `numpy`, `matplotlib`, `sklearn`
