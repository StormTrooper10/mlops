# mlops

for python virtual environment:
python -m venv venv
which python
cd venv
cd Scripts
activate

in requirements.txt:

black
pylint
pytest
pytest-cov

test.py

def add(a, b):
    return a + b

def sub(a,b):
    return a-b

from main import add, sub

def test_add():
    assert 4 == add(2,2)
    
def test_sub():
    assert 3 == sub(5,2)


