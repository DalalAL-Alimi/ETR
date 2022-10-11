# ETR: Enhancing Transformation Reduction for Reducing Dimensionality and Classification Complexity in Hyperspectral Images 

This is the main code of the paper, which is [here](https://www.sciencedirect.com/science/article/abs/pii/S0957417422019893)

## Abstract
Recent improvements in remote sensing techniques (RST) allow for collecting hyperspectral images (HSIs) with enhanced spatial and spectral resolution. These enhancements boost the volume, velocity, and variety of obtaining HSIs. However, many HSIs comprise extensive variability and undesired pixel distribution because of different atmospheric scattering conditions or maybe because of a malfunction in the RST, called mixed pixels and noise, posing significant processing issues. Dimensionality reduction methods (DRM) have been developed to address this issue. They reduce the complexity of data while retaining the relevant information for the analysis. This study presents a novel DRM called enhancing transformation reduction (ETR) that can enhance and reduce the dimensionality of HSI. The data in ETR goes through two parts. The first part reduces dimensionality and increases the classes' variation. The second part aims to reduce the noise and the gap between values, and it corrects pixels' location and distribution. ETR is an HSI DRM that is quick. It was evaluated using four distinct HSIs and various state-of-the-art classification models. It enables faster extraction, more robust results, and prompt classification compared to other notable DRMs. The code of the ETR method is available on the GitHub site.

### The requested packages:
 
  
> - Tensorfolow 2.6.0 
> - keras 2.10.0 
> - matplotlib 3.53 
> - numpy 1.23.2 
> - pandas 1.4.4 
> - plotly 5.10.0 
> - scikite-image 0.19.3 
> - seaborn 0.12.0 
> - sklearn 
> - spectral 0.22.4 

### The second part of the correction to the position of each pixel in the transferred image.
![alt text](https://github.com/DalalAL-Alimi/ETR/blob/main/images/3.png)

### The results of enhancing transformation reduction (ETR) for the first feature of the KSC dataset.
![alt text](https://github.com/DalalAL-Alimi/ETR/blob/main/images/6.png)

### The time complexity of the enhancing transformation reduction (ETR) method.
![alt text](https://github.com/DalalAL-Alimi/ETR/blob/main/images/7.png)



## Citation
### We would appreciate a citation to the original paper if you use this code in your research works.
```
{
  @article{ALALIMI2022118971,
  title = {ETR: Enhancing Transformation Reduction for Reducing Dimensionality and Classification Complexity in Hyperspectral Images},
  journal = {Expert Systems with Applications},
  pages = {118971},
  year = {2022},
  issn = {0957-4174},
  doi = {https://doi.org/10.1016/j.eswa.2022.118971},
  url = {https://www.sciencedirect.com/science/article/pii/S0957417422019893},
  author = {Dalal AL-Alimi and Zhihua Cai and Mohammed A.A. Al-qaness and Eman Ahmed Alawamy and Ahamed Alalimi}
  }
}
```
