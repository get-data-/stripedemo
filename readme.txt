# This set of instructions assumes that you have installed Anaconda from https://www.continuum.io/downloads

# Create Python environment
$ conda create -n stripe python=3.4

# Activate Environment
$ activate stripe

# Install dependencies
$ pip install --upgrade stripe
$ pip install flask

# Navigate to directory where app.py sits
$ cd path/to/.../stripe

# start app
$ python app.py

# Navigate to site http://localhost:5000/


# Demo CC number
# 4242 4242 4242 4242
# any three digit CVC and any expiry date in the future.