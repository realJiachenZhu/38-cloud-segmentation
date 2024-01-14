# 38-cloud-segmentation
The aim of this project is to UNET and then use UNET to do cloud segmentation in satellite images. The dataset is from "[https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset](https://www.kaggle.com/datasets/sorour/38cloud-cloud-segmentation-in-satellite-images)https://www.kaggle.com/datasets/sorour/38cloud-cloud-segmentation-in-satellite-images", named "38-Cloud: Cloud Segmentation in Satellite Images". 

The dataset is not included in this repo due to its size after decompression(16 GB)



Demo Explanation:

There are two demos: 10-version-demo.pdf and 70-version-demo.pdf

10-version-demo: This model is trained on 10% of the samples in the dataset(approximately 840 samples), which takes about 1 hour to run 10 epochs.

70-version-demo: This model is trained on 70% of the samples in the dataset(approximately 5880 samples), which takes about 3.5 hours to run 5 epochs(I manually stopped the program).

I didn't create a demo in which the model is trained on 70% of the samples in the dataset and run for 30/50 epochs due to device and time limitations.

However, based on the results(in pdf), we can still conclude that the model works, and we can predict that with more training epochs, the model will perform even better as its accuracy increases with the growth of epochs.
