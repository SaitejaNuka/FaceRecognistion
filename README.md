# FaceRecognistion

How to run ?
# Create a new environment
Step 1 : open your anaconda prompt (for windows user search inside start menu )
                                   (for Ubuntu and Mac user you can open your terminal)

Step 2 : Create a new environment
                command : conda create -n facerecognition python==3.6.9
Step 3 : activate your environment
                conda activate facerecognition
Step 4 : Install requirements.txt in the newly created environment
            a). Navigate to your folder location on anaconda prompt/teminal
                    for me ( /PycharmProjects/FaceRecogAcademy )
                    for your folderName
            b). Check if we have requirements.txt or not in the current directory

                    command : for windows (dir)
                              for Mac/Ubuntu(ls)
                    datasets,  How to run.txt,  requirements.txt,  src

                    you should see the above mentioned name of files.

                    if yes:
                        Your are good to go
                    elif No:
                        Please check the steps again you must have missed something

Step 5 : Installation and setup is done:
         a).  cd src
         b). python clientApp.py

         Yor are good to go ........................................

**InsightFace: Face Recognistion Project**

![1 jpeg](https://user-images.githubusercontent.com/65356981/127193824-f95d791a-b34a-41e8-9c9c-da53e4aaad67.jpg)
InsightFace is an open source 2D&3D deep face analysis toolbox, mainly based on PyTorch and MXNet.

The master branch works with PyTorch 1.6+ and/or MXNet=1.6-1.8, with Python 3.x.

InsightFace efficiently implements a rich variety of state of the art algorithms of face recognition, face detection and face alignment, which optimized for both training and deployment.


![2](https://user-images.githubusercontent.com/65356981/127194389-5bb9a1bf-4a5c-4414-a314-8367765fafd9.png)

**Projects**
**Face Recognition**
In this module, we provide training data, network settings and loss designs for deep face recognition.
The supported methods are as follows:
 ArcFace_mxnet (CVPR'2019)
 ArcFace_torch (CVPR'2019)
 
 Commonly used network backbones are included in most of the methods, such as IResNet, MobilefaceNet, MobileNet, InceptionResNet_v2, DenseNet, etc..
 
 **Datasets**
The training data includes, but not limited to the cleaned MS1M, VGG2 and CASIA-Webface datasets, which were already packed in MXNet binary format. 
 
**Evaluation**
We provide standard IJB and Megaface evaluation pipelines in evaluation

**Pretrained Models**
Please check Model-Zoo for more pretrained models.

**Face Detection**

![3](https://user-images.githubusercontent.com/65356981/127195501-8c0a8c1e-cd9a-440e-af33-b513cd8b1a58.jpg)

In this module,  provide training data with annotation, network settings and loss designs for face detection training, evaluation and inference.

The supported methods are as follows:

 RetinaFace (CVPR'2020)
 SCRFD (Arxiv'2021)
 
 RetinaFace is a practical single-stage face detector which is accepted by CVPR 2020. We provide training code, training dataset, pretrained models and evaluation scripts.

SCRFD is an efficient high accuracy face detection approach which is initialy described in Arxiv. We provide an easy-to-use pipeline to train high efficiency face detectors with NAS supporting.

**Face Alignment**

<img width="300" alt="4" src="https://user-images.githubusercontent.com/65356981/127195726-af8d52ae-06ea-45d7-a232-39f562f77c27.png">
In this module, provide datasets and training/inference pipelines for face alignment.

Supported methods:

 SDUNets (BMVC'2018)
 SimpleRegression
SDUNets is a heatmap based method which accepted on BMVC.

SimpleRegression provides very lightweight facial landmark models with fast coordinate regression. The input of these models is loose cropped face image while the output is the direct landmark coordinates.
