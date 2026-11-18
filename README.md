# machine-learning

Simple neural-network implementations in **pure Python**, with no NumPy, written for learning the basics.

> Fork of [mheronanh/machine-learning](https://github.com/mheronanh/machine-learning).

## Contents

| File | What it does |
|---|---|
| `matrix_lib.py` | Small `Matrix` class (random init, add, multiply, transpose, element-wise map) used by the networks below |
| `single_layer_perceptron.py` | Single perceptron (step activation) trained with the perceptron rule on the **AND** gate |
| `multi_layer_perceptron.py` | 2-2-1 multilayer perceptron with sigmoid activation and backpropagation, trained on **XOR** |
| `autoassociative_network.py` | Autoassociative (Hebbian) memory with `hardlims` activation that recalls 5×6 bipolar digit patterns from a noisy input and saves the input and recalled grid as PNG images |

## Requirements

- Python 3
- `matplotlib`, only for `autoassociative_network.py`

## Usage

Each script runs its demo when executed:

```bash
python single_layer_perceptron.py   # prints weights per epoch and the predictions for AND
python multi_layer_perceptron.py    # prints the XOR outputs after 5000 epochs
python autoassociative_network.py   # writes "Test Data.png" and "Recognition.png"
```
