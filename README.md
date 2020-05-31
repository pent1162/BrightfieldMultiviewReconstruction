
Example code for Brightfield Multiview Reconstruction as described in Calisesi et al. ----- (2020)

The code reconstructs a single section (y) of a sample acquired in brightfield mode from multiple views.

The data should be ordered (resliced after multi-view acquisition) in the following order:
                                [angles, z, x]
                                
Please read Calisesi et al. for details on acquisition and on the coordinates definition.  

In order to reconstruct a full 3D sample, the code should be run section by section 
or could be modified to take into account 3D multiview stacks. Please contact
the corresponding author if you need help in performing this step. 

Required dependencies are included in Anaconda, except for tqdm that can be installed with pip.