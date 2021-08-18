# IRIS - 1.0.0 - Complete Rewrite And Real World Test

In 1.0.0, the goal is to have a fully functioning version of IRIS with creating, training, running, saving, and loading a neural network. The idea behind multiple scripts in the previous version was to organize functions for serialization and controlling the neural network. The drawback is that it introduces problems between scripts and problems with communication when creating, loading, or training a bot as the scripts are running at the same time and can't communicate the way I want. This version goes back to one big script for the purposes of actually being able to complete the project, or at least this iteration of it.