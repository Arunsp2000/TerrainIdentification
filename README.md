# Lower Limb Activity Recognition Data Description

This project is based on the publication [Lower Limb Activity Recognition Using Wearable Sensors](https://research.ece.ncsu.edu/aros/paper-tase2020-lowerlimb/). The dataset includes measurements from accelerometers and gyroscopes placed on the lower limb, along with corresponding activity labels. Here is a brief description of the files included in the dataset:

## File Descriptions

### Accelerometer and Gyroscope Data

The `_x` files contain sensor data from accelerometers and gyroscopes. The structure of these files is as follows:

- **First Column:** Timestamps (in seconds)
- **Next Three Columns:** XYZ accelerometer measurements
- **Final Three Columns:** XYZ gyroscope measurements

The data is sampled at a rate of 40 Hz.

### Activity Labels

The `_y` files contain activity labels corresponding to the sensor data. The structure of these files is as follows:

- **First Column:** Timestamps (in seconds)
- **Second Column:** Labels indicating the type of activity

The labels are defined as:
- **0:** Standing or walking on hard terrain
- **1:** Going down the stairs
- **2:** Going up the stairs
- **3:** Walking on soft terrain

The data is sampled at a rate of 10 Hz.

## Data Structure

Here is a summary of the data structure:

- **Timestamps:** Recorded in seconds.
- **Sampling Rates:**
  - Accelerometer and Gyroscope Data: 40 Hz
  - Activity Labels: 10 Hz

  
## Notes

- Ensure that the timestamps in the `_x` files and `_y` files are synchronized for accurate activity recognition.
- The difference in sampling rates (40 Hz for sensor data and 10 Hz for labels) should be considered when processing the data for analysis.

For more details on the dataset and its usage, refer to the publication [here](https://research.ece.ncsu.edu/aros/paper-tase2020-lowerlimb/).

