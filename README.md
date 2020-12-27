# Bangla-Handwritten-Character-Recognition
Bangla Handwritten Character Recognition using different CNN architectures.

## Overview
The handwritten character recognition problem which varies among different languages due to distinct shapes, strokes and number of characters has been studied extensively during the last few decades with varying level of success. In case of Bangla Handwritten Character Recognition, here I tried different CNN architectures and made few modifications to improve the result. However, I used [Colab](https://colab.research.google.com/) to train the models and PC for furthers works. An overview of this project is available on [YouTube](https://www.youtube.com/watch?v=SvCAFmg2emI&ab_channel=MehediHasanBijoy).


## Requirements
| In Colab                | In PC                  |
| ------------------------|------------------------|
| • Python 3.6.9          | • Python 3.7.9         |
| • Tensorflow 2.4.0      | • Tensorflow 2.4.0     | 
| • Keras 2.4.3           | • Keras 2.4.3          | 
| • PIL 7.0.0             | • PIL 8.0.0            | 
| • Numpy 1.19.4          | • Numpy 1.19.4         |

## Train A Particular Model
#### Part_1: In Colab
1. Upload the `ModelName.ipynb` file in colab.
2. Upload the `Dataset.zip` file in `ModelName.ipynb` notebook's Files section. 
3. Run the notebook.
4. Two files will be saved after the training completed. Download both `ModelName.h5` and `ModelName.json` files and keep them in `./Saved Models` directory.
#### Part_2: In PC
5. Extract `Dataset.zip` file.
6. Run `LoadModel.ipynb` and follow the notebook for further work.

## Load A Pre-Trained Model
1. Extract `Dataset.zip` file.
2. Open `LoadModel.ipynb` in your PC.
3. Load the saved model.
4. Compile the loaded model.
5. Follow the notebook for further work.


#### Working...
