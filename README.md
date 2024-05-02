# Automated vehicle damage classification using the three-quarter view car damage dataset and deep learning approaches

This repository is to supplement the paper "Automated vehicle damage classification using the three-quarter view car damage dataset (TQVCD) and deep learning approaches".

# Contribution
\begin{itemize}
    %%
    \item We introduce the Three-Quarter View Car Damage dataset (TQVCD dataset). The main objective of the dataset is to efficiently acquire comprehensive information on damage without explicitly labeling every damaged part. Unlike other datasets, the TQVCD dataset is constructed as a reference by mixing vehicle orientation and damage type.
    \item Our research is public data and is expected to be the basis for future research related to the automobile industry. Most studies have different standards for each study using their own datasets, and few are car-related datasets.
    \item To validate our dataset, we leverage transfer learning with diverse pre-trained deep learning-based models to build a binary classifier for each type of damage. To improve the robustness of classification results, we implemented a model ensemble method to reduce the deviation of individual model dependencies effectively. Our experiments included various weight values for each single model to optimize classifier performance.
    \item In recognition of the reduced sensitivity to lighting and background noise, we incorporated grayscale datasets into our analysis. The final results were derived by combining prediction values obtained from RGB datasets and computing the elementwise average.    
    \item Since it is an industrial issue, the effectiveness of this study was verified through interviews with industry experts and the effectiveness of the paper was reviewed.


# Dataset
We collected the car damage images corresponding to 3/4 views from the "vehicle damage data" of AI HUB and constructed the data by dividing the damage type into breakage and crushed.

# Model
To verify the validity of the TQVCD dataset, we constructed a binary classification model (breakage vs. normal / crushed vs. normal) trained using transfer learning techniques with five pre-trained models (ResNet-50, DenseNet-160, EfficientNet-B0, MobileNet-V2, and ViT).

# Interview
To ve
