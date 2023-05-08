<div align="center">

# Face Detection on Thermal Image
<a href="https://www.python.org/"><img alt="Python" src="https://img.shields.io/badge/-Python 3.7+-blue?style=for-the-badge&logo=python&logoColor=white"></a>
<a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/-PyTorch 1.8+-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white"></a>

![Sample]('imgpath')

<br>
</div>

# Installation

Before installing, make sure the following packages are available:
- Numpy
- PyTorch (I recommend to install your PyTorch from [following website](https://pytorch.org/))
- PIL
- OpenCV

To Install, run the following command:
```bash
pip install MCTThermalFace
```

*Only available in PIP, not in Conda*

# Usage
```python
import MCTThermalFace
from PIL import Image

detector = ThermalFace.Detector('thermal_face_detection.pt')
img = Image.open("img_path")
bbox = detector.detect(img)
```

<br>

# Model Download
Click Here To Download [thermal_face_detection.pt](https://github.com/mctosima/MCTThermalFace/blob/master/thermal_face_detection.pt)

<br>

# Sample Usage
Check this [notebook](https://github.com/mctosima/MCTThermalFace/blob/master/how_to_use.ipynb)

<br>

# Credits
Original Works by: Diza Febriyan Hasal on his Bachelor Thesis about Detecting Face in Thermal Image. Reworked by Martin Clinton Manullang to adjust the performance, adaptability, and compatibility (2023). 