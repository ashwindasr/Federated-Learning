# Federated-Learning

#####        A cats and dogs classifier trained using Federated Learning and deployed using PyTorch and PySyft.

#### What is Federated Learning?
  [Federated learning](https://en.wikipedia.org/wiki/Federated_learning) enables multiple actors to build a common, robust machine learning model without sharing data, thus addressing critical issues such as data privacy, data security, data access rights and access to heterogeneous data. Check out Google's [online comic](https://federated.withgoogle.com) or [blog post](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html) for more details.

#### Installation

  This notebook uses [PyTorch](https://pytorch.org/) and [PySyft](https://github.com/OpenMined/PySyft). 
To install Pytorch on your device, follow the instructions [here](https://pytorch.org/get-started/locally/). If you're using [Google Colab](https://colab.research.google.com/), PyTorch come pre-installed.<br /><br />
To install PySyft, run the commands:
```python
git clone https://github.com/OpenMined/PySyft.git
python ./PySyft/ setup.py test
pip install syft
```
