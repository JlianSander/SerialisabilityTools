-----------------------------------------
Arguments:
-----------------------------------------

args[0] = number of arguments of the frameworks
args[1] = "strong" / "standard" / "sequenceNaiv" / "graphIsomorph" / "graphNaiv" / "tranSeqNaiv" / "identity"  - sort of eqivalence for 1. equivalence condition (EQ1)
args[2] = "strong" / "standard" / "sequenceNaiv" / "graphIsomorph" / "graphNaiv" / "tranSeqNaiv" / "identity" - sort of eqivalence for 2. equivalence condition (EQ2)
args[3] = name of the experiment
================= optional ==============
args[4] = Number of tries to generate 2nd AF; has to be > 0; default = 1000
args[5] = 1st semantics; seperate semantics by ',' use "ADM" / "CO" / "GR" / "PR" / "ST" / "UC" / "SA"; default = All semantics
args[6] = 2nd semantics; default = NULL
args[7] = Path to the folder, in which a new folder will be created for the started experiment. If this argument is empty, then the folder will be created in the same place the program was started in

-----------------------------------------
Conditions:
-----------------------------------------

Accepts pairs if:
EQ1 != EQ2

Rejects 1st AF if:
never

Examines Pair only if:
- Number of Argument in 1st AF == Number of Argument in 2nd AF

Continues Generating 2nd AF if:
Number of Argument in 1st AF >= Number of Argument in 2nd AF

Only saves 1 pair as an example for one direction found (EQ1=>EQ2 or EQ2=>EQ1)

-----------------------------------------
Information about Generators:
-----------------------------------------

1st AF Generator:
global Enumerating Generator
iterated through all possible AF's

2nd AF Generator:
Enumerating Generator, created for each pair, starts with number of arguments of 1st AF
