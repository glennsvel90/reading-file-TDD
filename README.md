# reading-file-TDD
A project to explore TDD(Test-Driven Development) using test doubles in unit tests with the MagicMock class and pytest Monkeypatch test fixture. Mock objects were created to pass two tests. The first test was to read from a file and return the correct string. The second test was to read from a file and throw an exception when the file doesn't exist. For both tests to pass, the first test had code that made the file exist, while the second test had code that made the file not exist.


### Prerequisites

 * Python 3
 * Import the pytest python package with by typing in the terminal:
 
```
pip install pytest
```

### Testing the program

In the terminal, change to the directory where the TestCheckout.py file is located in, then type:

```
pytest -v TestDoubles_Tests.py
```
