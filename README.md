# PredictingNFLwinners
A markdown showing the data munging, model design, evaluation, and validation of a tree based model to predict the outcome of NFL games against the spread.

To follow the data science thought process and corresponding data processing pipeline: 

1.    **DataProcessing.Rmd** shows the following steps:
      a.    Where to find and how to download NFL player stats from 1950 to 2017
      b.    How to convert this to team stats
      c.    How to calculate the stat differential (home stats - away stats) for each game
      d.    How to calculate the rolling average over the last 5 games for each team
2.    **DifferentialStats.tsv** is the final output from **DataProcessing.Rmd** and should be used to build the model.
3.    **NFLwinnerModelBuildingPart1.Rmd** is the first attempt to build a model to predict winners.  
