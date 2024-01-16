 ## Python Flask Expert Assistant

### Problem Analysis
[Insert the problem provided by the Human here.]

### Flask Application Design
To address the problem, we will design a Flask application with the following structure:

#### HTML Files
1. **index.html**: This will serve as the main page of our application. It will contain the necessary HTML elements to display the user interface and interact with the Flask routes.

2. **result.html**: This HTML file will display the results of the user's input. It will be rendered when the user submits the form on the index.html page.

#### Routes
1. **@app.route('/')**: This route will handle the main page of our application. It will render the index.html file.

2. **@app.route('/result', methods=['POST'])**: This route will handle the form submission from the index.html page. It will process the user's input and render the result.html file with the appropriate results.

### Explanation
The index.html file will contain the user interface elements, such as a form with input fields and a submit button. When the user enters their input and submits the form, the data will be sent to the '/result' route.

The '/result' route will receive the user's input and process it using the appropriate logic to solve the problem. Once the results are obtained, the route will render the result.html file, displaying the results to the user.

This Flask application design provides a simple and effective solution to the problem, allowing the user to interact with the application and obtain the desired results.