To use spark simply login to the schulich ignite server [here](https://ignite.aranite.com/)

## The basics

1. Explain cells

2. Explain running cells

3. Explain the import boilerplate

```python
!pip install --upgrade schulich-ignite
import spark
%reload_ext spark
```

4. Explain cell boilerplate

```python
%%ignite

def setup():
    size(450, 600)

def draw():
    # loops forever and draws stuff
```

5. A list of the other pages of docs available with short descriptions, and a mention of the searchbarr in the top right
