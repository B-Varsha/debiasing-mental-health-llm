# Mitigating Bias for Mental Health Analysis

This project reduces demographic bias in mental health AI models.

## Description

Large Language Models often encode and perpetuate demographic biases. This allows unfair outcomes in high stakes applications like suicide risk detection. We investigate bias in transformer based models using the CSSRS and Dreaddit datasets. Our work evaluates Counterfactual Data Augmentation and Adversarial Debiasing. We focus on fairness metrics including Equalized Odds Difference and Demographic Parity Difference. These methods help build fairer mental health AI systems.

## Getting Started

### Dependencies

* Python 3.8 or newer
* PyTorch
* Hugging Face Transformers
* Pandas
* NumPy
* Jupyter Notebook

### Installing

* Clone the repository to your local machine.
* Navigate to the project folder.
* Install the required packages via pip.

```bash
git clone [https://github.com/B-Varsha/debiasing-mental-health-llm](https://github.com/B-Varsha/debiasing-mental-health-llm)
cd debiasing-mental-health-llm
pip install -r requirements.txt

```
### Executing program

* Open the specific Jupyter Notebook for the dataset and method you want to run.
* Run the cells strictly in order.
* Use `Model_training_CSSRS.ipynb` for the baseline CSSRS model.
* Use `CDA_CSSRS.ipynb` for Counterfactual Data Augmentation on CSSRS.
* Use `AdversarialDebiasingCSSRS.ipynb` for the adversarial method on CSSRS.

```bash
jupyter notebook Model_training_CSSRS.ipynb
```

