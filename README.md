# Short term option pricing with jumps

This code supports the results in my thesis. For different datasets we can plot the BSQH and MJD implied volatility and prices. 

## Dependencies

- PyVollib

This project requires the PyVollib library to be installed. PyVollib is a Python library for option pricing, implied volatility calculations, and more.

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
1. `commonFunctions.py`
   
3. `CommonFunctionsMatrix.py`
4. `PlotIVagainstStikes+Maturities.py`
5. `PlotIVParameters.py`
6. `PLOTMERTON.py`
7. `PLOTSTOCKS.py`
8. `plotPDFs.py`
9. `QH.py`

Furthermore, we have the following folders:
1. Data
2. Plots



   

## Example Plots
BSQH model:![DataJPM2IV](https://github.com/rjvandel/thesis/assets/91630817/ce2c3ed0-9927-428c-94b4-bf002e4ae760)

MJD model: ![DataJPM2IVMerton](https://github.com/rjvandel/thesis/assets/91630817/ce02dbac-4ae4-4484-9f1b-ec4d782229e1)



