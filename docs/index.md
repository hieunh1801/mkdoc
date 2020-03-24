# Hello World

```py
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello_world:
    return "Hello World"

app.run(debug=True)
```

!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.