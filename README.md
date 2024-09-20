# Aerial Landscape MSc Project Code. READ INSTRUCTIONS BELOW!

Before attempting to run the code, please download the following datasets:  

training dataset: https://drive.google.com/drive/folders/1GaOdVETCCDiH92ym8rLkZnH10ChMuEtE?usp=drive_link  

test dataset: https://drive.google.com/drive/folders/1AeqAznYLLQdcvZNttBtboXRiUFLq0nLV?usp=drive_link  

These datasets should be added to the same folder as the notebook, or uploaded to the local storage if using colab(faster than mounting google drive) in order for the notebook to access them. If you are using an environment such as vs code, you can open the terminal and install the required libraries using: pip install -r requirements.txt (Making sure to place the text file in the same folder as the notebook. Alternitvely you can open the text file and install these libraries manually. If you are using Google Colab, these libraries should work without any installiation.  

Once you have followed the above steps, proceed to run the cells in the notebook sequentially.  

Note that the proposed system is collapsed under the heading 'Transfer learning', whereas the model used to benchmark this system is collapse under 'Baseline model'  

# Model accuracies
it is important to note that these accuracies may vary slightly due to factors such as random initialization, shuffling of the data, and other inherent randomness in the training process. The actual performance might vary by a small margin but should be close to these values.  

Transfer Learning Model The transfer learning model, built using MobileNetV3Larg typically achieves:  

Average Validation Accuracy: Ranges from ~92% ~95% Test Accuracy: Ranges from ~91% ~95%   

Baseline Model The baseline model is a simpler architecture used as a point of comparison. As expected, it performs with lower accuracy than the transfer learning model. During training, the baseline model typically achieves:  

Validation Accuracy: Ranges from 59% to 68% Test Accuracy: Ranges from 59% to 70%  

# Video showing working code
Link: https://southwales.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=b09d65ee-569c-41e6-8946-b1f100022871  

#   A e r i a l - L a n d s c a p e - C o d e - M s c  
 