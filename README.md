# LuxDrive-Dataset

Welcome to the Luxembourg driving dataset (LuxDrive-Dataset) repository, a fundamental resource designed to support research on perception in autonomous driving environments. This dataset serves as a crucial tool for validating and benchmarking innovative research concepts in autonomous driving, utilizing vehicle-to-everything (V2X) communication. It can be utilized for various purposes spanning computer vision to computer networking.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Cooperative Perception using V2X Communications: An Experimental Study**":
- [Read the Full Paper (PDF)]

### Citation:
If you use this dataset in your research, please use the following citation:

```text
@article{hawlader2024,
  author={Hawlader, Faisal and Robinet, François and Frank, Raphaël},
  booktitle={2024 IEEE 100th Vehicular Technology Conference (VTC2024-Fall)}, 
  title={Cooperative Perception Using V2X Communications: An Experimental Study}, 
  year={2024},
  volume={},
  number={},
  pages={1-7},
  keywords={Vehicular and wireless technologies;Image coding;Ecosystems;Object detection;Cameras;Real-time systems;Hardware;Communications technology;Delays;Testing;Cloud Computing;Distributed Perception;C-V2X;ITS-G5;Object Detection;CPM},
  doi={10.1109/VTC2024-Fall63153.2024.10757448}}

```
## Dataset Overview
- Real-world driving dataset captured using a front-facing camera sensor mounted on the rooftop of an autonomous vehicle developed by 360lab, a research group at the University of Luxembourg. The dataset was created while driving around JFK Avenue in Kirchberg, Luxembourg City. 
- The dataset contains 5k camera frames and ground truth bounding box annotations for three classes:
  - **vehicles (bus, car), pedestrians, and traffic lights**
- Split into three subsets:
    - Training (3500 images)
    - Validation (750 images)
    - and Testing (750 images)
```text
LuxDrive Dataset (format):
    - Train
        - images
          - *.bmp
        - labels
          - *.txt
    - Test
        - images
          - *.bmp
        - labels
          - *.txt
    - Validation
        - images
          - *.bmp
        - labels
          - *.txt
```
### Example Images
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/LuxDrive-Dataset/assets/43897254/1199af98-36db-4ccb-b729-e7671a6c1bf4)">


## Downloads
To access the sample dataset (the complete dataset will be shared in the final version of the paper), please use the following link:
- [Download the Dataset (15 GB)](https://doi.org/10.5281/zenodo.14523854).

If you encounter any issues or have questions, please feel free to get in touch by sending an email to faisal.hawlader@uni.lu. We'll be happy to assist you!
## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
