# DeepGlobe-Land-Cover-Classification

> You can read the in depth explanation [here](https://hrish.in/projects/DeepGlobe/)

# <a name="instructions"></a>
## How to Run

1. Clone this repository. Navigate to desired directory and use:
```
git clone git@github.com:hrishikeshh/DeepGlobe-Land-Cover-Classification.git
```
2. The Python notebook is optimized and set up for proper execution in [Google Colab](https://colab.research.google.com/). I'd recommend to upload **deepglobe_land_cover.ipynb** and execute from there. Please see **Folder Structure** section for how to set up the initial folder structure. The Python notebook will move and create new directories to accomodate for certain preprocessing procedures but the initial setup is shown below.
3. Download the data from this [source](https://competitions.codalab.org/competitions/18468#learn_the_details-overview) and upload all data into Google Drive workspace based on the prior mentioned folder structure.
4. Execute the Python notebook. Note that for training, it is recommended to connect to a GPU enabled runtime for faster training speeds.

# <a name="structure"></a>
## Folder Structure

#### Initial Google Drive Folder Setup for Google Colab:
```
satellite_image_segmentation
│    Land_Cover_Segmentation.ipynb
└───data
│    │   class_dict.csv
│    │   metadata.csv
│    └───test
│    │    │ 1499_sat.jpg
│    │    │ 1500_sat.jpg
│    │    │ ...
│    └───train
│    │    │ 199_sat.jpg
│    │    │ 199_mask.png
│    │    │ ...
│    └───valid
│    │    │ 1074_sat.jpg
│    │    │ 1074_sat.jpg
│    │    │ ...
```

# <a name="datasets"></a>
## Dataset

> [DeepGlobe Land Cover Classification Dataset](https://competitions.codalab.org/competitions/18468#learn_the_details-overview)