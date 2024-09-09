# HAM10000

Skin cancer is the most commonly diagnosed form of cancer in humans. It can occur when there is an abnormal growth of skin cells, typically triggered by damage to DNA from ultraviolet (UV) radiation found in sunlight or tanning beds. There are several types of skin cancer, including basal cell carcinoma, squamous cell carcinoma, and melanoma.

In the latest years, Deep Learning (DL) tools such as Artificial Neural Networks (ANNs) have been deployed for the early detection and classification of diseases. Neural networks are able to learn patterns from the given input: texts, graphs, audios and also images, an inestimable source of data when it comes to biology. Convolutional Neural Networks (CNNs) are particularly used for computer vision tasks, included cancer classification.

The dataset ([download link](https://www.kaggle.com/datasets/surajghuwalewala/ham1000-segmentation-and-classification/download?datasetVersionNumber=2)) presented in this project is the HAM10000 dataset ("Human Against Machine with 10000 training images"). This dataset consists of 10015 dermatoscopic images, in "RGB" channel, which can serve as a training set for academic machine learning purposes. Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions:



*   Actinic keratoses and intraepithelial carcinoma / Bowen's disease (***akiec***);
*   Basal cell carcinoma (***bcc***);
*   Benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, ***bkl***);
*   Dermatofibroma (***df***);
*   Melanoma (***mel***);
*   Melanocytic nevi (***nv***);
*   Vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, ***vasc***).

The dataset comes with a single folder for the images (*images*) and a .csv metadata file (*GroundTruth.csv*). Beyond of the project scope is the *masks* folder, containing the segmented images (i.e., the delineation of the tumoral region in the images folder).

The goal of this project is to train a multicategorical CNN classifier able to recognize all the seven cancer types present in the dataset, trying to improve its performance and eventually reduce overfitting.
