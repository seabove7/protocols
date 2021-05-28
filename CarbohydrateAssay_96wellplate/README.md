# Carbohydrate assay of coral host tissue in 96-well plates

## Files included in folder
1. PDF version of protocol for carbohydrate assay lab work (*Colorimetric Carbohydrate Assay for Corals.pdf*)
2. Carbohydrate calculation Rmarkdown script (*Carbohydrate Calculation Script.Rmd*)
4. Sample plate files to running the Rmarkdown script (*Bove_Plate8_07Aug19.csv*)


## Running the calculation script
1. Put the Rmarkdown file into a folder with the csv files from the plate reader output
2. Open the Rmarkdown file and run with the sample plate name (*Bove_Plate8_07Aug19*) to ensure it runs
3. If code runs successfully, input the following that correspond to your samples and run again:
    * **output_filename:** This is the output file name that the calculated values will populate
    * **filename:** The name of the initial plate run 
    * **coral_ID:** The sample names you wish each sample to be associated with and saved in the output as
 4. If issues occur with the code, check to make sure all required packages are installed and loaded, all files are correctly named, and all files are in the correct location. If errors still occur, please feel free to contact me with any questions (colleenbove@gmail.com).


## What the script does:
The Rmarkdown will calculate a standard curve (see below for sample) that is used for calculating the concentration of carbohydrate per well based off the absorbance values. The Rmarkdown output file will display the calculated standard equation and R<sup>2</sup>, an interactive standard curve plot, table including a subset of calculated lipid concentrations per sample, and the name of the output file.

Sample of the standard curve plot obtained from sample plate included:
![Bove_Plate8_07Aug19_STD plot_2021-05-28 copy](https://user-images.githubusercontent.com/45176386/120034921-c340c400-bfcb-11eb-9b72-31b0b4cf5405.png)



---

**For the published protocol, see [dx.doi.org/10.17504/protocols.io.bvb9n2r6](https://www.protocols.io/view/coral-carbohydrate-assay-for-96-well-plates-bvb9n2r6)**
