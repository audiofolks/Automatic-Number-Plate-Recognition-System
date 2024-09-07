Automatic-Number-Plate-Recognition-YOLOv8
Project Setup

    Create a Python Environment:

    bash

python -m venv pyenv

Activate the Environment:

bash

.\pyenv\Scripts\activate

Create Required Folders:

bash

mkdir Src Output

Install Project Dependencies:

bash

pip install -r requirements.txt

Run the Main Script:

    This will process the sample video and generate test.csv.

bash

python main.py

Interpolate Missing Data:

    This step smooths out the data to match frames.

bash

python add_missing_data.py

Visualize the Results:

    Pass the interpolated CSV files to generate smooth license plate detection output.

bash

    python visualize.py

Data

    Place your video files in the Src folder.
    The processed output will be saved in the Output folder.