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

- Face detection successfully identified multiple faces of the professors from the group image.
- Hue and saturation features were sufficient to create meaningful separation between faces when clustered using K-means.
- K-means clustering grouped faces into visually consistent clusters, this shows color-based features capture important facial appearance differences.
- The centroids of the clusters represented dominant color patterns and helped in visualizing faces.
- Template matching was able to locate the closest match in the cluster space.
- The scatter plots displayed that most faces formed compact clusters, suggesting stable clustering behavior with the chosen feature representation.


## Conclusions

This Lab exercise demonstrates that distance-based classification using K-means clustering can effectively group facial images using simple color features. Even with only hue and saturation, the system produced structured clusters and allowed template-based matching against a reference face. While the approach does not achieve perfect identity recognition, it shows how unsupervised clustering along with distance metrics can group simlar visual data meaningfully. 

![WhatsApp Image 2026-02-15 at 9 38 59 PM](https://github.com/user-attachments/assets/348022e3-603c-4c72-a047-02298550c07a)
![WhatsApp Image 2026-02-15 at 9 37 55 PM](https://github.com/user-attachments/assets/110f982b-c0a6-45b1-8b27-74373bfaccd6)

![WhatsApp Image 2026-02-15 at 9 37 32 PM](https://github.com/user-attachments/assets/beaef3a7-ad04-42fa-8ae3-bb8b3a236f41)
![WhatsApp Image 2026-02-15 at 9 41 24 PM](https://github.com/user-attachments/assets/eb198341-935c-474d-8182-080e9343f856)
![WhatsApp Image 2026-02-15 at 9 37 03 PM](https://github.com/user-attachments/assets/7ea68c91-367b-4a10-b2d7-24075bcef8e5)
![WhatsApp Image 2026-02-15 at 9 36 49 PM](https://github.com/user-attachments/assets/d359b020-84c8-4131-827a-38ab7251e315)






