# SAMIAssignment

Hello! This is where I'm updating changes to the code.
Please, feel free to download it and try and play around with it, or skim through - most of it is just me playing around with the data.

# Reading the Data

Here is a summary of the data you'll see in `FJR.csv` and `FJR_withAGE.csv`

| CATID | ellip | z_spec | Mstar | M_r | r_e | VSIGMA_RE | VSIGMA_RE_ERR | SIGMA_RE | SIGMA_RE_ERR | TYPE | Age_RE | Age_RE_ERR | SFR_RE | SFR_RE_ERR |
|-------|-------|--------|-------|-----|-----|-----------|---------------|----------|--------------|------|------|------|------|------|
| Galaxy ID  | Eccentricity of the Galaxy | Redshift | Galaxy Mass (log Solar Masses) | Magnitude in R-Band (mag) | Effective Radius (arcsec) | V/σ. Low number (< 0.2 ish) means non rotating | V/σ Error | Velocity Dispersion σ | Velocity Dispersion Error | Galaxy Type. 0=Ellipse; 0.5=Maybe Ellipse | Galaxy Age (Gyrs) | Galaxy Age Error (Gyrs) | Star Formation Rate (Msun/yr) | Star Formation Rate Error (Msun/yr) |


# The Different .ipynb's
`SAMIAssignment.ipynb` is where I will be running the actual code for the assignment. <br>
`Fits.ipynb` is where I read and produce plots of the .fits files. The images can be found in the `/fitsfiles` folder. <br>

# The Different Files
`Query.csv` is the uncleaned data used for the assignment. <br>
`FJR.csv` is the cleaned data used for the assignment. <br>
`FJR_withAGE.csv` is the cleaned data used for the assignment with Galaxy Age and Star Formation Rate Information. <br>
<br>
Note: the reason these two .csv's are seperated is because the data is cleaned in seperate ways. <br>

# The Different Folders
`/plots` is where I save all my graphics generated from the `SAMIAssignment.ipynb`. <br>
`/fitsfiles` is where you can find the .fits files and related images. <br>
`/readings` is where you can find and put readings relevent to the assignment. <br>
