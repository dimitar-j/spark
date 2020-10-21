*Below is a list of all of the shapes available for drawing within spark.*

All of the examples below assume you already have a cell at the top with:

```python
!pip install --upgrade schulich-ignite
import spark
%reload_ext spark
```

### Rectangle

To create a rectangle use:

```python
fill_rect(x, y, w, l)
```

**Parameters**

- x: (int or float) The value of the x position of the rectangle
- y: (int or float) The value of the y position of the rectangle
- w: (int or float) The width of the rectange
- l: (int or float) The length of the rectange

#### Example:

Creating a rectangle at (100, 100) with a width of 75, and length of 50


```python
%%ignite

def setup():
    size(200, 200)

def draw():
    fill_rect(100, 100, 75, 50)
```

Results in:

![fill_rect() example](./img/fill_rect.png)

### Circle

To create a circle use:

```python
fill_circle(x, y, r)
```

**Parameters**

- x: (int or float) The value of the x position of the rectangle
- y: (int or float) The value of the y position of the rectangle
- r: (int or float) The radius of the circle

#### Example:

Creating a circle at (100, 100) with a radius of 75


```python
%%ignite

def setup():
    size(200, 200)

def draw():
    fill_circle(100, 100, 75)
```

Results in:

![fill_circle() example](./img/fill_circle.png)
