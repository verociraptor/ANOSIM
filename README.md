# ANOSIM
# Language: Python
# Input file: TXT file (of filenames used)
# Ouput file: None 
# Tested with: PluMA 1.0, Python 2.7
PluMA plugins that calculates an ANOSIM test for two or more groups of samples based on a categorical factor. 

The plugin takes into input a txt file listing the filenames to be used, including a dissimilarity matrix in CSV format and a
listing of samples into their respective groups in CSV format. The plugin outputs the results of the test to the screen, 
including the p-value and test-statistic.