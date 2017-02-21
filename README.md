<h1 align="center">
  <img src="https://github.com/smartsight/smartsight-art/raw/master/logo/variants/engine/logo.png" alt="SmartSight Engine">
</h1>

> Engine for the SmartSight app in Python 3

SmartSight engine is an image recognition algorithm based on [Tensorflow](https://github.com/tensorflow/tensorflow) and trained on [ImageNet](http://www.image-net.org/) data set.

## Usage

```console
$ python classify.py --image_file <path to the image>

[
  {
    "class": "pizza, pizza pie",
    "score": 0.884148
  }, {
    "class": "butcher shop, meat market",
    "score": 0.002444
  }, {
    "class": "carbonara",
    "score": 0.00208
  }, {
    "class": "trifle",
    "score": 0.002078
  }, {
    "class": "pomegranate",
    "score": 0.001326
  }
]
```

## Install

### Create a virtual environment (optional)

If you use several Python versions on your computer, create a virtual environment with the Python 3 interpreter:

```console
$ virtualenv -p python3 venv
```

Activate the new environment:

```console
$ source venv/bin/activate
```

### Install dependencies

```console
$ pip install -r requirements.txt
```

## License

GPL © SmartSight
