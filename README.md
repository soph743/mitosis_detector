![alt text](https://github.com/soph743/mitosis_detector/blob/main/Mitosis%20Classification%20(1).png)

# Mitosis Detector 
--Disclaimer: This is an ongoing project as part of our fellowship with MIT Break Through Tech.

## Description
Mitosis Detector is a supervised machine learning model desgined to classify cells from MIDOG++ wholeslide images as mitotic vs non-mitotic. the dataset include 26000+ annotated microscopay images across 7 different tissue and cell types. The goal of the project is to benchmark multiple deep learning archetectures and evluate the effectiveness in automating mitosis detection which is a key challenge in computational pathology. 
## Project Highlights
- **Achieved** an accuracy of 84%, which is a higher accuracy than the MIDOG++ competition accuracy
- Efficiently ran model on 26k+ images
## Data Exploration
To prepare the data, we preprocessed images from the open source MIDOG++ dataset, and we split up the images into two folders: mitotic and non-mitotic

## Models
We explored several architectures to compare segmentation-augmented and classification-focused pipelines:

###  Resnet101 + Deeplabv3
- pretained on everyday images (animals and other objects)
- custom head with hydriv segmentation and classification pipeline. 
- accuracy: 80%
### Midnight12k
- pretained on wholeslide pathology images
- custom linear classifier head
- accuracy: 84%

### Selected Model
We decided to use the Midnight12k model due to its higher performance compared to the Deeplabv3 model

## Contributors
Sophia Cherkaoui (github.com/soph743)
Gaurang Deka
Brianna Matey (https://github.com/briannammatey)
Tasnim Hossain
Andres Figeroa



## Citations & Acknowledgements

We are immensely grateful for the support from our industry advisors, as well as our BTTAI TA and staff throughout the course of our project.

MIDOG++ Dataset:

Aubreville, M., Wilm, F., Stathonikos, N. et al. A comprehensive multi-domain dataset for mitotic figure detection. Sci Data 10, 484 (2023). https://doi.org/10.1038/s41597-023-02327-4

Midnight12k:

https://github.com/kaiko-ai/midnight

## Contact

For questions and collaboration, contact: 

sophiacherkaoui46@gmail.com
gaurangdeka10@gmail.com
briannammatey@gmail.com
Tasnim.Hossain@tufts.edu
andresfigueroa@brandeis.edu



