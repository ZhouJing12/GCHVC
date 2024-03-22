Galactic Center High Velocity Clouds - Expansion of Galactic center outflow: FAST observation of HI high velocity clouds

1. FAST observation data (GCHVC_imcontsub.fits)

2. Convolve the FAST data using 3D gaussian kernel of (5,3,3). (convolve_image.ipynb)

3. Use DuChamp to search for high velocity clouds (|vlsr|>120km/s), the parameters are shown in InputExample file.

4. Select true clouds by some criteria and by eye. (select_subsample.ipynb)

5. Plot moment 0, 1, and spectral map. (draw_source.ipynb)

6. Compare FAST data and GBT data extracted from article pdf file. (compare_GBT.ipynb)

7. Generate biconical outflow model seen from sun location. (outflow_model.ipynb)
