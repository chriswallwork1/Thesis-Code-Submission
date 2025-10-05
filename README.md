All model variants were run in the Julia programming language. Data was obtained using Python. All runnable code is provided as Jupyter Notebooks.

"Risk Free Rate.ipynb" contains the Python code to determine the risk-free rate from 1 January 2015 to 31 December 2024.

"Simulation Study.zip" consists of:

    • "Fetch Simulation Data.ipynb", which sources the four assets' (LLY, JPM, KWR, DIN) daily returns from 1 January 2015 to 31 December 2024.

    • "Y_sim.csv", which contains these daily returns.

    • "G-4 Data Generation.ipynb", which runs the G-4 model to obtain the data-generating parameters used to simulate the datasets.

    • For each model used in the simulation test (EW, ν-1000-NP, G-NP, G-4, G-2, G-1), there exists a "<model name> sim.csv" which contains the code to run that model, "<model name> summary.csv" which contains the final portfolio balance for each of the 25 indpendent simulation tests, and a folder titled by the model's name, which contains the daily progression of the: (i) portfolio balance, (ii) transaction costs paid, and (iii) portfolio weights, for each of the 25 independent simulation tests. 

"Empirical Analysis.zip" consists of:

    • "Fetch Empirical Data.ipynb", which sources the ten assets' (AEP, APD, C, MCD, MMM, SLB, TRI, UNH, WIT, WMT) daily returns from 1 January 2015 to 31 December 2024, as well as the 504 trading days (2 January 2014 to 31 December 2014) preceeding this window.

    • "Y_full.csv", which contains these daily returns.

    • For each model used in the empirical analysis (EW, t-NP, ν-NP, G-NP, DS-HDP-HMM, Sticky HDP-HMM, HDP-HMM, t-4, t-2, t-1), there exists a "<model name>.csv" which contains the code to run that model, and "<model name>.csv" which contains the daily progression of the: (i) portfolio balance, (ii) transaction costs paid, and (iii) portfolio weights, for that model.
