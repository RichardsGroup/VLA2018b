# VLA2018B

This repository serves as a database for all (primarily Trevor's) work done for Richards et al. 2021: "Probing the Wind Component of Radio Emission in Luminous High-Redshift Quasars".  The structure of the repository is described below.

* ``Bokeh/`` contains notebooks to make all Bokeh plots made along the way: t-SNE2 space, CIV distance with images animated in
* ``DriveImages/`` contains PNGs of all our VLA targets
* **Update** ``FITS_Images/`` contains the final FITS images of all our VLA targets and a ``.tgz`` file with all images
* ``ForcedPhotometryImages/`` contains example ``.jpg`` NVSS images from our forced photometry analysis.  Images are broken up into sources with luminosity above the FIRST detection limit and above where the AGN is expected to dominate radio (L1.4 > 10^24.45 W/Hz; Figure 2)
* ``Notebooks/`` should contain all of the useful notebooks that went into the paper.  Although it's possible I forgot to transfer some important ones from my personal machine, so let me know if there's something you can't find.
    * ``CIVPlot/`` includes notebooks that make the CIV plot -- both new and old.  The final important one is ``CIVPlot_wLOFAR_final_finalCIVdist.ipynb``
    * ``RandomDataAnalysis/`` includes notebooks that maybe aren't so useful anymore, but nevertheless contain plots of our data that are probably worth keeping
    * ``Stacking/`` contains the notebook to stack our non-detections and all the materials needed to do it
    * ``TSNE/`` includes some interesting work on the t-SNE analysis of the experimental 6-component ICA on our parent sample of DR7 quasars -- the original "PGv2", deterministic t-SNE, 3-D t-SNE (and rotating it to maximize range in FIRST/CIV distance)
    * There are a few other self-explanatory standalone notebooks without a subdirectory.  Note that the ``MakeFigures_forPaper.ipynb`` is from the first submission
* ``PaperFigures/`` contains all figures in the paper
* ``Text\ Files\ with\ walkthrough/`` contains my personal notes for processing each image in CASA
* ``data/`` *should* contain all the data needed to run the notebooks in this repo, but let me know if something looks to be missing
    * ``CIV_RM_data/`` contains files needed for the CIV plot notebooks
    * ``MK2021/`` contains data from McCaffrey, Kimball et al. 2021: "Kpc-scale Radio Structure in z~0.25 Radio-Quiet QSOs"
    * ``Nyland2020/`` contains Nyland QSOs with known SDSS redshifts and which have CIV (z~1.55-4.6)
    * ``PGv2_DR7/`` contains mostly files related to the original VLA2018b proposal created by GTR.  Most files are used in the PGv2 notebooks.
* ``table_for_paper/`` contains files to make the big LaTeX table in the paper.
