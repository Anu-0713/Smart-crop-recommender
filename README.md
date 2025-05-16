🌾 Smart Crop Recommender
An intelligent crop recommendation system leveraging machine learning to assist farmers in selecting the most suitable crops based on soil and environmental conditions.

🚀 Features
User-Friendly Interface: Intuitive web application for seamless user interaction.

Machine Learning Model: Predicts the optimal crop based on input parameters.

Customizable Dataset: Easily update or expand the dataset for different regions or conditions.

Modular Codebase: Well-structured code for easy maintenance and scalability.

🖥️ Output Screen

![image](https://github.com/user-attachments/assets/460580bc-96e7-45a2-82bc-21ce99d32468)

The output screen displays the recommended crop based on the user's input parameters.

🧰 Technologies Used
Frontend: HTML, CSS

Backend: Python, Flask

Machine Learning: scikit-learn

Model Serialization: pickle

📂 Project Structure
cpp
Copy
Edit
Smart-crop-recommender/
├── static/
│   └── output_screen.png
├── templates/
│   └── index.html
├── app.py
├── model.pkl
├── requirements.txt
└── train_model.py
⚙️ Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Anu-0713/Smart-crop-recommender.git
cd Smart-crop-recommender
Create a Virtual Environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Application

bash
Copy
Edit
python app.py
Access the application at http://localhost:5000/ in your web browser.

📊 Dataset
The dataset includes the following features:


N: Nitrogen content in the soil

P: Phosphorus content in the soil

K: Potassium content in the soil

Temperature: Temperature in degrees Celsius

Humidity: Relative humidity in percentage

pH: pH value of the soil

Rainfall: Rainfall in mm


Note: Ensure the dataset is preprocessed and cleaned before training the model.

🧠 Model Training
The train_model.py script is used to train the machine learning model. It reads the dataset, preprocesses the data, trains the model, and saves it as model.pkl.

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes
