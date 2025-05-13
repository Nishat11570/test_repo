# Test Repo for PHY 546

This is the test repository for our PHY 546 git experimenting.
import numpy as np
from scipy import integrate
N = 17
x = np.linspace(0.0, 2.0*np.pi, N, endpoint=True)
y = np.sin(x)**2

I = integrate.simpson(y, x=x)
print(I)
