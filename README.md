# Machine-Learning-Naive-Bayes-Project-0

# Gauss Naive Bayes Classifier

This is a simple implementation of Gaussian Naive Bayes Classifier, which is a probabilistic algorithm used in classification tasks. This implementation assumes that the features are independent and normally distributed. It is suitable for small to medium-sized datasets and can be used for both binary and multiclass classification problems.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/gaussian-naive-bayes.git
```

2. Navigate to the directory:

```bash
cd gaussian-naive-bayes
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Prepare your dataset. The dataset should be in a CSV file, where the first row contains the column names and the last column contains the labels.

5. Train the model:

```bash
python train.py --dataset path/to/dataset.csv
```

This will train the model on the dataset and save the model to a file named model.pkl.

6. Make predictions:

```bash
python predict.py --input path/to/input.csv --output path/to/output.csv --model path/to/model.pkl
```
This will make predictions on the input dataset and save the predictions to the output file.
