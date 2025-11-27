# Mitosis Detector 
--Disclaimer: This is an ongoing project as part of our fellowship with MIT Break Through Tech.

<br>
The collaborators on this project are: Gaurang Deka,  Andres Figueroa, Tasnim Hossain, Sophia Cherkaoui, and Brianna Matey

## Description
A model to classify cells from the MIDOG++ dataset as 'mitotic' or 'not mitotic' using multiple machine learning approaches. The dataset contains 7 cell types and 25,000+ images.

## Models

- Resnet101 + Deeplabv3 (version 1 model, 80% accuracy)

- Midnight12k (version 2 model, 84% accuracy)

## Dataset Citation

MIDOG++ Dataset:

Aubreville, M., Wilm, F., Stathonikos, N. et al. A comprehensive multi-domain dataset for mitotic figure detection. Sci Data 10, 484 (2023). https://doi.org/10.1038/s41597-023-02327-4

Midnight12k Weights:

@InProceedings{KDK_Training_MICCAI2025,
  title={Training state-of-the-art pathology foundation models with orders of magnitude less data},
  author={Mikhail Karasikov and Joost van Doorn and Nicolas Känzig and Melis Erdal Cesur and Hugo Mark Horlings and Robert Berke and Fei Tang and Sebastian Otálora},
  booktitle = {Medical Image Computing and Computer Assisted Intervention -- MICCAI 2025},
  year = {2025},
  publisher = {Springer Nature Switzerland},
  volume = {LNCS 15967},
  month = {October},
  pages = {573--583},
  doi={10.1007/978-3-032-04984-1_55},
}



