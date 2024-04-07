# Python Web Spider

This project contains a simple web spider written in Python. It uses `venv` for environment management.

## Prerequisites

- Python 3.10.13
- pip

## Setup

1. Clone the repository:

```bash
git clone https://github.com/blackg33/python-spider-boilerplate.git
cd python-spider-boilerplate
```

2. Create a virtual environment
```bash
python3 -m venv venv
```

3. Activate the virtual environment:
On Unix or MacOS, run:
```bash
source venv/bin/activate
```
On Windows, run:
```bash
.\venv\Scripts\activate
```

4. Install the required packages:
```bash
pip install -r requirements.txt
```

Running the Spider
To run the spider, use the following command:
```bash
scrapy runspider spider.py
```
Replace spider.py with the name of your spider script.

Deactivating the Virtual Environment
When you're done, you can deactivate the virtual environment by running:
```bash
deactivate
```
This will stop the shell session from using the virtual environment and return to using the system-wide Python interpreter and packages.