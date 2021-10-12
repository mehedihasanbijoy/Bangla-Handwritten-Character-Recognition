<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">Bangla-Handwritten-Character-Recognition</h1>

  <h4 align="center">
    Bangla Handwritten Character Recognition using different CNN architectures. <br> <br>
  </h4>
  
<!--   <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">Overview</a>
    </li>
    <li>
      <a href="#getting-started">Keras</a>
    </li>
    <li>
      <a href="#usage">Pytorch</a>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Overview
The handwritten character recognition problem which varies among different languages due to distinct shapes, strokes and number of characters has been studied extensively during the last few decades with varying level of success. In case of Bangla Handwritten Character Recognition, here I tried different CNN architectures and made few modifications to improve the accuracy. However, I used [Colab](https://colab.research.google.com/) to train the models and PC for further works. Moreover, I have implemented this project using Keras and Pytorch. An overview of this project is available on [YouTube](https://www.youtube.com/watch?v=SvCAFmg2emI&ab_channel=MehediHasanBijoy).





<!-- KERAS -->
## Keras

### Prerequisites
| In Colab                | In PC                  |
| ------------------------|------------------------|
| • Python 3.6.9          | • Python 3.7.9         |
| • Tensorflow 2.4.0      | • Tensorflow 2.4.0     | 
| • Keras 2.4.3           | • Keras 2.4.3          | 
| • PIL 7.0.0             | • PIL 8.0.0            | 
| • Numpy 1.19.4          | • Numpy 1.19.4         |

### Train A Particular Model
#### Part_1: In Colab
1. Upload the `ModelName.ipynb` file in colab.
2. Upload the `Dataset.zip` file in `ModelName.ipynb` notebook's Files section. 
3. Run the notebook.
4. Two files can be found in the files section when training is complete. Download both `ModelName.h5` and `ModelName.json` files and keep them in `./Saved Models` directory.
#### Part_2: In PC
5. Extract `Dataset.zip` file.
6. Run `LoadModel.ipynb` and follow the notebook for further work.

### Load A Pre-Trained Model
1. Extract `Dataset.zip` file.
2. Open `LoadModel.ipynb` in your PC.
3. Load the saved model.
4. Compile the loaded model.
5. Follow the notebook for further work.



<!-- PYTORCH -->
## Pytorch





<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.




<!-- CONTACT -->
## Contact
Mehedi Hasan Bijoy - [@Facebook](https://facebook.com/mhbsheikh) - [@LinkedIn](https://www.linkedin.com/in/mhbsheikh/)

