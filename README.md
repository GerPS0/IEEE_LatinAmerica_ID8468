# IEEE_LatinAmerica_ID8468
![GraphicalAbstract](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/assets/108953866/53410559-b1f5-47c6-acd6-ece8fdedcb40)

# IMPORTANT NOTES

THE FOLLOWING DOCUMENTATION IS A HELP TO EXECUTE AND PROBE THE RESULT OF THE IEEE LATIN AMERICA PAPER CALLED "Fractional-Order Control for Voltage Regulation in Bidirectional Converters An Experimental Study" WITH ID 8468

## MATLAB FILES
1. [Boost_aproximation.m](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/MATLAB_files/Boost_aproximation.m) Mat function with the code to generate the FOPID and fractional approximation of Boost converter.
2. [Buck_aproximation.m](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/MATLAB_files/Buck_aproximation.m) Mat function with the code to generate the FOPID and fractional approximation of Buck converter.
3. [Main_function.m](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/MATLAB_files/Main_function.m) Main script to set the parameters of each converter and escecute both function. Note: the parameters can be modified by user.
4. [Variables.m](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/MATLAB_files/Variables.m) Global variables used in each Mat function.

## INSTRUCTIONS TO DESIGN THE FOPID
The file [Steps to FOPID controller.txt](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/Steps to FOPID controller.txt) is a guide to use the provided material together with the steps described in the article to generate a FOPID controller.

## INSTRUCTIONS TO EXECUTE A CORRECT TEST OF THE FOPID
The file [Steps to implement the controller.txt](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/Steps to implement the controller.txt) is a guide on how to test the controller in a test setup similar to the one illustrated in the article.

## PSEUDO CODE TO HELP THE CODING THE FOPID IN A MICROCONTROLLER
The file [Pseudocode.txt](https://github.com/GerPS0/IEEE_LatinAmerica_ID8468/blob/main/Pseudocode.txt) provides an example of the code used to execute the controller on a DSP.

## LIST OF MATERIALS AND EQUIMENT
* DC Power source, at least 100W.
* Osciloscope, 2Gs reccomended. (Used: Keysight DSOX1102A).
* Controller MCU, with at least 100KSPS ADC & PWM (Used: Texas Instrument F280042C).
* DC-DC Power electronic converter, see article for details.
* Resistive loads, see article for details.

## SOFTWARE REQRUIREMENTS
* Matlab 2018 or later
* PSIM (optional)
* Code Composer 10.1.1 or later
