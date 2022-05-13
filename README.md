<div id="top"></div>



<!-- PROJECT SHIELDS -->

[![MIT License][license-shield]][license-url]
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ning-yu-kao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaoningyupage/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaoningyu@gmail.com)





<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1HC6VrP9t-nF4w-2FUaR2pU_dhst8vlsB" width="1000" height="200">
  <h1 align="center">Image Segmentation of Medical Scans to Improve Cancer Treatment</h1>
  <p>Deep learning, one of the branches of artificial intelligence, has seen exponential growth in recent years. Furthermore, a large amount of medical data and the development of more powerful computers has also fostered an interest in this area. This project aimed to implement modern deep learning architecture, U-Net, to track healthy organs to improve cancer treatment.</p>
</div>



<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#references">References</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project was inspired by a [Kaggle competition](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation). Briefly, we want to create a model that can automatically segment the stomach and intestines on MRI scans. A method to segment the stomach and intestines would make treatments much faster and would allow more patients to get more effective treatment. 

Please check out the Kaggle competition page if you need more information!



### Built With

This is major frameworks/libraries used in this project.

* Python
* Jupyter
* Pytorch

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

You can just follow the steps in the notebook to install and get started.

### Prerequisites

Go to [Weights & Biases](https://wandb.ai/site) to sign up an account if you want to use MLOps to track your experiments.

### Installation


1. Install packages
   ```sh
   pip install -q segmentation_models_pytorch
   pip install -qU wandb
   pip install -q scikit-learn==1.0
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


## References
```sh
@article{ANAYAISAZA2021100723,
title = {An overview of deep learning in medical imaging},
journal = {Informatics in Medicine Unlocked},
volume = {26},
pages = {100723},
year = {2021},
issn = {2352-9148},
doi = {https://doi.org/10.1016/j.imu.2021.100723},
url = {https://www.sciencedirect.com/science/article/pii/S2352914821002033},
author = {Andrés Anaya-Isaza and Leonel Mera-Jiménez and Martha Zequera-Diaz}
}
```
```sh
@InProceedings{10.1007/978-3-319-24574-4_28,
author="Ronneberger, Olaf and Fischer, Philipp and Brox, Thomas",
title="U-Net: Convolutional Networks for Biomedical Image Segmentation",
booktitle="Medical Image Computing and Computer-Assisted Intervention -- MICCAI 2015",
year="2015",
publisher="Springer International Publishing",
address="Cham",
pages="234--241",
}
```

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

These resources are which I would like to give credit to.
* [Pytorch AMP](https://pytorch.org/docs/stable/amp.html)
* [Pytorch Scheduler](https://www.kaggle.com/code/isbhargav/guide-to-pytorch-learning-rate-scheduling/notebook)
* [UWMGI: Unet](https://www.kaggle.com/code/awsaf49/uwmgi-unet-train-pytorch)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
<div align="center">
  <h3>Please feel free to connect with me on social media</h3>
    <a href="https://github.com/ning-yu-kao">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.linkedin.com/in/kaoningyupage">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="3%"/>
    </a>
    <img width="3%" />

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/ning-yu-kao/Med_scan_img_seg_unet/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/ning-yu-kao/Med_scan_img_seg_unet/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/kaoningyupage/
[product-screenshot]: images/screenshot.png
