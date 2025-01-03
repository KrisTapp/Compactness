This Repo contains the data and code used to create the plots and analysis in the paper "Revisiting Compactness for District Plans".
The files and folders are as follows.

weighted_recom.ipynb: contains all of the code, annotations and examples.  Start here.

THE NOTEBOOK USES THE FOLLOWING INPUT FOLDERS:

VTD_shapefiles: contains the census VTD shapefiles for the states we consider (NC, PA, OH, FL).  Filenames indicate the state's fips code.

Initial_assignments: contains initial seed maps for (NC, PA, OH, FL) for each of: congressional, upper state, lower state.  
The filenames begin with 'fips_k' where k is the number of districts.

AND THE NOTEBOOK WAS USED TO CREATE THE FOLLOWING OUTPUT FOLDERS
(in which filenames include 'fips_k')

dataframes_50K_ensembles: for [NC, FL]. Includes all of the scores for all of the maps in the ensembles.

dataframes_5K_ensembles: for [NC, FL, PA, OH]. We only ran 5K ensembles for PA and OH because of resource constraints.

Corr_tables: like table 1 of the paper

Plots: all plots of the paper and more.