# Hello hardpy

This is the simplest example of using **HardPy**.
The code for this example can be seen inside the hardpy package [Hello Hardpy](https://github.com/everypinio/hardpy/tree/main/examples/project/hello_hardpy).

### how to start

1. Launch [CouchDH instance](../documentation/database.md#couchdb-instance).
2. Create a directory `<dir_name>` with the files described below.
3. Launch `hardpy-panel <dir_name>`.

### test_simple.py

Contains the simplest example of a valid test.

```python
import pytest

def test_one():
    assert True
```
