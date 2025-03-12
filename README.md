# KCTD5_MoSeq_Analysis
This repository contains code for the behavioral analysis performed in "KCTD5 tunes neuromodulatory signal decoding in striatal neurons necessary for motor function" [insert link to paper here].

## What is This Repository?
What this repository shows:
- How to configure a Keypoint-Moseq project to use keypoints from the DeepLabCut Superanimal Topview Mouse model
- How to perform the same analysis using data generate by Keypoint-Moseq as was performed in the referenced paper

For a more in-depth explanation of how to use Keypoint-Moseq, refer to the following:
- https://keypoint-moseq.readthedocs.io/en/latest/index.html
- https://www.nature.com/articles/s41592-024-02318-2

To learn more about markerless keypoint tracking with DeepLabCut, refer to the following: 
- https://deeplabcut.github.io/DeepLabCut/README.html
- https://www.mackenziemathislab.org/deeplabcut

## How to Use this Repository
### Download the Data
1. Download the data here: [insert link to wherever the files are shared]
### Prerequisites
1. Install Anaconda: https://www.anaconda.com/docs/getting-started/anaconda/install
2. Install Keypoint Moseq: https://keypoint-moseq.readthedocs.io/en/latest/install.html
   - For the purposes of repeating the analysis in analysis.ipynb using the data provided, the CPU version should be adequate
### Analysis
1. Locate the downloaded data on your machine and make sure the files have been extracted
   - Do not change the organization of files inside of the folder
2. Download analysis.ipynb
3. open the anaconda prompt and type "jupyter lab" to open jupyter lab
4. Make sure you're using the kernel associated with your keypoint-moseq conda environment and open analysis.ipynb
5. follow the instructions provided in the file 
