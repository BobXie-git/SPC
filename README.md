# SPC
Use python to draw control charts
Base on Matt Harrison's Python SPC (https://github.com/mattharrison/python-spc) to fix some bugs and also update some line from Python2 to Python3.
Fixed bugs:
1. Xbar_R and Xbar_S charts without subgroup (Xset)
2. P and C chart can use different subgroup size (Sizes)
At this moment, to run "SPC.py" can not use "pip install" to setup to your computer, but can download the "SPC.py" to your computer, also add two lines in your code as below:
>>import sys
>>sys.path.append('/Python/SPC')  # instead "/Python/SPC" to your path where "SPC.py" is.
