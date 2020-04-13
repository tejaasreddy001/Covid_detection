# Covid_detection
I have used CNN using Keras and TensorFlow to detect whether the patient is suffering from Corona or not based on his or her's lung X-ray

In order to run the code you need to first install Keras and Tensorflow 2.0 libraries in Python.

Follow the steps for execution:

Step1: Create a folder (name it as keras-covid-19 or any other name)

Step2: Inside the folder create another folder and name it as dataset
       Inside the dataset folder create 2 new folders covid and normal
       Inside the covid folder place all the covid+ve images
       Inside the covid folder place all the covid-ve images or nomal images
     
Step3:Come back to keras-covid-19 folder and in that folder first save the get_data.py code and then run  the code.
      After running the code in the same folder you will see two new files created X.pickle and Y.pickle
      Then copy the neural_net.py code and run it in the same folder
      Download an image and save it in keras-covid-19 folder as test.jpg or .png etc and at the same time open the time_to_test.py code and           find test.jpg and replace it with the type of image you have downloaded.
      Then finally run the time_to_test.py code and check the output.
