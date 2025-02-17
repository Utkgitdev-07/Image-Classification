# Image-Classification-Streamlit
This project is a deep learning-based image classification application built using Streamlit. The model is trained to classify images of flowers. The web application allows users to upload test images and get predictions in real time.



It classifies the given image of a flower into one of the following five categories :-  
1. Daisy
2. Dandelion
3. Rose
4. Sunflower
5. Tulip

## Folder structure

Image-Classification-Streamlit/
│── flower_photos/                # Dataset folder containing images for training  
│   ├── class_1/                  # Example class folder  
│   ├── class_2/                  # Example class folder  
│   ├── ...  
│  
│── test_images/                   # Folder containing test images  
│   ├── test_1.jpg  
│   ├── test_2.jpg  
│   ├── ...  
│  
│── misc/                          # Folder containing working screenshots  
│   ├── screenshot_1.png  
│   ├── screenshot_2.png  
│   ├── ...  
│  
│── app.py                         # Streamlit application file  
│── flower_model_trained.hdf5      # Trained model file  
│── model_final.ipynb              # Jupyter Notebook for model training   
│── README.md                      # Project description  


## Commands

To run the app locally, use the following command :-  
`streamlit run app.py`  

The webpage should open in the browser automatically.  
If it doesn't, the local URL would be output in the terminal, just copy it and open it in the browser manually.  
By default, it would be `http://localhost:8501/`  

Click on `Browse files` and choose an image from your computer to upload.  
Once uploaded, the model will perform inference and the output will be displayed.  

## Output

<img src ='misc/sample_home_page.png' width = 700>  

<img src ='misc/sample_output.png' width = 700>


## Notes
* A simple flower classification model was trained using TensorFlow.  
* The weights are stored as `flower_model_trained.hdf5`.  
* The code to train the modify and train the model can be found in `model.py`.  
* The web-app created using Streamlit can be found in `app.py`


## References

* https://www.tensorflow.org/tutorials/images/classification
* https://docs.streamlit.io/en/stable/
