# Nurtur-prediction
The source code of machine learning model's API of Nurtur smart guide in order to complete Bangkit Capstone Project

# How to run this Flask app
- Clone this repo
- Open terminal and go to this project's root directory
- Type `python -m venv .venv` and hit enter
- In Linux, type `source .venv/bin/activate`
- In Windows, type `.venv\Scripts\activate`
- Type `pip install -r requirements.txt`
- Serve the Flask app by typing `flask run`
- It will run on `http://127.0.0.1:5000`

# How to predict image with Postman
- Open Postman
- Enter URL request bar with `http://127.0.0.1:5000/predict`
- Select method POST
- Go to Body tab and select form-data
- Change key from form-data with file (it must be named `image`)
- Input the image that you want predict as a value of the key
- Send the request

![TestLocalAPIML](https://github.com/Nurtur-Capstone-Project/Nurtur-prediction/assets/85015643/57aa27a8-924f-4c49-a36c-037fb3bfe22c)
![ssmlLocal](https://github.com/Nurtur-Capstone-Project/Nurtur-prediction/assets/85015643/b9f2f34b-f8ba-4703-b681-b4fea7046f95)
