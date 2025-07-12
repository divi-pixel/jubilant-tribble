# jubilant-tribble

import seaborn as sns
import matplotlib.pyplot as plt

# Sample data
data = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4, 5, 5, 6, 7, 8, 9]

# Create a KDE plot
sns.kdeplot(data, shade=True, color='blue')

# Add labels and title
plt.xlabel('Value')
plt.ylabel('Density')
plt.title('KDE Plot Example')

# Show the plot
plt.show()
