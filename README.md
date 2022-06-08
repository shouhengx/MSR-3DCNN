# Multiple Spectral Resolution 3D Convolutional Neural Network (MSR-3DCNN)

This is the code of the hyperspectral image classification network: Multiple Spectral Resolution 3D Convolutional Neural Network (MSR-3DCNN).
The datasets required for the code can be found at http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes.

The corresponding paper __*Multiple Spectral Resolution 3D Convolutional Neural Network(MSR-3DCNN) for Hyperspectral Image Classification*__ of the code has been accpeted by remote sensing.
The paper can be found at https://www.mdpi.com/2072-4292/13/7/1248.

## Model
![MSR-3DCNN](https://user-images.githubusercontent.com/66879051/172546821-0c433f40-acf5-41e2-9ccc-41ecf2606a34.jpg)

The main idea of the proposed MSR-3DCNN is based on two novel designs: spectral dilated convolution and multiple spectral resolution fusion. These two designs give the proposed model three advantages: First of all, operations based on SDC are quite efficient to extract spectral features in HSIs. Then, the MSR modules in the proposed model can effectively make use of the rich spectral information in HSIs. As more attention has been paid to the processing of spectral information, MSR-3DCNN shows less reliance on spatial information and therefore is more robust to images with different spatial structures.

## Citation
Please kindly cite the papers if this code is useful and helpful for your research.  
```
@Article{rs13071248,
AUTHOR = {Xu, Hao and Yao, Wei and Cheng, Li and Li, Bo},
TITLE = {Multiple Spectral Resolution 3D Convolutional Neural Network for Hyperspectral Image Classification},
JOURNAL = {Remote Sensing},
VOLUME = {13},
YEAR = {2021},
NUMBER = {7},
ARTICLE-NUMBER = {1248},
URL = {https://www.mdpi.com/2072-4292/13/7/1248},
ISSN = {2072-4292},
}
```
## License
Copyright (c) 2021 Hao Xu. Released under the MIT License.
