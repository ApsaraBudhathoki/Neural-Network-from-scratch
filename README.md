# Neural Network Visualizer from scratch

This project is a simple neural network visualizer implemented in JavaScript. The neural network classifies points on a 2D plane into four quadrants using a feed-forward neural network. The visualization dynamically shows the structure of the network, including neurons, weights, and biases, with different colors based on their values.

## Features

- **Interactive Visualization:** The neural network structure (input, hidden, and output layers) is displayed, and the connections (weights) between layers are visualized with colors representing their magnitudes.
- **Dynamic Weights:** Weights are visualized with a gradient from green to red based on their values, with labels displaying the actual weight value.
- **Bias Visualization:** Biases for the hidden and output layers are displayed next to each neuron.
- **Point Classification:** Random points are generated and classified into four categories (blue, red, green, purple) based on their coordinates on the 2D plane.
- **Training Options:** The neural network can be trained dynamically, with adjustable parameters for learning rate, hidden nodes, and training iterations.
- **Visualization Options:** Adjust the number of points, hidden nodes, and other parameters to observe changes in the network's behavior.

## Usage

### Prerequisites

To run the visualization, you need a modern web browser that supports HTML5 Canvas and JavaScript.

### Running the Project

1. Clone the repository or download the files.

2. Open the `index.html` file in your preferred web browser.

3. Adjust the parameters (learning rate, hidden nodes, number of points, etc.) using the input fields.

4. Click **Initialize** to set up the neural network.

5. Click **Train** to train the neural network on the generated training data.

6. Click **Classify Points** to classify random points on the 2D plane using the trained network.

7. Click **Visualize Neurons and Weights** to see the neural network structure, including neuron activations and weight values.

### Parameters

- **Learning Rate:** Adjust the rate at which the network learns during training.
- **Hidden Nodes:** Set the number of hidden neurons in the network.
- **Training Iterations:** Set the number of iterations to train the network.
- **Number of Points:** Set the number of points to classify after training.
- **Training Data Size:** Set the number of points in the training dataset.

## Visualizing the Neural Network

- **Neurons:** The neurons in the input, hidden, and output layers are visualized with distinct colors. Input neurons are gray, hidden neurons are aqua, and output neurons are red.
- **Weights:** Weights between neurons are displayed as lines. The color of each line represents the weight's magnitude, ranging from green (positive) to red (negative).
- **Biases:** Bias values for neurons in the hidden layer are displayed next to each neuron.

## Files

- **index.html:** The main HTML file that contains the UI and canvas elements.
- **neural_network.js:** The main JavaScript file that contains the neural network logic and visualization functions.
- **style.css:** The CSS file that styles the UI elements and canvas.

## Example

Here's an example of how the network might look after training:

- Input neurons: Visualized as gray circles.
- Hidden neurons: Visualized as aqua circles.
- Output neurons: Visualized as red circles.
- Weights: Visualized as lines connecting neurons, with colors representing the weight values (green for positive, red for negative).
- Biases: Displayed next to neurons as numerical values.

## Customization

You can customize the network's structure by modifying the following parameters in the HTML file:

- **Number of Hidden Nodes:** Adjust the number of hidden neurons.
- **Learning Rate:** Set the learning rate for training.
- **Training Iterations:** Set the number of iterations for training.
- **Number of Points:** Change the number of points to classify.
- **Training Data Size:** Adjust the size of the training data.

## License

This project is open-source and available under the MIT License. Feel free to fork, modify, and use it in your own projects.

## Acknowledgments

This project was inspired by basic neural network implementations and aims to provide a simple yet powerful visualization tool for understanding neural networks.
