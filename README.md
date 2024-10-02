# Automated-Segmentation-of-Carotid-Arteries
Carotid Artery Segmentation using U-Net with Transfer Learning
This project involves the application of the U-Net convolutional neural network for segmenting carotid arteries in medical images. Accurate segmentation is vital for cardiovascular disease diagnosis and treatment planning. The model leverages deep learning techniques, transfer learning, and advanced evaluation metrics such as the Dice score to ensure high accuracy.

##Model Architecture
The U-Net model is used for segmentation with the following key features:

Encoder-Decoder Architecture: The U-Net model captures context through the encoder and constructs detailed segmentation maps through the decoder.
Skip Connections: These connections from encoder to decoder ensure that spatial details are preserved.
Transfer Learning: Pretrained weights are used to initialize the model, followed by fine-tuning on the carotid artery dataset.
