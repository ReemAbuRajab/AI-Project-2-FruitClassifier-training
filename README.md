# Fruit Classifier Setup Instructions

## Prerequisites

Make sure you have Node.js and npm installed on your system. You can download them from [Node.js official website](https://nodejs.org/).

## Installation

1. Clone the repository or download the source code to your local machine.
2. Navigate to the project directory in the terminal.
3. Run the following command to install the dependencies:

```bash
npm install
```

## Starting the Application

To start the application, run the following command in the terminal:

```bash
npm start
```

This will start the server, and you should see the message "Fruit Classifier app listening at http://localhost:3000" indicating that the server is running.

## Accessing the Application

Open your web browser and go to `http://localhost:3000` to access the Fruit Classifier application.

## Training the Model

To train the model, use the following suggested input data and configuration in the training form on the web interface:

### Input Data (Features)

```json
[
  {"sweetness": 5, "color": 1},
  {"sweetness": 7, "color": 2},
  {"sweetness": 6, "color": 3}
]
```

### Configuration Parameters

- Number of Neurons in Hidden Layer: `9`
- Activation Function for Hidden Layers: `ReLU`
- Activation Function for Output Layer: `Sigmoid`
- Learning Rate: `0.05`
- Maximum Number of Epochs: `100`
- Goal: `0.01`

## Making Predictions

After training the model with the above data, you can make predictions by entering new input data in the prediction form:

### Example Input for Prediction

```json
{"sweetness": 5, "color": 1}
```

Replace the above JSON with the values for the fruit you want to predict.
