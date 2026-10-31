# Vibrating Sample Magnetometer Signal Processing Code

This is the folder to measure the residual magnetisation
You can run it once per data set (eg, once per CSV with 3 columns:

Time (s) | CH1 (V) | CH2 (2)

5 main conditions must be met for this code to work:

1. THE COLUMNS MUST BE IN THE ABOVE ORDER
2. CH1 MUST BE THE PICKUP COIL SIGNAL
3. CH2 MUST BE THE EXTERNAL H COIL SIGNAL
4. THE CSV FILE MUST BE IN THE SAME FOLDER AS THE JUPYTER NOTEBOOK FILE
5. MUST HAVE SCIPY, PYTHON and JUPYER LAB INSTALLED ON DEVICE RUNNING CODE

You may install things from here:
Python Install: https://www.python.org/downloads/
Jupyter Lab installation: https://jupyter.org/install
SciPy installation: https://scipy.org/install/

I run jupyter on mac by opening the terminall and typing:

jupyter lab

followed by pressing 'return'. 

Each notebook in this folder is numbered according to how recently it was created

To get started, download this folder onto your computer
Then open and run the python script 'signal_process3.jpynb' in jupyter notebooks 
