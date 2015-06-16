# GalAlign
REU research for Maria Michell 2015 on galaxy alignments 

Goal of the project is to determine 1) if the brightest galaxies in clusters are similarly oriented in axis to the orientation of the galaxy cluster (previous results indicate this) 2) if this relation exists at higher redshifts 3) how this relationship extends or does not extend to fainter galaxies in the cluster.  The extension of alignment to further redshifts is scientifically interesting for galaxy cluster evolution theories.  Perhaps mergers along an axis/filament of the cluster imprints a preferred axis of orientation for the cluster.  Or, perhaps the large central galaxy is torqued to become aligned with the cluster axis/filament over time. This could be examined by looking for evidence that larger galaxies torque smaller ones. It was also noted that our conclusions could be compared to preferred orientations of satellite galaxies. 

Data were acquired from Clash survey (archive/stcsci.edu/prepds/clash) and was estimated to be of about 20 galaxy clusters.  Data were sampled from the red sequence to prevent inclusion of foreground/background galaxies.  Though redshift is a superior measure for cluster inclusion, this information was not available for all galaxies. De Propris performed the sampling and the estimation of the position angles of the galaxies in the data set he sent me on 6/5/2015 via email correspondence. I’m not sure what the errors are on the red sequence sampling method or the position angle fitting method. 

Data received have been previously been analyzed with galfit (iraf?) to determine position angles (from -90 to 90, unclear exact orientation of the angles given) though it was noted that for some galaxies galfit failed to produce an orientation axis so the ellipse function in iraf should be used due to its ability to mask regions. Position angles are given in the R band. 

The general outline of the steps to complete the project: 
Acquire PAs for galaxies which do not have one listed via ellipse in IRAF
Look up redshift data for the galaxies that have it available
Determine orientation of a galaxy cluster
Two methods were given: 1. moments of inertia calculation to find principal axis and 2. Xray gas as a tracer (similar to MACS database)
Compare that position angle (PA) to that which is listed as the PA of the brightest member galaxy as found by de Propris (previous research supports this)
 Select a statistical method to compare the cluster PA with fainter member galaxy PAs as given by de Propris to see if the orientations are random or if there is a preference
Investigate the PAs as a function of redshift (perhaps there hasn’t been enough mergers at this point to create a preferred direction?)
Look at filaments with neighboring clusters and see if they influence orientation
Repeat for other clusters
Repeat for the composite cluster

