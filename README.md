# Music classification
This is a classifier of music samples between 10 genres, based on the GTZAN dataset:
 - blues
 - classical
 - country
 - disco
 - hiphop
 - jazz
 - metal
 - pop
 - reggae
 - rock

It uses a customized CNN, reaching a test accuracy of ~80%. 

### Installation, usage
Install the project dependencies using the `requirements.txt` file (in a virtual environment):
```bash 
pip install -r requirements.txt
```

### Improvements
The loss function could be modified to penalize the model for misclassifying samples from genres which are known to be confused (eg. rock and metal). 
Further hyperparameter tuning could also be done. 