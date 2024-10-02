# Automated-Segmentation-of-Carotid-Arteries
Carotid Artery Segmentation using U-Net with Transfer Learning
This project involves the application of the U-Net convolutional neural network for segmenting carotid arteries in medical images. Accurate segmentation is vital for cardiovascular disease diagnosis and treatment planning. The model leverages deep learning techniques, transfer learning, and advanced evaluation metrics such as the Dice score to ensure high accuracy.

##Model Architecture
The U-Net model is used for segmentation with the following key features:

Encoder-Decoder Architecture: The U-Net model captures context through the encoder and constructs detailed segmentation maps through the decoder.
Skip Connections: These connections from encoder to decoder ensure that spatial details are preserved.
Transfer Learning: Pretrained weights are used to initialize the model, followed by fine-tuning on the carotid artery dataset.


Link to model weights: https://drive.google.com/file/d/1AimQU6I-cY9VpwTk7i0t2LuSuXCC__Bn/view?usp=drive_link
Link to dataset 1 : https://drive.google.com/drive/folders/1lJxMgHa99C1E2grTX4aFnKkn7p42Vphv?usp=sharing
Link to dataset 2 : https://drive.google.com/drive/folders/1zZ0N0oXkLS586e0Uq1sUIHaAj0E4KTCy?usp=sharing
