# Automatic-Number-Plate-Recognition-YOLOv8

## Project Setup

* Make an environment with python using the following command 
``` bash
python -m venv pyenv
```
* Activate the environment
``` bash
.\pyenv\Scripts\activate
``` 
* Create Src & Output Folders 
``` bash
mkdir Src, Output
``` 
* Install the project dependencies using the following command 
```bash
pip install -r requirements.txt
```
* Run main.py with the sample video file to generate the test.csv file 
``` python
python main.py
```
* Run the add_missing_data.py file for interpolation of values to match up for the missing frames and smooth output.
```python
python add_missing_data.py
```
* Finally run the visualize.py passing in the interpolated csv files and hence obtaining a smooth output for license plate detection.
```python
python visualize.py
```
## Data
keep your video in Src folder and the output will be in Output folder
