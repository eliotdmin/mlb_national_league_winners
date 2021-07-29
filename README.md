I trained a neural network on data from 1995-2015 to predict winners of the National League in Major League Baseball from 2016-2020. Using fielding percentage (FP), stolen bases (SB), walks (BB), hits (H), home runs (HR), earned run average (ERA), runs (R), doubles (X2B) and tribles (X3B) as inputs, my model was able to correctly predict each national league winner from 2016-2020 with the exception of the 2019 Washington Nationals, whose 2019 championship is well-documented as a statistical anomaly.

The data was taken from Sean Lahman's 'Teams' database. I preprocessed the data in R before shipping it for use in python.

<img width="1174" alt="Screen Shot 2021-07-29 at 10 57 00 AM" src="https://user-images.githubusercontent.com/60484287/127541764-ead142f9-9607-4b91-80a9-23bedf36f8e6.png">
