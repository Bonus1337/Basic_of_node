# Basic Node.js Calculator & BMI Calculator

This project is an introductory hands-on experience for students learning Node.js. It consists of two basic applications - a simple arithmetic calculator and a BMI calculator, both built using Node.js and Express.js.

## Installation

To set up this project, follow the steps below:

1. Install Node.js and npm (node package manager) on your system. If you have not installed these, you can download them [here](https://nodejs.org/en/download/).

2. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

3. Navigate into the directory of the project:

```bash
cd your-repo-name
```

4. Install the dependencies:

```bash
npm install
```

This command installs the express and body-parser packages which are required for this project.

## Usage

Start the server by running the following command in your terminal:

```bash
node calculator.js
```

Once the server is running, you can interact with the applications through a web browser.

- Navigate to `http://localhost:3000` to access the arithmetic calculator.
- Navigate to `http://localhost:3000/bmicalculator` to access the BMI calculator.

## File Structure

This project consists of three main files:

- `calculator.js`: This is the entry point file which contains all the server-side code, including serving of the HTML files and processing of POST requests.

- `index.html`: This is the HTML file for the arithmetic calculator, which contains a form for the user to input two numbers and see the result of their addition.

- `bmiCalculator.html`: This is the HTML file for the BMI calculator, which contains a form for the user to input their weight (in kilograms) and height (in meters), and calculates their Body Mass Index (BMI).

## Learning Outcomes

Through this project, students can learn and understand the following concepts:

- The basics of Node.js and how to set up a Node.js project
- Using Express.js to handle routing and server HTTP requests
- Serving static files using Express.js
- Using the body-parser middleware to parse incoming request bodies
- Handling GET and POST requests
- The basics of HTML form handling in conjunction with a backend server

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
