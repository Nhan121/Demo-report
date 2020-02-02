# Demo-report

import numpy as np
import matplotlib.pyplot as plt

t = np.linspace(-np.pi, np.pi, 200)
x = 2*np.cos(t)
y = 3*np.sin(t)

plt.plot(x, y, marker = '*', color = 'red', label = 'demo-fig')
plt.legend()
plt.show()
