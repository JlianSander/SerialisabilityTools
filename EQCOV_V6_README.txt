Arguments:
args[0] = abbreviation of 1st semantics (ADM, CO, PR, GR, ST, UC, SA)
args[1] = abbreviation of 2nd semantics (ADM, CO, PR, GR, ST, UC, SA) (repeat 1st if only one)
---------------------- optional ---------------------------------
args[2] = index of first example to be displayed; if <0 or no argument then all files will be displayed
args[3] = index of last example to be displayed
args[4] = "TRUE" / "FALSE" ; iff TRUE only saved frameworks shall be shown
args[5] = path to the folder containing the folders for each semantics. If no path is declared the program searches for the folders at the location, where the program was started


in Powershell use:
java -jar EQCOV_V6.jar ADM ADM 0 0 FALSE C:\Users\User\experiments\tweetyProject\eQExperiment\strongEQ_serialSequenceNaivEQ