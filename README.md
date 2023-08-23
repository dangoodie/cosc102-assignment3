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

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/dangoodie/cosc102-assignment3
   cd cosc102-assignment3
   </code></div></div></pre>
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

1. Navigate to the repository directory:
   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">cd cosc102-assignment3
   </code></div></div></pre>
2. Launch Jupyter Notebook:
   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">jupyter notebook
   </code></div></div></pre>
3. Navigate to and run the respective `.ipynb` files in sequence, as outlined in the "Analysis Workflow" section.

## Contributing

If you find any issues or have suggestions, please open an issue in this repository.
