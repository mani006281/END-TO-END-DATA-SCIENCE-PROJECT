# END-TO-END-DATA-SCIENCE-PROJECT

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:PENUGONDA MANI KUMAR

*INTERN ID*:CTO6DF445

*DOMAIN*: DATA SCIENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SSANTOSH

This project is a simple web application built using Flask that helps predict whether a tumor is cancerous (malignant) or not (benign). It uses a machine learning model trained earlier to make this prediction. When the app runs, it loads the trained model and a scaler (used to standardize input values) from saved files. The app has a single endpoint (`/predict`) that listens for incoming data. When you send in the features of a tumor in JSON format, the app processes the data, runs it through the model, and sends back a result telling you whether it’s malignant or benign.

To build this project, we used Python for coding, Flask to create the web server, and Scikit-learn to train and save the machine learning model. The input and output are both in JSON format, which makes it easy to test using tools like Postman or curl. This kind of app is usually built and tested locally (on your computer), but it can also be deployed online using platforms like Heroku, Render, or Railway so others can access it too. This project is a great example of how machine learning can be combined with web development to create real-world applications.
