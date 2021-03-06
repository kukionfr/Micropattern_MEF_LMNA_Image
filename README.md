# Fluorescence image of Mouse Embryonic Fibroblast(MEF)

These images are for Nature Protocol paper (2020): 
*A robust unsupervised machine learning method to quantify the morphological heterogeneity of cells and nuclei* 

Dataset Size: 2.37GB (Download time ~12min @ 100Mbps)

Number of cells: 15661\
Number of nuclei: 15661

MEF cells are seeded on Circle and Triangle micropattern coated with Fibronectin. Control group cells are seeded on cell culture surface without any micropattern.

Exact method of micropatterning is described in this paper: 
Hale, Christopher M., et al. "SMRT analysis of MTOC and nuclear positioning reveals the role of EB1 and LIC1 in single-cell polarization." Journal of cell science 124.24 (2011): 4267-4285.

MEF cells with(++) and without(--) Lamin A knockout are stained with DAPI and Phallodin. Image filename with "c1" tag is phallodin channel, and "c2" tag is DAPI channel.

Analysis time estimate using i9-10900k cpu:\
Building model: 19 sec\
Applying model: 21 sec\
