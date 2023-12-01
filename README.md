# elk_data_python_process
The following repo houses a jupyter notebook for performing experimental geospatial data analysis.
The notebook elk_data_python_demo.ipynb goes into detail of what we hope to accomplish.
By working through this notebook you will learn how to enrich a CSV file containing tracked elk locations with data from other sources to help in understanding the behavior of the animals being tracked.


To work with this notebook it will help to run it from a virtual environment so the dependencies are available.  
Setting-up the virtual environment can be done from the terminal on osx and linux with the following commands:
```
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
# now open Jupiter lab with your virtual environment running and updated with then necessary requirements
jupyter lab
```
