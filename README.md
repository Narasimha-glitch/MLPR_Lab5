# Name : Narasimha P
# UID : U20240081
# CSAI


## Aim 

The aim of this Lab exercise is to apply distance-based unsupervised learning to facial images to group and analyze visual similarity.
This exercise focuses on detecting faces from a group image, extracting color-based features, and using K-means clustering to organize faces in feature space. 
A template face is then matched using distance metrics to demonstrate how similarity-based classification can be performed. 
The objective is to understand how clustering and feature distance can be used to structure and interpret visual data.


## Methodology

This Lab includes distance-based classification, with emphasis on KNN. The methodology includes:
- Face detection,
- Feature extraction,
- K-means clustering,
- Template based matching ,and
- visualization using scatter plots fo hue and Saturation .

## Key Findings

- Face detection successfully identified multiple facesof the professors from the group image, showing that the preprocessing pipeline is effective for real-world multi-person scenes.
- Hue and saturation features were sufficient to create meaningful separation between faces when clustered using K-means.
- K-means clustering grouped faces into visually consistent clusters, this shows color-based features capture important facial appearance differences.
- The centroids of the clusters represented dominant color patterns and helped in visualizing faces.
- Template matching was able to locate the closest match in the cluster space.
- The scatter plots displayed that most faces formed compact clusters, suggesting stable clustering behavior with the chosen feature representation.


## Conclusions

This Lab exercise demonstrates that distance-based classification using K-means clustering can effectively group facial images using simple color features. Even with only hue and saturation, the system produced structured clusters and allowed template-based matching against a reference face. While the approach does not achieve perfect identity recognition, it shows how unsupervised clustering along with distance metrics can group simlar visual data meaningfully. 


