# Recommend_system
These are some algorithm about recommend movie

Now there are three algorithm:

### 1. Item-based collborative filtering
* ICF predict ratings
* ICF topN recommend

### 2. Latent factor model
* LFM predict ratings
* LFM topN recommend
  
### 3. Recommend movie base on movie's genre

## Dataset
We use data set of MovieLens which contain 100000 ratings from 3000+ users on 650 movies

We can see that most of the ratings are greater than 2. And popular movies have higher average rating.
<img src="rating_count.png" width=300 height=200>
<img src="rating_people.png" width=500 height=200>


## Item-based collaborative filer
First method is ICF. We try different metrics to compute the nearst neighbours.We use Pearson,jaccard,IIF and also consider time. And finally we recommend 6 movies to users. Then computer how much movie apppear in test set and the ratings are greater than 2. These are the outcome.
<div align=centre><img src="ICF_precision.png" width=300 height=200><img src="ICF_recall.png" width=300 height=200></div>
<div align=center><img src="ICF_Fscore.png" width=300 height=200><img src="ICF_coverage.png" width=300 height=200></div>

## LFM
Use LFM to computer recommend list. We do research on the relation between #classcount, ratio and precision,recall,Fscore,Coverage.
<div align=centre><img src="LFM_classcount.png" width=300 height=200><img src="ICF_recall.png" width=300 height=200></div>



