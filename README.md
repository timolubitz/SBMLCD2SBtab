# SBMLCD2SBtab
Conversion of SBML files with Cell Designer annotations to SBtab

The main class SBMLDocument can be initialised by providing an SBML model (as libsbml object) and the filename (as string).
The latter should end on the file extension.

If the SBML file includes Cell Designer annotations, then this is checked automatically upon class initialisation by the function determineCD().
