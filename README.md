# Non-linear dynamics of outdoor walking 
Code to calculate the non-linear dynamics analysis of walking on various surfaces from a single IMU placed on the lower back
presented in the paper: 

Emmerzaal, J., Ippersiel, P., & Dixon, P. C. (2025). Non-Linear Gait Dynamics Are Affected by 
Commonly Occurring Outdoor Surfaces and Sex in Healthy Adults. Sensors, 25(13), 4191. https://doi.org/10.3390/s25134191

## Pre-requisites 
cd to the root folder containing the main.py in the terminal or command window, and run the following commands:

```python
conda create -n nld_surfaces python=3.10 -y
```

```python
conda activate nld_surfaces
```

```python
pip install -r requirements.txt
```

## Run the provided python script

The run the python script, use the command <code>python main.py</code>  where <code>main.py</code> is the specific python file. 

<code>main.py</code> will extract the data from the ``data.json.zip`` file, create the file and folder structure required for the non-linear dynamics analysis. 
It will write the final output into a .csv file.




