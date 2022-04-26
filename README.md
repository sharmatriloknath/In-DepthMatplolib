# Matplotlib
- Most popular and oldest data visulization library. Python's alternative to MatLab
- It is open source and freeware where as Matlab is not open source (closed source) and not freeware.
- By using this library we can plot data in graphical form very easily. That graphical form can be either 2-D or 3-D.
- It is comprehensive library for creating static, animated, and interactive visualizations in python.
- John Hunter developed matplotlib on top of Numpy and Sidepy libraries.
- It has very large community support. Every data scientist used this library atleast once in his life.
- Advanced libraries like seaborn, plotly are developed on top of matplotlib

**Install Matplotlib**
```python
python -m pip install -U pip
python -m pip install -U matplotlib
```

**To Get Started With Matplotlib**
```python
import matplotlib.pyplot as plt
import numpy as np

x= np.arange(11)
plt.plot(x,x**2)
plt.xlabel("X values")
plt.ylabel("X**2 Values")
plt.show()
```
**For Documentation You Can Check Out The Below Link**
- Check for [Documentation](https://matplotlib.org/stable/users/getting_started/).