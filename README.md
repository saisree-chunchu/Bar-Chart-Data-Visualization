# Bar-Chart-Data-Visualization
import matplotlib.pyplot as plt
import pandas as pd

# Load dataset
data = pd.read_csv('/content/Amazon.csv')

# Example of creating a bar chart
#Code 1
plt.figure(figsize=(10,6))
plt.bar(data['category'], data['rating'], color='blue')
plt.title('Bar Chart of Categories')
plt.xlabel('category')
plt.ylabel('rating')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()

#Code 2
import matplotlib.pyplot as plt
import pandas as pd

# Load dataset
data = pd.read_csv('/content/Amazon.csv')

# Example of creating a bar chart
plt.figure(figsize=(20,16))
plt.bar(data['category'], data['rating'], color='blue')
plt.title('Bar Chart of Categories')
plt.xlabel('category')
plt.ylabel('rating')
plt.xticks(rotation=0)
plt.tight_layout()
plt.show()

#Code 3
import matplotlib.pyplot as plt
import pandas as pd

# Load dataset
data = pd.read_csv('/content/Amazon.csv')

# Example of creating a bar chart
plt.figure(figsize=(20,16))
plt.bar(data['category'], data['rating'], color='blue')
plt.title('Bar Chart of Categories')
plt.xlabel('category')
plt.ylabel('rating')
plt.xticks(rotation=90)
plt.tight_layout()
plt.show()
