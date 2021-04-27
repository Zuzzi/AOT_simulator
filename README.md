# AOT_simulator
A simulator for calculating stats in a new Attack On Titan board game project.
The main script is AOT_simulator, which simulate n fights between different kind of titans (defined in the same file).
Both raw results and aggregate stats of the simulations are saved as pickle files.
The second script, AOT_join, merges all the aggregate stats of the pickle files to generate a heat map of the win rate of each titan against the others.
For an easy visualization, it saves the heat map as a html file, together with the aggregate stats of each fight.
