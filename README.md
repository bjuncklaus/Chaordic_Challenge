# Chaordic_Challenge
Repository for the Chaordic - Machine Learning Challenge which can be found [here](https://github.com/chaordic/machinelearning-challenge/blob/master/dswa-challenge.ipynb).

## Follow the steps below
You should have the dataset (provided by you via email). Please extract everything into a directory called `data`. You should end up with this structure:
```
+-- data
|   +-- clicks
|   	--- part-00
|				.
|				.
|				.
|   	--- part-36
|   +-- impressions
|   	--- part-00
|				.
|				.
|				.
|   	--- part-36
|   +-- pageViews
|   	--- part-00
|				.
|				.
|				.
|   	--- part-36
|   +-- transactions
|   	--- part-00
|				.
|				.
|				.
|   	--- part-36
```
Then you should run the following Jupyter Notebooks in order:
#### pickler.ipynb
This will reduce the memory usage for each dataset (ie. pageViews, clicks, impressions, transactions) by saving a `.pickle` file on the their respective directories.

*Note: You can see the the memory usage analysis done on the `memory_improvement.ipynb` notebook, which was the basis to extract all the necessary information for pickling.*

I recommend shutting down the notebook after pickling to reduce memory usage.
#### stats.ipynb
This is the notebook where all the statistics are presented. There are print statements as well as markdown descriptions describing the analysis.