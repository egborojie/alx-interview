# Pascal's Triangle Generator

This Python project generates Pascal's triangle up to a specified number of rows.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Pascal's triangle is a mathematical construct that consists of an infinite number of rows of integers. The first few rows of Pascal's triangle look like this:


This project provides a Python function to generate Pascal's triangle up to a specified number of rows. The function returns a list of lists, where each list represents a row of the triangle.

## Installation

To use this project, you'll need Python installed on your system. You can download Python from the [official website](https://www.python.org/downloads/).

1. Clone this repository to your local machine using the following command:

git clone https://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@github.com/egborojie/alx-interview.git 

2. Navigate to the project directory:

3. You can now use the `pascal_triangle` function in your Python scripts or projects.

## Usage

To generate Pascal's triangle, use the `pascal_triangle` function as follows:

```python
from pascal_triangle import pascal_triangle

# Specify the number of rows you want in the triangle
n = 5

# Generate Pascal's triangle
triangle = pascal_triangle(n)

# Now you can work with the `triangle` variable
from pascal_triangle import pascal_triangle

def print_triangle(triangle):
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

n = 5
triangle = pascal_triangle(n)
print_triangle(triangle)


