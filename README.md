## Smoke Detection Dataset
Detect smoke with the help of IOT data and trigger a fire alarm.

About the dataset Collection of training data is performed with the help of IOT devices since the goal is to develop a AI based smoke detector device. Many different environments and fire sources have to be sampled to ensure a good dataset for training. A short list of different scenarios which are captured:

- 1- UTC : The time when experiment was performed.
- 2- Temperature : Temperature of Surroundings. Measured in Celsius
- 3- Humidity : The air humidity during the experiment.
- 4- TVOC : Total Volatile Organic Compounds. Measured in ppb (parts per billion)
- 5- eCo2 : CO2 equivalent concentration. Measured in ppm (parts per million)
- 6- Raw H2 : The amount of Raw Hydrogen present in the surroundings.
- 7- Raw Ethanol : The amount of Raw Ethanol present in the surroundings.
- 8- Pressure : Air pressure. Measured in hPa
- 9- PM1.0 : Paticulate matter of diameter less than 1.0 micrometer .
- 10- PM2.5 : Paticulate matter of diameter less than 2.5 micrometer.
- 11- NC0.5 : Concentration of particulate matter of diameter less than 0.5 micrometers.
- 12- NC1.0 : Concentration of particulate matter of diameter less than 1.0 micrometers.
- 13- NC2.5 : Concentration of particulate matter of diameter less than 2.5 micrometers.
- 14- CNT : Simple Count.
- 15- Fire Alarm : If fire was present then value is 1 else it is 0.

### Getting Started
* **Prerequisites:**
  * Python 3.6+
  * numpy, pandas, scikit-learn, matplotlib
* **Creating a virtual environment:**
  ```bash
  python -m venv my_env
  ```
  Replace my_env with your desired environment name.
* **Activate the environment:**
  ```bash
  source my_env/bin/activate  # For Linux/macOS
  my_env\Scripts\activate  # For Windows
  ```
* **Installation:**
  ```bash
  pip install -r requirements.txt
  ```
### Acknowledgement / Credits
The data is collected by Stefan Blattmann in his project Real-time Smoke Detection with AI-based Sensor Fusion.
Author's GitHub : [Blatts01](https://github.com/Blatts01)
  
