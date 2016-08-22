# SBMLCD2SBtab
Conversion of SBML files with Cell Designer (CD) annotations to SBtab

The main class SBMLDocument can be initialised by providing an SBML model (as libsbml object) and the filename (as string).
The latter should end on the file extension.

If the SBML file includes CD annotations, then this is checked automatically upon class initialisation by the function determineCD(model). If CD annotations are found, a preprocessing function is started which accesses the multilayered information of CD SBML files: cd_preprocessing().


