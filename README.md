# Dashtoon Neural Style Transfer with PyTorch
This repository hosts the `dashtoon-neural-style-transfer.ipynb notebook`, showcasing the implementation of neural style transfer using PyTorch. The notebook demonstrates how to apply the artistic style of one image to another, blending them to create visually captivating results.

Here are the installation commands for each dependency, provided line by line for `dashtoon-neural-style-transfer.ipynb` notebook:

1. **PyTorch**: 
   ```bash
   pip install torch
   ```
   
2. **Torchvision**:
   ```bash
   pip install torchvision
   ```
   
3. **PIL (Python Imaging Library)**:
   ```bash
   pip install pillow
   ```

4. **Numpy**:
   ```bash
   pip install numpy
   ```

5. **Matplotlib**:
   ```bash
   pip install matplotlib
   ```

6. **Requests**:
   ```bash
   pip install requests
   ```

We can execute these commands one after the other in the terminal or command prompt to set up the environment for running your notebook. Each line installs one of the required libraries.

---

## Image Resources

The notebook utilizes a set of images stored in two folders within this repository:

- `neural_style_transfer_images1/`
- `neural_style_transfer_images2/`

These folders contain various images that can be used to perform style transfer, including but not limited to:

- Artistic styles: `hockney.jpg`, `kahlo.jpg`, `magritte.jpg`, etc.
- Content images: `cat_image_1.jpg`, `aeroplane_image_1.jpg`, `dash_toon_logo.png`, etc.

### How to Use Images

To use these images in the notebook, we can refer to them by their relative paths. Here's an example snippet of code that loads an image from the first folder:

```python
from PIL import Image

# Load an artistic style image
style_image = Image.open('neural_style_transfer_images1/hockney.jpg')
```

---
## Demonstration Example

Below is an example of how to perform neural style transfer with the images provided in this repository:

### Content Image
Here is the content image we will be using:
![Content Image](neural_style_transfer_images1/octopus.jpg)

### Style Image
Here is the style image that we will apply to the content:
![Style Image](neural_style_transfer_images1/hockney.jpg)

### Stylized Output
After running the style transfer process, we get the following result:
![Stylized Image](stylized_image.png)
