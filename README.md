# AutoCop
An automated vehicle policing application 


This is a Python application that recognizes car colors and license plates and matches them to a database using OpenCV and a custom machine learning algorithm.

Installation

Clone the repository: git clone https://github.com/your-username/car-recognition-app.git

Navigate to the project directory: cd car-recognition-app

Install the required packages: pip install -r requirements.txt

Download the pre-trained models for license plate detection and 
recognition from here and place them in the models directory.


Usage

Place the images of cars to be recognized in the input directory.

Run the application: python app.py

The application will recognize the car colors and license plates and match them to the database.

The results will be saved in the output directory.



How it Works


The application works as follows:

Load the pre-trained models for license plate detection and recognition.

Load the database of car colors and license plates.
For each image in the input directory:

Use OpenCV to detect the license plate in the image.

Use the license plate recognition model to recognize the characters on the license plate.

Use a custom machine learning algorithm to match the license plate to the database.

Use OpenCV to detect the color of the car in the image.

Save the results to a file in the output directory.
Customization

The following parameters can be customized in the config.py file:



DATABASE_FILE: 

The path to the database file.
LICENSE_PLATE_DETECTION_MODEL_FILE: The path to the license plate detection model file.

LICENSE_PLATE_RECOGNITION_MODEL_FILE: The path to the license plate recognition model file.

LICENSE_PLATE_SIZE: The size of the license plate to be recognized.

MIN_CONFIDENCE: The minimum confidence level required to match a license plate to the database.

CAR_COLOR_DETECTION_MODEL_FILE: The path to the car color detection model file.

