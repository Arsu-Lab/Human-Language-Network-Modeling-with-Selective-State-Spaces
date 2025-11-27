# Human-Language-Network-Modeling-with-Selective-State-Spaces
Code for the paper "Human Language Network Modeling with Selective State Spaces".

# Setup
1. To run our code, first download the [data files](https://www.cs.cmu.edu/~fmri/plosone/files/) from the Original "Simultaneously uncovering the patterns of brain regions involved in different story reading subprocesses" (Wehbe et al 2014) study.
2. The current setup runs the models locally so please ensure you have sufficient computational resources.

# Running
- Use the file `mamba_gpt_fmri_pipeline.ipynb` to load the text and process it before getting model activations and correlating them with the fMRI data for each subject
- To skip to the results, `generate_plots.ipynb` allows the user to combine different brain ROIs and plot the weighted average correlation of different brain areas with the model activations. 
