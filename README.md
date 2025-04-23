# SKV AI

**SKV AI** is a Python package designed to simplify machine learning tasks like image classification, regression, and general classification. With simple functions, it allows users to load data, train models, and output results easily.

## Installation

To install `skvai` package, use pip:

```bash
pip install skvai
```
👨‍💻 Author
Sivakandasamy velumani
SKV AI is developed as part of ongoing ML toolkits to accelerate model prototyping for students and developers.

## Features
* Image Classification (using CNNs)
* Regression (using linear models)
* Classification (using logistic regression)
* Easy-to-use interface for common machine learning tasks

## Usage Example
```python
from skvai.tasks.classification import Task

# Load the dataset
task = Task()
task.load_data('data.csv')

# Train and get output
task.train_and_output('graph')
```# skvai




