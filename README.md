# Road Sign Classification with PyTorch
The project presented is a Road Sign Classification task using Pytorch. It is the project inserted in the last chapter of my Bachelor Thesis.<br><br>
## Approach
The project will analyze a case of classificiation of road sign. The dataset used for this classification is the German Traffic Sign Recognition Benchmark (GTSRB), composed by 39209 training images divided in 43 classes and 12631 test images. This dataset can be download from: https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign.
Below some images of the dataset.
![](/images/sign.png)<br><br>
In order to be able to carry out the operations in a reasonable time with the available system, it is necessary to use Cuda, which allows to increase the performance using the GPU . More detailed information from: https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html#abstract.<br><br>
From the implementation perspective, it will be used a convolutional neural network based of AlexNet, an Adam optimizer, a cross entropy function as error function. A detailed explanation about all the features of the project is made in the jupyter notebook available in this folder.
## Conclusion
To conclude, the main elements and the final performances can be summarized: the training phase allowed to obtain a model with an accuracy equal to 99% after 15 epochs, also confirmed by the evaluation using the validation test. Finally, the model also performed optimally with the test set, obtaining an accuracy of 95% and excellent metrics such as precision and recall.
