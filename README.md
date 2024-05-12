# Norwegian University of Life Sciences - Sushant Kumar Srivastava ( Master Thesis)

# Semantic Enhancements in Image Captioning: Leveraging Neural Networks to Improve BLIP and GPT-2

## Abstract

This repository houses the code and outputs from the thesis "Semantic Enhancements in Image Captioning: Leveraging Neural Networks to Improve BLIP and GPT-2." The study introduces cutting-edge techniques to produce captions that are closer to human-generated text, improving quality and efficiency without frequent retraining.

## Introduction

Addressing the challenge of resource-intensive training for automated image captioning models, this research introduces 'Weighted Summarization,' a technique that optimizes existing neural network capabilities to enhance models like BLIP and GPT-2.

## Repository Structure
Thesis-code/ - Contains all source code files used in the thesis. json_files_for_COCO/ - JSON output files for the COCO dataset. json_files_for_FLICKR/ - JSON output files for the FLICKR dataset. LICENSE - Licensing information for project use and distribution. README.md - Repository overview and setup guide.


## Installation

Clone the repository and install the necessary libraries:

```bash

git clone [Your Repo URL]

cd [Repository Name]

pip install -r requirements.txt

## Installation Clone the repository and install the necessary libraries: ```bash git clone [Your Repo URL] cd [Repository Name] pip install -r requirements.txt
```
Usage
-----

### Running Notebooks Locally

Update the paths to the JSON files in the notebooks before running them:
```bash
json_path = '/path/to/your/json_files_for_COCO'

```
### Running on Google Colab

For optimal performance and ease of use, it is recommended to run these notebooks on Google Colab:

1.  Upload the notebooks and corresponding JSON files to Google Colab.
2.  Update the file paths in the notebooks to the location of your uploaded JSON files.
3.  Run the notebooks directly in your browser.

Notebooks and Corresponding Thesis Sections
-------------------------------------------

Detailed alignment of each notebook with the thesis sections is provided in the repository for clarity.

Contributing
------------

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.
