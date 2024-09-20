# Aerial Landscape MSc Project Code. READ INSTRUCTIONS BELOW!

Before attempting to run the code, please download the following datasets:  

- **Training dataset**: [Download here](https://drive.google.com/drive/folders/1GaOdVETCCDiH92ym8rLkZnH10ChMuEtE?usp=drive_link)  
- **Test dataset**: [Download here](https://drive.google.com/drive/folders/1AeqAznYLLQdcvZNttBtboXRiUFLq0nLV?usp=drive_link)

These datasets should be added to the same folder as the notebook, or uploaded to local storage if using Google Colab (faster than mounting Google Drive) for the notebook to access them.  

If you are using an environment such as VS Code, you can open the terminal and install the required libraries using:


pip install -r requirements.txt

Model Accuracies
It is important to note that these accuracies may vary slightly due to factors such as random initialization, shuffling of the data, and other inherent randomness in the training process. The actual performance might vary by a small margin but should be close to these values.

Transfer Learning Model
The transfer learning model, built using MobileNetV3Large, typically achieves:

Average Validation Accuracy: Ranges from ~92% to ~95%
Test Accuracy: Ranges from ~91% to ~95%
Baseline Model
The baseline model is a simpler architecture used as a point of comparison. As expected, it performs with lower accuracy than the transfer learning model. During training, the baseline model typically achieves:

Validation Accuracy: Ranges from 59% to 68%
Test Accuracy: Ranges from 59% to 70%



