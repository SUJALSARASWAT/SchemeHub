
# SchemeHub – AI-Powered Financial Scheme Identifier for India Post

SchemeHub is an innovative AI-based system that dynamically identifies and recommends financial schemes (banking & insurance) tailored to individual users based on their demographic and economic profiles. Leveraging machine learning, the project enhances financial inclusion and engagement by providing personalized financial recommendations through India Post.

## 🎯 Features

- **Personalized Financial Recommendations**: Recommends banking and insurance schemes based on user demographics (age, income, occupation, etc.) and seasonal economic cycles.
- **AI-Powered Predictions**: Utilizes machine learning models (LR, RF, GB, LSTM) combined with a Voting Regressor for accurate financial need prediction.
- **Time-Based Recommendations**: Adjusts recommendations based on the user's current economic situation, such as seasonal income variations and farming cycles.
- **Handling Unseen Data**: Efficiently handles new or unseen demographic data points using custom fallback mechanisms.
- **User-Friendly Interface**: Simple interface to interact with and get personalized scheme recommendations.

## 💻 Technologies Used

- **Languages**: Python, React, Node.js, Express.js, MongoDB
- **Libraries/Frameworks**: TensorFlow, Keras, Scikit-learn, Pandas, GIS Tools
- **Cloud & Deployment**: AWS, Docker, Flask/FastAPI
- **Other Tools**: MinMaxScaler, One-Hot Encoding, Voting Regressor

## 📋 Requirements

Before running the application, ensure the following are installed:

- Python 3.x
- pip
- MongoDB (for database management)
  
Install the required Python packages using the command:

```bash
pip install tensorflow scikit-learn pandas flask fastapi
```

## 🚀 Getting Started

Clone the Repository:

```bash
git clone https://github.com/yourusername/SchemeHub
```

Change into the Project Directory:

```bash
cd SchemeHub
```

Run the Application:
Ensure you have MongoDB running and then start the application:

```bash
python app.py
```

## 🎮 Using the Application

- Input demographic and economic details such as age, occupation, income, and location.
- The system will predict and recommend financial schemes.
- You will receive personalized recommendations based on your current needs.

## 🖌️ Contributing

We welcome contributions! Feel free to fork the repository, submit pull requests, and share your improvements.

For any issues, please open an issue on GitHub.
```

### Fixes made:
1. **Closing the code block** for the `pip install` command.
2. **Minor formatting consistency** in the markdown.

This version is now ready for use.
