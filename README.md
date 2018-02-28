# Snowfalke mass retrievals 2014/2015
## Snow microphysical properties retrieved from PIP observations collected in Hyytiala on 2014-2015

The datafile is given in the Matlab format. The data structure contains snow_cm MAT structure with the following content
```
time: [1×3012 double]     - MAT time vector
DPIP: [3012×131 double]   - PIP diameter matrix, the PIP diamter is the disk equivalent diameter
PSD: [3012×131 double]    - measured snow particle size distribution (PSD) given as a function of DPIP
vel: [3012×131 double]    -  mean fall velocities of snowflakes
mass: [3012×131 double]   - retrieved particle mass
Dmax: [3012×131 double]   - measured particle maximum dimension
T: [1×3012 double]        - surface air temperature in deg. C
RH: [1×3012 double]       - relative humidity in %
N0_star_mass: [1×3012 double]  - N0* of the PSD. In this case the PSD is defined as a function melted drop diameter, N(Ddeq)
Dm_mass: [1×3012 double]       - mass weighted mean diameter of the PSD, N(Ddeq)
IWC_mass: [1×3012 double]      - Ice water content
PSD_Deq: [3012×131 double]     - The PSD defined as a function of the melt water diamter, N(Ddeq)
Deq: [3012×131 double]         - melt water diameter
```
The particle masses are retrieved using von Lerber et al. (2017) method. All variables should be given in cgs units. If you are using the data please cite:

von Lerber, A., D. Moisseev, L.F. Bliven, W. Petersen, A. Harri, and V. Chandrasekar, 2017: Microphysical Properties of Snow and Their Link to Ze-S Relations during BAECC 2014. J. Appl. Meteor. Climatol., 56, 1561-1582, https://doi.org/10.1175/JAMC-D-16-0379.1

## Questions
In case of any questions, please don't hesitate to contact Dmitri Moisseev: dmitri_DOT_moisseev_(AT)_helsinki_DOT_fi
