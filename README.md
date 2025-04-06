# Data Quality Assessment and Enhancement for Sustainable Water Management In IoT-Enabled Peackeeping Missions.

This repository contains code and documentation used for my Masters Thesis.

---

The methodology has been converted to a Python package here: https://github.com/jeafreezy/iot-dqa

## Usage

### Open In Colab

- Exploratory Data Analysis - <a target="_blank" href="https://colab.research.google.com/github/jeafreezy/masters-thesis/blob/main/notebooks/EDA.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


- Data Quality Assessment - <a target="_blank" href="https://colab.research.google.com/github/jeafreezy/masters-thesis/blob/main/notebooks/Data%20Quality%20Assessment.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- Data Quality Enhancement - <a target="_blank" href="https://colab.research.google.com/github/jeafreezy/masters-thesis/blob/main/notebooks/Data%20Quality%20Enhancement.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- Post Enhancement Assessment - <a target="_blank" href="https://colab.research.google.com/github/jeafreezy/masters-thesis/blob/main/notebooks/Post%20Enhancement%20Assessment.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### Manual Installation

1. Clone the Repository:

```bash
    git clone https://github.com/jeafreezy/master-thesis.git
    cd thesis-code-repo
```

2. Set up the Python Environment: It is recommended to use a virtual environment such as [Pipenv](https://pipenv.pypa.io/en/latest/):

```bash
   # Create a new environment variable.
   pipenv shell
   # Install the dependencies
   pipenv install
```

3. Start the notebook server.


```bash
   jupyter-lab .
```

## Dataset

The dataset can not be distributed here; however, below is the attribute and sample dataset:

Attribute:
- Cummulative consumption.

```markdown
| DATE       | DEVICE ID | CONSUMPTION | LAT      | LONG     |
|------------|-----------|-------------|----------|----------|
| 2024-01-01 | A123      | 150         | 40.7128  | -74.0060 |
| 2024-01-02 | A124      | 160         | 34.0522  | -118.2437|
| 2024-01-03 | A125      | 170         | 51.5074  | -0.1278  |
| 2024-01-04 | A126      | 180         | 48.8566  | 2.3522   |
| 2024-01-05 | A127      | 190         | 35.6895  | 139.6917 |
```

## License

This project is licensed under the MIT License.


## Contact
For any queries or suggestions regarding this thesis project, please contact:

- **Emmanuel Jolaiya** ([emmanuel.jolaiya@uji.es](mailto:emmanuel.jolaiya@uji.es)) (Student) . 
- **Dr. Sergi Trilles** ([strilles@uji.es](mailto:strilles@uji.es)) (Main Supervisor).


## Acknowledgement

- All reviewed literature authors.
- [Erasmus Mundus MSc in Geospatial Technologies](https://mastergeotech.info/).
- UNGSC technical experts.

