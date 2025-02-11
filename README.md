# nanogpt

The code is a replication of the bigram character-level tokenized language model this specific model is the foundation of transformers to built upon for my 10,000 hour goal of AI studies. The model is trained on a dataset of text, and it can generate text based on the input it receives. The code is written in Python and uses the PyTorch library for training and inference. The model is designed to be simple and easy to understand, making it a great starting point for anyone interested in learning about language models and deep learning. 

### Installation
To install the required dependencies, run the following command in your terminal:
```bash
pip install torch numpy matplotlib
```###### Usage
To train the model, run the following command in your terminal:
```bash
python train.py --data-path path/to/your/dataset --model-name nanogpt --batch-size 64 --learning-rate 0.001 --epochs 1000``````To generate text using the trained model, run the following command in your terminal:
```bash
python generate.py --model-path path/to/your/trained/model --prompt "Once upon a time" --max-length 1000``````
### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### License
MIT