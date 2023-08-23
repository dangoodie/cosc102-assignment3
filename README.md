# Data Science Assignment 03

Welcome to the GitHub repository for Data Science Assignment 03! This repository contains all the necessary code to run the analysis for the assignment. However, due to the size of the datasets, these files are not directly included in the repository. Follow the instructions below to set them up.

## Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.7
* Required Python libraries:
  * [numpy](https://numpy.org/)
  * [matplotlib](https://matplotlib.org/)
  * [scikit-learn](https://scikit-learn.org/)
  * [dtreeviz](https://github.com/parrt/dtreeviz)

### Setup

1. **Clone the Repository**

   ```
   git clone https://github.com/dangoodie/cosc102-assignment3
   cd cosc102-assignment3
   ```
2. **Download the Datasets**
   You will need to manually download the datasets:

   * [IMU Data](http://turing.une.edu.au/~cosc102/topics/assignment_03/a3_imu_data.csv)
   * [Activity Annotations](http://turing.une.edu.au/~cosc102/topics/assignment_03/a3_activity_annotations.csv)

   Download the datasets and place them in a directory named `datasets` in the root of the repository.
3. **[Optional] Download the Video Annotation**
   To verify specific data points, you can optionally download:

   * [Annotations Video](http://turing.une.edu.au/~cosc102/topics/assignment_03/a3_annotations.mkv)

   If downloaded, place the video in the `datasets` directory.

### Analysis Workflow

The analysis is broken down into 5 distinct jobs, each having its own Jupyter notebook:

1. **Sanitise the Data** : Align the data points and plot the annotations.
2. **Construct the Feature Set** : Calculate mean, min, max, Signal Magnitude Intensity, Average Intensity.
3. **Train 3 Classifiers** : Optimise at least one hyperparameter for each algorithm.
4. **Construct a Portfolio** : Visualise the data, feature construction, training and hyperparameter optimisation, performance metrics/visualizations and explanations.
5. **Conclusions** : Outlining the final analysis results.

After completing these jobs, the results will be compiled into a final Jupyter notebook for presentation.

### Running the Analysis

1. Navigate to the repository directory: ``cd cosc102-assignment3``
2. Launch Jupyter Notebook: ``jupyter notebook``
3. Navigate to and run the respective `.ipynb` files in sequence, as outlined in the "Analysis Workflow" section.

## Contributing

If you find any issues or have suggestions, please open an issue in this repository.
