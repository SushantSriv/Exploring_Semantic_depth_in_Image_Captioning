# Norwegian University of Life Sciences - Sushant Kumar Srivastava ( Master Thesis)

# Semantic Enhancements in Image Captioning: Leveraging Neural Networks to Improve BLIP and GPT-2

## Abstract

This repository houses the code and outputs from the thesis "Semantic Enhancements in Image Captioning: Leveraging Neural Networks to Improve BLIP and GPT-2." The study introduces approaches that produce captions that are closer to human-generated text, improving quality and efficiency without frequent retraining.

## Introduction

Addressing the challenge of resource-intensive training for automated image captioning models, this research introduces 'Weighted Summarization,' a technique that optimizes neural network capabilities to enhance models like BLIP and GPT-2.

## Repository Structure
Thesis-code/ - Contains all source code files used in the thesis.<br />
json_files_for_COCO/ - JSON output files for the COCO dataset.<br />
json_files_for_FLICKR/ - JSON output files for the FLICKR dataset.<br />
LICENSE - Licensing information for project use and distribution. <br />
README.md - Repository overview and setup guide.


## Installation

Clone the repository and install the necessary libraries:

```bash

git clone https://github.com/SushantSriv/Semantic-Enhancements-in-Image-Captioning-Leveraging-Neural-Networks-to-Improve-BLIP-and-GPT-2.git

cd Semantic-Enhancements-in-Image-Captioning-Leveraging-Neural-Networks-to-Improve-BLIP-and-GPT-2

pip install -r requirements.txt

```
Usage
-----

### Running Notebooks Locally

Update the paths to the JSON files in the notebooks before running them:

```bash
json_path = '/path/to/your/json_file'
```

### Running on Google Colab

For optimal performance and ease of use, it is recommended to run these notebooks on Google Colab:

1.  Upload the notebooks and corresponding JSON files to Google Colab.
2.  Update the file paths in the notebooks to the location of your uploaded JSON files.
3.  Run the notebooks directly in your browser.

Notebooks and Corresponding Thesis Sections
-------------------------------------------

-   COCO_DATASET_PROCESSING_AND_CAPTION_GENERATION.ipynb - Section 4.2.1
-   FLICKR_DATASET_PROCESSING_AND_CAPTION_GENERATION.ipynb - Section 4.2.1
-   EVALUATING_SCORES_ALL_CASES_COCO.ipynb, EVALUATING_SCORES_ALL_CASES_FLICKR.ipynb - Chapter 5
-   SUMMARIZATION_USING_ANN_COCO.ipynb, SUMMARIZATION_USING_ANN_FLICKR.ipynb - Section 5.5
-   WEIGHTED_SUMMARIZATION_COCO.ipynb, WEIGHTED_SUMMARIZATION_FLICKR.ipynb - Section 5.4
-   SCENARIO01_COCO.ipynb, SCENARIO01_FLICKR.ipynb, SCENARIO02_COCO.ipynb, SCENARIO02_FLICKR.ipynb - Section 4.3
-   TRAINING_ANN_COCO.ipynb, TRAINING_ANN_FLICKR.ipynb - Section 4.2.2.4
-   IMAGE_CATEGORIES_EVALUATION_COCO.ipynb, IMAGE_CATEGORIES_EVALUATION_FLICKR.ipynb - Related to Section 5.1
-   CHARTS_AND_FIGURES_PRODUCED_COCO_FLICKR.ipynb - Supports visual analysis in Chapter 5 and 6.

Contributing
------------

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.
