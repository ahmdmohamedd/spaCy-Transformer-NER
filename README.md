# Named Entity Recognition with spaCy and Transformers
This project demonstrates Named Entity Recognition (NER) using spaCy 3 and transformers in Google Colab. It covers data loading, preprocessing, model training with a custom config, evaluation, and prediction visualization. The model is trained on the CoNLL-2003 dataset and evaluated using common NER metrics.

## Project Structure

*   `Transformer_Based_NER.ipynb`: The main Jupyter Notebook containing the code for the project.
*   `eng.train`, `eng.testa`, `eng.testb`: CoNLL-2003 dataset files for training, development, and testing.
*   `config.cfg`: Configuration file for training the spaCy NER model.
*   `output/`: Directory where the trained model is saved.

## Getting Started

1.  Open the `NER_with_spaCy_and_Transformers.ipynb` notebook in Google Colab.
2.  Run the code cells sequentially to load the data, preprocess it, train the model, and evaluate its performance.
3.  The notebook includes visualizations of the predicted entities on sample text.

## Dependencies

*   spaCy 3
*   Transformers
*   tqdm

You can install these dependencies using `pip`:

bash pip install spacy transformers tqdm

 
## Dataset

The project uses the CoNLL-2003 dataset, which is a standard benchmark for NER tasks. The dataset is included in the repository.

## Model

The NER model is trained using spaCy's transformer-based pipeline. A custom configuration file (`config.cfg`) is used to define the model architecture and training parameters.

## Evaluation

The model is evaluated on the test set using standard NER metrics such as precision, recall, and F1-score. The evaluation results are printed in the notebook.

## Contributing

Contributions to this project are welcome. Feel free to open issues or pull requests.
