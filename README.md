import matplotlib.pyplot as plt
import numpy as np
x_line = [0, 1, 2, 3, 4, 5]
y_line = [10, 20, 15, 25, 30, 20]
plt.figure(figsize=(10, 6))
plt.plot(x_line, y_line, 'r--', marker='o', markerfacecolor='blue')
plt.title("Biểu đồ Line")
plt.xlabel("Thời gian (giờ)")
plt.ylabel("Giá trị")
plt.grid(True)
plt.show()
