# Image Reconstruction using Orthogonal Illumination and Compressed Sensing
This project focuses on reconstructing images using orthogonal illumination and the compressed sensing approach. The objective is to minimize the total variance of the final image by utilizing incoherent structured illumination.

## Dataset
The illumination dataset and files used in this project were acquired from Dr. Michael. The dataset consists of two data folders: "random" and "hg". Each folder contains positive and negative intensity profiles used for incoherent structured illumination. Additionally, a CSV file dataset is included, which contains projection/illumination coefficients for reconstructing both random and hg images of phantom and USAF.

## Variables
Six variables have been created to store the total illumination profile, positive intensity profiles, and negative intensity profiles for both the random and hg illumination datasets. The total illumination profile is calculated by taking the difference between each positive and negative image intensity profile present in the dataset. Furthermore, four variables are used to store the projection coefficients found in the CSV files.

## Results
The project demonstrates the application of both the orthogonal illumination and compressed sensing approaches to reconstruct the images. The results are showcased for both compressed sensing and illumination microscopy techniques.

## Dependencies
This code relies on the following dependencies:

- NumPy
- SciPy
- Matplotlib

## How to Run
To run the code, follow these steps:

Make sure you have Python installed on your system (preferably Python 3).
Install the required dependencies by executing the following command:
```bash
pip install numpy scipy matplotlib pandas
```
Clone this repository or download the project files.
Open the code in your preferred Python IDE or text editor or anaconda.
Run the code and observe the reconstructed images and results.
Additional Notes
Please note that the dataset and files used in this project were obtained from Dr. Michael. If you have any questions regarding the dataset or specific implementation details, please refer to the original source or contact the respective author.

Feel free to explore the code and experiment with different parameters to further understand the impact of orthogonal illumination and compressed sensing on image reconstruction.

If you encounter any issues or have suggestions for improvements, please don't hesitate to raise an issue or contribute to the project.

Happy image reconstruction!
