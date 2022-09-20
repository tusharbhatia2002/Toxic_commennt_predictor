# Toxic_comment_predictor
Machine Learning project to predict whether a comment is toxic or not
<br />
#### Aim : 
     To train a NLP model to predict whether a comment is toxic or not.
##
     
     
#### Dataset : 
  [Drive link](https://drive.google.com/drive/folders/1ttx1biVo1073lZOMnMlWqQcjn6jpEO10?usp=sharing)
<br />
  
 ##   

#### Process : 
    1. Data exploration and preprocessing : 
            a. Reading a csv file of training dataset.
            b. Exploring the dataset 
            c. Coverting the words in the dataset into numeric numpy arrays using TextVectorization
            d. Identifying dependent and independent variables and creating batches.
            e.Splitting the dataset into traintest and validation set.

    2. Building the layers of neural network : 
            a. selected sequential model becuase each layer has one input and one ouput. 

    3. Configuring .pbtxt and .config file : 
            a. Generated a .pbtxt file which consists of labels. In this case "scratch", "dent" and "replacement" was used. 
            b. Configured .config file. path to training data, evaluation data, number of classes, batch size, number of steps were configured to initiate the training process.

    4. Training the model : 
           a. Trained the model using : 
                                a. batch size = 24
                                b. num_step = 25k
                                c. number of hrs trained = 2:30 hrs 
                                d. loss of saved model = 1.3% 
                                e. The model was trained on Google Colab for accessing the better resource like GPU. 
                                

##

#### Libraries used : 
        1. Tensorflow 
        2. keras
        3. Numpy
        4. OS
        5. Matplotlib
        6. Pandas 
        
##
     
##
