Ensure that conda is loaded on your computer by using brew (if mac) or apt-get (if linux). Then run the following command, to load the dependencies into a conda environment.
```
$ conda env create -f environment.yml
```
Then, activate the environment:
```
$ source activate carnd-term1
```
Next you would want to run Jupyter, to get your environment set up properly and navigate to http://<your-instance-ip>:8888 in the browser.

```
$ juptyer notebook &
```

Sail away!
