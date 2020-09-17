# SPC
Use python to draw control charts<br>
Base on Matt Harrison's [Python SPC] (https://github.com/mattharrison/python-spc) to fixed some bugs and also updated some lines from Python2 to Python3.<br>
Fixed bugs:<br>
1. Xbar_R and Xbar_S charts without subgroup (Xset)<br>
2. P and C chart can use different subgroup size (Sizes)<br>
At this moment, to run "SPC.py" can not use "pip install" to setup to your computer, 
but can download the "SPC.py" to your computer, also add two lines in your code as below:<br>

```
import sys
sys.path.append('/Python/SPC')    # instead "/Python/SPC" to your path where "SPC.py" is.
```

For more detail of how to use SPC, pls refer the "Demo.ipynb"
