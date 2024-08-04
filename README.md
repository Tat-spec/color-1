# color-1import matplotlib.pyplot as plt

# Define the RGB values for turquoise
turquoise = (64/255, 224/255, 208/255)

# Create a plot to display the color
plt.figure(figsize=(2, 2))
plt.imshow([[turquoise]])
plt.axis('off')  # Hide the axes
plt.title('Turquoise Color')
plt.show()
