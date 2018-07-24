# geeznet
GeezNet is a Residual Network approach for Amharic Characters Recognition 
![oneshot task](images/task_25.png)
[koch et al, Siamese Networks for one-shot learning,](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)  (mostly) reimplimented in keras. 
Trains on the [My own Dataset]( https://github.com/isrugeek/geeznet/dataset).




## Installation Instructions


To run, you'll first have to clone this repo and install the dependencies

```bash
git clone https://github.com/isrugeek/geeznet
cd geeznet
#if you have enviroment workon [YOUR-ENVIROMENT-NAME]
sudo pip install -r requirements.txt

```


Then you'll need to import it and .
```bash
from habesha.geeznet import GeezNet
model = GeezNet.build(96, 96,
    numfidels=len(fidelLB.classes_),
    finalAct="softmax")
```
```bash
you need to use it as Trainer and Classifier
```

