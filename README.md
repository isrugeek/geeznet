# geeznet
GeezNet is a Residual Network approach for Amharic Characters Recognition 

[The Project Abstract is can be found here](https://www.github.io/geeznet.pdf)  (mostly) implimented in keras backend with tensorflow. 
Trains on the [My own Dataset]( https://github.com/isrugeek/geeznet/dataset).

## This Project is Ongoing and it is not convinient to re-upload the Code Many times ! I promise I will Upload them Very soon


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

