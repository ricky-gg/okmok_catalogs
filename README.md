# okmok_catalogs

Repository for the seismic catalogs from Garza-Giron et al. (submitted). These include the catalog with absolute locations using NonLinLoc (Lomax et al., 2001; Lomax and Curtis, 2001), and the relocated catalogs using hypoDD (Waldhauser and Ellsworth, 2000) and GrowClust (Trugman and Shearer, 2017).


The header of the CSV files is as follows:

Date (year/month/day),
Time (hr:min:sec:msec),
Latitude (decimal degrees),
Longitude (decimal degrees),
Depth (km), 
Magnitude (Ml calculated for this study),
Event_type (VT:vulcano-tectonic;LP:long-period),
Number of stations where the event was detected,
ID



References:
Lomax A, Curtis A (2001) Fast, probabilistic earthquake location in 3-D models using oct-tree importance sampling. Geophys Res Abstracts, 3:955. 
Lomax, A., Zollo, A., Capuano, P., and Virieux, J. (2001). Precise, absolute earthquake location under Somma‐Vesuvius volcano using a new 3D velocity model.Geophysical Journal International,146, 313–331
Trugman, D. T., and Shearer, P. M. (2017). GrowClust: A hierarchical clustering algorithm for relative earthquake relocation, with application to the Spanish Springs and Sheldon, Nevada, earthquake sequences. Seismological Research Letters, 88(2A), 379-391.
Waldhauser, F., and Ellsworth, W. L. (2000). A double-difference earthquake location algorithm: Method and application to the northern Hayward fault, California. Bulletin of the Seismological Society of America, 90(6), 1353-1368.
