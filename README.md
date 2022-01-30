# Dixit-Coupled-Drillstring-Model

## Objective
Current tool assists in modelling transient behavior of drill-string under different tripping and drilling operations.

## Scope
The current model covers following outline:
*	The tool helps to understand the severity of coupled axial torsional vibrational dysfunctions on the drilling performance
*	Both on and offbottom cases can be modeled using the current tool.
*	Stick slip severity can be assessed to identify the optimum range of parameters for certain run
*	Tool present transient variation of drillstring under different operating conditions
*	Tool account modelling for drilling, tripping, backreaming operations 
*	Tool also includes the case of drilling in interbedded formations where rock strength varies with depth.
*	Flexibility to choose different Topdrive ROP and RPM Input conditions with necessary delays if required.
* No limit on segregation of elements of drillstring to account for sensitivity in well path 
*	Selection flexibility for Open and Cased Hole Friction Factor 

Model also accommodates a down hole mud motor assembly in the string to assess following cases:
*	Drilling in Slide and Rotate mode
*	Pipe Rocking phenomenon
*	Motor stall and back off events
*	Axial and torsional stiction of string under different borehole friction conditions
*	Effect of application of lubrication on various position of drillstring on friction

## Software layout
The software solutions contain:
* A model where actual variation in field test cases can be modelled and is providing support in both planning and post job analysis to idntify dysfunctions.

The development of current model is in Python, MATLAB and Simulink programming languages. Proper comments and labelling has been rendered in all code languages to help the user understands the background Physics of model implementation and make necessary changes as per test cases variability.

## Prerequisites
User needs to have downloaded in his system, MATLAB version post 2015b to be able to operate the code and generate results accordingly.

## Assumptions
Current model has accounted following assumptions:
* Pipe stretch effects during tripping operations are not included in model popularly known as Capstan effect. This feature is currently under development phase to make the current version a full fletched soft string model. 

In mud motor integrated code, pressure pulse effects are not accounted for now, 
* A flow rate delay feature has been introduced in the system to allow drilling mud to travel along the length of the string to the mud downhole in realistic timeframe and does  not alter the results.

## License
The code is a donation by ExxonMobil and is made available under the MIT license. The original contributors for the software solutions are:

OSDC: Dixit-Coupled-Drillstring-Model
* Rajat Dixit (ExxonMobil)
* Paul Pastusek (ExxonMobil)
* Greg Payette (ExxonMobil)
