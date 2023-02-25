# Decentralized-learning-approach-with-handwritten-data
The federated learning approach for handwritten data. The comparison between without parellelization and with parellelization was plotted. 

Introduction 
      MNIST is a widely used dataset of handwritten digits that contains 60,000 handwritten digits for training a machine learning model and 10,000 handwritten digits for testing the model. It was introduced in 1998 and has become a standard benchmark for classification tasks. It is also called the “Hello, World” dataset as it’s very easy to use. MNIST was derived from an even larger dataset, the NIST special database which not only contains digits but also uppercase and lowercase handwritten letters.

The model have been trained with use of gpu that yield a good results with speed execution.

GPU’s have more cores than CPU and hence when it comes to parallel computing of data, GPUs perform exceptionally better than CPUs even though GPUs has lower clock speed and it lacks several core management features as compared to the CPU. 

Thus, running a python script on GPU can prove to be comparatively faster than CPU, however, it must be noted that for processing a data set with GPU, the data will first be transferred to the GPU’s memory which may require additional time so if data set is small then CPU may perform better than GPU. 

What is Federated Learning?
Federated Learning is simply the decentralized form of Machine Learning.

In Machine Learning, we usually train our data that is aggregated from several edge devices like mobile phones, laptops, etc. and is brought together to a centralized server. Machine Learning algorithms, then grab this data and trains itself and finally predicts results for new data generated.

Great!

But, can you smell a “privacy nightmare”?

The AI market is dominated by tech giants such as Google, Amazon and Microsoft, offering cloud-based AI solutions and APIs. In the traditional AI methods, sensitive user data are sent to the servers where models are trained.

That’s awful! With the increased awareness of user privacy across different devices and platforms, AI developers should not ignore the fact that their model is accessing and using data that is user-sensitive!

Well, here comes our Savior! The Federated Learning approach.
