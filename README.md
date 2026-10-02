# AI Tools Lab

A small Python project containing a sorting algorithm and a set of utility functions, built as part of the AI Tools and Applications Lab to practise Git, GitHub workflows and AI-assisted development.

## Features

- **Bubble sort** implementation with an early-exit optimisation (`sorting.py`)
- **Utility functions** with full docstrings (`utils.py`):
  - `is_palindrome(s)`: checks if a string is a palindrome, ignoring case, spaces and punctuation
  - `count_words(text)`: counts the words in a text
  - `celsius_to_fahrenheit(c)`: converts Celsius to Fahrenheit

## Installation

1. Make sure Python 3.8 or higher is installed:
```bash
   python --version
```
2. Clone the repository:
```bash
   git clone https://github.com/pulkitsharma24022008-art/ai-tool-lab.git
```
3. Move into the project folder:
```bash
   cd ai-tool-lab
```

No extra libraries are required.

## Usage

### Sorting

```python
from sorting import bubble_sort

numbers = [64, 34, 25, 12, 22, 11, 90]
print(bubble_sort(numbers))
# Output: [11, 12, 22, 25, 34, 64, 90]
```

### Utility functions

```python
from utils import is_palindrome, count_words, celsius_to_fahrenheit

print(is_palindrome("A man, a plan, a canal: Panama"))  # True
print(count_words("Hello AI Tools Lab"))                # 4
print(celsius_to_fahrenheit(100))                       # 212.0
```

You can also run each file directly:

```bash
python sorting.py
python utils.py
```

## Project Structure

```
ai-tool-lab/
├── README.md
├── hello.py
├── sorting.py
└── utils.py
```

## Contributors

- **Pulkit Sharma**: [@pulkitsharma24022008-art](https://github.com/pulkitsharma24022008-art)

Parts of this project, including the utility functions, docstrings and this README, were written with AI assistance (Claude) and reviewed by the author.

## License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2026 Pulkit Sharma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```