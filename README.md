# Chondrogenesis_MODEL
This repo contains 3 cps files, 2 csv files and a png file.

The Ideal_Output.png shows the calibration and validation data we received. The validation data set occurred from the Knock down of MIR199b-5p.

The CALIB and VALID csv files contain data to be used in Parameter estimation (PE). 

The TOY_MODEL is an example of trying to run PE with both CALIB and VALID data. This does not work, only the CALIB data is taken into account when estimating parameters. 

The TOY_MODEL_duplicatedreaction cps file shows the recommendation from the COPASI forum. To duplicate experiments. This can work but will generate two distinct parameter sets. This is not what we want. 

The TOY_EYE cps file shows the most successful attempt at simulating this knock down. Here an event is used to reduce the MIR levels and this somewhat matches the Ideal_Output.png file.


