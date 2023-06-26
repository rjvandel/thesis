# Short term option pricing with jumps

This code supports the results in my thesis. For different datasets we can plot the BSQH and MJD implied volatility and prices. 

## Dependencies

- PyVollib

This project requires the PyVollib library to be installed. PyVollib is a Python library for option pricing, implied volatility (IV) calculations, and more.

### Installation

You can install PyVollib using pip. Open your terminal or command prompt and run the following command:
```
pip install pyvollib
```

For more information about PyVollib, including detailed installation instructions and usage examples, please refer to the [PyVollib GitHub repository](https://github.com/vollib/py_vollib).

## Python Version

This project was developed using Python 3.4.10. To check your Python version, run the following command in your terminal:

```shell
python --version
```

## Files and Folders
The project consists of the following files: 
1. `commonFunctions.py`: In this file you can find the common functions we used in different other files. Such as the COS pricing formula.
3. `CommonFunctionsMatrix.py`: This is the updates file for where the strikes, maturities and interest rates are vectors. 
4. `PlotIVagainstStikes+Maturities.py`: Here we plot the IV against the strike prices and the maturities. 
5. `PlotIVParameters.py`: Here we plot the IV for different varying parameters.
6. `PLOTMERTON.py`: Here we plot the IV and the prices for different datasets in case of the MJD model.
8. `PLOTSTOCKS.py`: Here we plot the IV and the prices for different datasets in case of the BSQH model.
10. `plotPDFs.py`: Here we plot the probability density functions for different N. 
12. `QH.py`: Here we find the class of a Queue Hawkes set. 

Furthermore, we have the following folders:
1. `Data`: In this folder you can find all the data sets, the first number on the first row is the underlying asset price. The second row are the different maturities in days.
2. `Plots`: Here we find all the plots. 

## Example Plots
BSQH model:![DataJPM2IV](https://github.com/rjvandel/thesis/assets/91630817/ce2c3ed0-9927-428c-94b4-bf002e4ae760)

MJD model: ![DataJPM2IVMerton](https://github.com/rjvandel/thesis/assets/91630817/ce02dbac-4ae4-4484-9f1b-ec4d782229e1)



