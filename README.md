# SPRINT_analysis
SPRINT (Spatial Pseudotime Ranking in Tissues)is a tool that spatially maps pseudotemporal trajectories at single-cell resolution in situ with a simple computational workflow and single-round fluorescent imaging.

SPRINT involves three major steps: (i) computational analysis of a scRNA-seq dataset from your tissue of interest to select features (i.e., genes) whose expressions significantly co-vary with cell state transitions. It then assigns each of such genes to an imaging channel; (ii) a tissue preparation and imaging step that probes the abundance of selected genes in situ by capturing the integrated fluorescence intensities within each cell. (iii) a post-imaging analysis step that uses the information from (ii) to reconstruct a trajectory of cell state transitions in situ.

Before using SPRINT, users need to provide a scRNA-seq dataset. Multiple datasets on the same tissue can be used to select for a gene list that yields the best reference distribution. Once having the scRNA-seq dataset, users need to 
