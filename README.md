# ECE 239AS Final Project
Data is located in /data, and is made publically available through the following [competition](http://www.bbci.de/competition/iv/). You can find a description of how the data is organized [here](http://www.bbci.de/competition/iv/desc_2a.pdf). Data is preprocessed using MATLAB code provided by [Professor Jonathan Kao (UCLA)](http://www.ee.ucla.edu/jonathan-kao/) for the course ECE239AS.  

Code is located in /notebooks

To run:
```
virtualenv .
source bin/activate
pip install ipykernel
pip install -r requirements.txt
ipython kernel install --user --name=ece239
jupyter notebook
```
Then select the ece239 kernel to use when running the Jupyter notebook files
