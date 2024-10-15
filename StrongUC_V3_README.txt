-----------------------------------------
Arguments:
-----------------------------------------

args[0] = number of arguments of the frameworks F, G
args[1] = number of arguments of the frameworks H
================= optional ==============
args[2] = number of iterations to generate FG		[Default: 10000]
args[3] = number of iterations to generate H		[Default: 10000]
args[4] = number of threads				[Default: 6]
args[5] = name of the experiment			[Default: "SearchStrongUC"]
args[6] = Path to the folder, in which a new folder will be created for the started experiment. If this argument is empty, then the folder will be created in the same place the program was started in

Generator F:	Random	(DefaultDungTheoryGenerator, AttckProb=0.2 AvoidSelfAtck='FALSE' enforceTree='FALSE')
Generator G: 	Random	(DefaultDungTheoryGenerator, AttckProb=0.2 AvoidSelfAtck='FALSE' enforceTree='FALSE')
Generator H:	Random	(DefaultDungTheoryGenerator, AttckProb=0.2 AvoidSelfAtck='FALSE' enforceTree='FALSE')

Enumerating Generators generate all frameworks possible for the specified number of arguments.


