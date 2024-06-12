# Kolmogorov-Arnold Networks (KANs) Project

Our project studies the potential of Kolmogorov-Arnold Networks (KANs), a cutting-edge deep learning architecture inspired by the Kolmogorov-Arnold representation theorem. This architecture was published ensuring that it could offer significant improvements over traditional neural networks in various tasks. The aim of our research was to thoroughly evaluate the capabilities and applications of KANs in both theoretical and practical scenarios.

Initially, we replicated several foundational experiments from the original KAN research to validate our understanding and to ensure our setup was correctly implemented. Following this, we extended these experiments to explore new applications and configurations, aiming to push the boundaries of what KANs can achieve.

## Main Activities and Experiments

1. **Function Fitting:** 
   We tested KANs on different mathematical functions to evaluate their performance in accurately modeling and predicting the dataset’s structure. This involved observing how well KANs generalize from known and unseen data from complex datasets.

2. **Grid Size and Optimizer Testing:** 
   We experimented with different grid sizes and spline degrees to understand their impact on the performance of KANs. Additionally, we compared various optimization algorithms, such as Adam and LBFGS, to determine the most effective methods for training KANs.

3. **KAN Architectures:** 
   By analyzing different architectures of KANs, we aimed to identify the most efficient configurations. This involved trying different widths of the architecture, different numbers of neurons per layer, and other parameters to optimize the performance for specific tasks.

4. **Real-world Applications:** 
   We applied KANs to real-world datasets to test their practical utility. We used KANs for binary classification with a heart disease dataset, analyzing their accuracy and robustness in medical data prediction. Furthermore, we integrated KAN layers with classical Convolutional Neural Networks (CNNs) to enhance image recognition tasks, using datasets like SVHN and MNIST to benchmark performance.

Throughout the project, we documented each experiment, ensuring that our methods are reproducible.

## Project Structure

- `Function_Fitting_Experiments.ipynb`: Notebook for the different function fitting experiments.
- `Heart_Disease_Classification.ipynb`: Notebook for the binary classification task in the heart disease dataset.
- `CNN_Performance_Analysis.ipynb`: Notebook for analyzing the performance with CNNs.

## Large Data Files

The large data files are stored on Google Drive. You can download them from the following link:

- [Google Drive Data Folder](https://drive.google.com/drive/folders/1WO30mB3RZojEvURz_zHhGA_JVlOJdI3m?usp=drive_link)

**Note:** Paths in the scripts must be modified accordingly by the user to match the local environment.

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
