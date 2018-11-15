# train

![bunny training](bunny.gif)

# Usage:

```Python
from train import train
import time

# simulate long training epoch
def train_epoch():
	time.sleep(0.3)

# training loop
epochs = range(1, 50)
for epoch in train(epochs):  # use bunny like tqdm
	train_epoch()
```

# Installation

```
pip install git+git://github.com/motmaytinh/train
```
