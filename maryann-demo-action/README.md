# Maryann Demo Action

This project is a simple web application that includes a contact form and a success page. It is designed to allow users to submit their contact information and receive confirmation of their submission.

## Project Structure

```
maryann-demo-action
├── src
│   ├── contactus.html      # HTML structure for the contact us page
│   ├── success.html        # HTML structure for the success page
│   └── lambda_function.py   # Python script to handle form submissions
└── README.md               # Documentation for the project
```

## Files Description

- **src/contactus.html**: This file contains the HTML structure for the contact us page. It includes a form for users to submit their contact information.

- **src/success.html**: This file contains the HTML structure for the success page. It is displayed after a successful form submission, confirming to the user that their submission was received.

- **src/lambda_function.py**: This file contains a Python script that defines a function to handle requests related to the contact form submission. It includes necessary imports for processing the request and sending responses.

## Setup Instructions

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open the `src` folder to access the HTML files and the Python script.
4. Ensure you have the necessary environment to run the Python script (e.g., AWS Lambda or a local server setup).

## Usage

- Open `contactus.html` in a web browser to view the contact form.
- Fill out the form and submit it to be redirected to the `success.html` page, which confirms your submission.

## License

This project is licensed under the MIT License.