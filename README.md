# Dog Breed Prediction Web App
- This is a Dog Breed Prediction app built using Streamlit and TensorFlow. The app allows you to predict the breed of a dog based on an uploaded image through a simple terminal interface.

## Features
- Dog Breed Prediction: Upload an image of a dog, and the app will predict its breed using a trained model.

- Model: A pre-trained TensorFlow model is used for dog breed classification.

- Supported Formats: PNG, JPG, and JPEG image formats.

# Technologies Used
* Streamlit: To build the web interface for the application.

* TensorFlow: For loading the pre-trained model and performing predictions.

* OpenCV: To handle image processing for input images.

# Setup Instructions

1. **Clone the Repository:**
**First, clone this repository to your local machine using Git.**
```
git clone https://github.com/yourusername/dog-breed-prediction.git
cd dog-breed-prediction
```

2. **Set Up Python Environment**
**To avoid conflicts with other projects, it’s a good practice to set up a virtual environment.**

```
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

3. **Install Required Libraries**
**Install the required Python libraries using pip.**

```
pip install -r requirements.txt
```

4. **Place the Pre-trained Model**
**Make sure you have the pre-trained model file (my_model.keras) in the project directory. If you don't have it, either train the model or download a suitable pre-trained model for the dog breeds.**

5. **Run the Streamlit App**
**Start the Streamlit app in the terminal by running:**
```
streamlit run app.py
```
# Usage
* Upload Dog Image: Click on the "Choose an image..." button to upload an image of a dog.

* Predict: After uploading, click the "Predict" button to get the breed prediction.

* Result: The breed name will be displayed in the app as the predicted breed.