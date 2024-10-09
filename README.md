# CI2024_lab1
Computational Intelligence Course at PoliTO - First Laboratory - Set Cover Problem  

`set-cover-approaches.ipynb` contains the approaches analyzed in order to decide how to tackle the problem in general. Many options were discarded and mainly the interesting results were left.

The problem in its different sizes has been instead solved in `set-cover-all.ipynb`. The approach chosen is simulated annealing with constant temperature for most instances, except for the first one, for which I decided to implement a tabu search with possibly single/double/multiple tweaks (the results were poor for each one, so I just kept the single/double as it was much faster).

Dragos-Constantin Buhnila --- 9/10/2024
