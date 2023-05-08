# KAP360_Straighten_Horizon
Straightening out the horizon in 360-degree Kite Aerial Photos

The python code dm4.py attempts to straighten out wavy horizon in
360-degree Kite Aerial Photos, based on user input. 

The code uses the pyEquirectRotate library from 
https://github.com/BlueHorn07/pyEquirectRotate. However Wheaton CS seniors 
during Spring 2023 semester made some speedup improvements by replacing a 
few nested for-loops by numpy vectorizations. See the top of the code 
equirectRotate/EquirectRotate.py for details.


Requirements:
- Matplotlib
- numpy
- opencv-python
