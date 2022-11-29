# Module14

My conclusions about the performance of the baseline trading algorithm:
Judging by plot given in bokeh_plot.png we can say that baseline strategy works better than actual returns. Strategy increases the income from 1.32 to 1.62.

Step 1: Tune the training algorithm by adjusting the size of the training dataset.
After increasing the training dataset size from 3 to 48 month the rusulting income decreased from 1.62 to 1.34.

Step 2: Tune the trading algorithm by adjusting the SMA input features.
Changing windows widths
short_window = 4 -> 3
long_window = 100 -> 50
increased the income from 1.62 to 2.04

Step 3
Best set of parameters is shown at best_bokeh_plot.png

New Model

Using LogisticRegression decreased the perfomance from 1.62 to 0.89, which is shown at lr_bokeh_plot.png. This is worse than any configurtion of algorithm above.