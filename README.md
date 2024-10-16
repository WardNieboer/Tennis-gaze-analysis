# Tennis-gaze-analysis
This repository contains Python code for analyzing gaze and ball coordinates in tennis trials. The analysis includes preprocessing of eye-tracking data, application of low-pass filters, saccade detection, and calculations of various angles and speeds related to ball movement and gaze behavior. The main goal is to investigate the gaze behaviour of tennis players.

Data organisation: [data_organisation.txt](https://github.com/user-attachments/files/17391567/data_organisation.txt)

Data extraction from eye-tracker video frames is available on: https://github.com/WardNieboer/tennis-ball-click-tool

Usage
  
  Select a Participant: Modify the participant variable in the code to specify the participant you want to analyze (e.g., participant = 'P1').  
  Run the Code: Execute the script in an environment that supports Python (e.g., Jupyter Notebook, PyCharm, or directly in the terminal).
  Results: The code will process the data, applying filters, detecting saccades, and calculating relevant metrics. Results, including average ball speed and saccade directions, will be printed in the terminal.
  Data Output: The processed results for each trial are stored in result_df_list, which contains dataframes with calculated values.

Functionality

  Data Loading: The code loads gaze and ball coordinates from Excel files.
  Data Preprocessing: Converts timing data to seconds and normalizes gaze coordinates.
  Low-Pass Filtering: Applies a Butterworth low-pass filter to smooth the gaze and ball coordinates.
  Saccade Detection: Detects saccades and analyzes gaze direction relative to the ball's movement.
  Angle and Speed Calculations: Calculates visual angles, ball speeds, head rotation, and gaze angles.

Contribution

Contributions to this project are welcome! If you would like to contribute, please fork the repository and create a pull request with your proposed changes.

