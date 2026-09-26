# Python Internship Tasks

Work completed during my internship at **Yuzhny Gerion** («Южный Герион», MAGIKA office):

- **Python tasks** (2023): 23 standalone scripts in the repository root; the task statement is included as a comment in each file.
- **[Neural networks from scratch](#neural-networks-from-scratch)** (2024): exercises in the `neural-network-book/` folder.

## Python tasks

| # | Task | Topics |
|---|---|---|
| [1](1.py) | Print all list elements less than 5 | lists, loops |
| [2](2.py) | Find the common elements of two lists | lists, counting |
| [3](3.py) | Sort a dictionary by value, ascending and descending | dicts, `sorted`, lambda |
| [4](4.py) | Merge several dictionaries | dicts, `\|` operator |
| [5](5.py) | Find the three keys with the highest values | dicts, sorting |
| [6](6.py) | Convert a number from a given base | `int(str, base)` |
| [7](7.py) | Print the first *n* rows of Pascal's triangle | nested lists |
| [8](8.py) | Check whether a string is a palindrome | strings |
| [9](9.py) | Format seconds as `days:hours:minutes:seconds` | integer arithmetic |
| [10](10.py) | Build a list and a tuple from comma-separated input | input parsing, tuples |
| [11](11.py) | Print the first and last elements of a list | indexing |
| [12](12.py) | Print a file's extension | string search |
| [13](13.py) | Compute `n + nn + nnn` | strings ↔ integers |
| [14](14.py) | Print even numbers until a stop value is reached | loops, `break` |
| [15](15.py) | Elements of the first list that are not in the second | sets |
| [16](16.py) | List the files in a directory | `os` |
| [17](17.py) | Sum the digits of an integer | `%` and `//` |
| [18](18.py) | Count occurrences of a character in a string | strings |
| [19](19.py) | Swap two variables | assignment |
| [20](20.py) | Extract numbers divisible by 15 with an anonymous function | `filter`, lambda |
| [21](21.py) | Check whether all numbers in a sequence are unique | sets |
| [22](22.py) | Find the most frequent and the longest word in a text | `Counter`, text processing |
| [23](23.py) | *(empty placeholder)* | |

## How to run

```bash
python 7.py
```

Most scripts read input from the console. Python 3.9+ is required (task 4 uses the dict union operator).

## Neural networks from scratch

Exercises following Tariq Rashid's book *Make Your Own Neural Network*: a three-layer neural network implemented with NumPy only, trained on MNIST handwritten digits.

| Notebook | Content |
|---|---|
| `neural-network-book/1задания до нейронки.ipynb` | Python and NumPy warm-up exercises |
| `neural-network-book/ckelet.ipynb` | Network skeleton: initialisation, weights, forward pass, training |
| `neural-network-book/dataminist.ipynb` | Loading and normalising MNIST data, visualising digits |
| `neural-network-book/216.ipynb` | Full pipeline, including testing on my own handwritten digit images |
| `neural-network-book/итогиyfdthyjt.ipynb` | Final version trained on the full dataset |
| `neural-network-book/вращайвращай.ipynb` | Data augmentation with rotated images |
| `neural-network-book/нейросетьнаоборот.ipynb` | Backward query: generating the image the network "imagines" for each digit |
| `neural-network-book/numbers-classification-pytorch-for-beginners.ipynb` | Digit classification with PyTorch |

The notebooks based on the book's code keep its original attribution; the book's code is published by its author under the GPLv2 license.

## License

[MIT](LICENSE)
