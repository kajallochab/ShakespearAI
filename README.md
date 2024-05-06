# ShakespearAI: Generating Shakespearean Text with LSTM Neural Networks

This repository contains code and a research paper for generating Shakespearean-style text using Recurrent Neural Networks (RNNs) with Long Short-Term Memory (LSTM) architecture.

## Overview

The project aims to develop a computational model capable of generating text in the style of William Shakespeare. By training an LSTM-based neural network on a dataset of Shakespearean texts, the model learns to capture the linguistic nuances and stylistic elements characteristic of Shakespeare's writing. The resulting model can then be used to generate new text that closely resembles the eloquent prose and poetry of the Bard.

## Project Workflow

1. **Data Collection and Preprocessing**: Obtain a dataset of Shakespearean texts, clean and preprocess the data to prepare it for training.
   
2. **Model Training**: Train the LSTM model on the preprocessed dataset, fine-tuning hyperparameters and optimizing training procedures as needed.

3. **Text Generation**: Use the trained model to generate new text samples in the style of Shakespeare, evaluating the quality and coherence of the generated output.

4. **Evaluation and Analysis**: Assess the performance of the model through various metrics and qualitative analysis, comparing the generated text against authentic Shakespearean works.

## Code

The `code/` directory contains Python scripts for training the model, generating text, and evaluating performance. Detailed instructions for running the code are provided in the respective files.

### Prerequisites

- Python 3
- TensorFlow
- Keras
- Other required libraries (specified in requirements.txt)

### Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the training script to train the model on the provided dataset.
4. Use the provided scripts to generate new text based on the learned patterns.

## Research Paper

The `paper/` directory contains the LaTeX source files for the accompanying research paper. The paper provides detailed information on the methodology, experiments, findings, and future work related to the Shakespearean text generation project.

## Future Work

- **Fine-Tuning and Optimization**: Further optimize the model architecture and training procedures to enhance the quality of generated text.
- **Interactive Text Generation**: Develop interactive systems that allow users to specify constraints and preferences for text generation, enabling more customized outputs.
- **Extension to Other Literary Styles**: Apply the proposed approach to other languages and literary styles, exploring the computational modeling of cultural and historical materials.

## Citation

If you use the code or findings from this repository in your research, please cite the accompanying research paper:

[Author(s), "Title of the Paper", Conference/Journal Name, Year]

## License

This project is licensed under the [MIT License](LICENSE).
