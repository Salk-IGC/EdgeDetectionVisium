# EdgeDetectionVisium

This repo is no longer being maintained. Please see SingleCellTools (https://github.com/gevensen95/SingleCellTools) for the most
up-to-date version, plus more functions.

This function is designed to identify spots near the edges of the Visium box, tissue boundary, and tears in the tissue. 
These spots may have abnormally high or low counts that may skew downstream analysis and should be filtered out.

## Getting Started

### Dependencies

* To use this function, you will need to install RANN, stringr, dplyr, and tidyr.
  * If they aren't already installed and/or loaded, then the function will handle that for you
* If you wish to use a Seurat object to ensure that the order of the file matches, then load Seurat


## Authors

Contributors names and contact info

K. Garrett Evensen

## Version History

* 0.1
    * Initial Release
