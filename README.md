Hate Speech Detection Web App

This project is a web application that uses machine learning to detect hate speech and offensive language in text. Users can enter text and receive a prediction on whether the text contains hate speech, offensive language, or neither. The application is built with Flask and hosted on Heroku.
Demo

You can try out the web app at https://hate-speech-detection-web-app.vercel.app/.

A blog post about this project is available on my website.
Installation

To install and run the web app locally, follow these steps:

    Clone the repository: git clone https://github.com/ALVINdimpos/Hate-Speech-Detection-Web-App.git
    Navigate to the project directory: cd hate-speech-detector
    Create a virtual environment: python -m venv env
    Activate the virtual environment:
        Windows: .\env\Scripts\activate
        Unix/MacOS: source env/bin/activate
    Install the required packages: pip install -r requirements.txt
    Start the Flask app: python app.py
    Open your web browser and go to http://localhost:5000

Usage

To use the web app, follow these steps:

    Enter text in the input box on the home page.
    Click the "Submit" button to get a prediction on whether the text contains hate speech, offensive language, or neither.
    The results will be displayed on the results page, along with the probability of each prediction.

Contributing

Contributions to this project are welcome. To contribute, follow these steps:

    Fork the project repository.
    Create a new branch: git checkout -b my-branch-name
    Make your changes and commit them: git commit -am 'Add some feature'
    Push to the branch: git push origin my-branch-name
    Create a pull request.

Related projects

Here are some related projects you may be interested in:

    Toxic Comment Classification: A machine learning model for classifying toxic comments.
    Sentiment Analysis Web App: A web application for analyzing the sentiment of text.

Licensing

This project is licensed under the MIT License. See the LICENSE file for details.
Screenshots

Here are some screenshots of the web app:

Home Page
![Screenshot of My App](https://github.com/ALVINdimpos/Hate-Speech-Detection-Web-App/blob/main/assets/home.PNG)


Results Page
![Screenshot of My App](https://github.com/ALVINdimpos/Hate-Speech-Detection-Web-App/blob/main/assets/result.PNG)
