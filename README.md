
# Garbage Redressal Model

This repository contains the **image verification model** used in the [Garbage Redressal System](https://github.com/sarfarajansari/garbageRedressal). The model is designed to automatically evaluate images submitted by users, determining whether they contain visible garbage, and helps verify the effectiveness of cleanup efforts.


## Screenshots

![image](https://github.com/user-attachments/assets/a06663bf-af68-49b2-bd63-2f53df376e0c)

![image](https://github.com/user-attachments/assets/fe2967ec-39d3-4f83-956e-de299ddc516c)

![image](https://github.com/user-attachments/assets/219a8826-5f76-4fce-9ec8-ebe8d24ab40f)

![image](https://github.com/user-attachments/assets/5eea0fba-9ec6-406e-bd1b-d11b6e98a7d1)

## Purpose

The model serves two primary functions within the Garbage Redressal System:

1. **Initial Verification**: When a user submits a waste management issue with images, the model processes these images to determine if they genuinely depict garbage. Verified requests are accepted and passed to the main system with coordinates.
   
2. **Cleanup Verification**: Once staff have addressed the issue and uploaded new images of the cleaned area, the model re-evaluates the images to confirm successful cleanup before the request is marked as resolved.



## How It Works

- **Image Processing**: The model uses deep learning techniques to analyze the visual contents of each image and classify it as containing garbage or not.
- **Request Integration**: Integrated seamlessly with the main application, the model interacts with incoming images during both initial and post-cleanup stages.

## Technologies Used

- **Deep Learning Frameworks**: The model was developed using modern deep learning libraries for efficient image classification.
- **Data Augmentation**: Techniques are applied to improve model accuracy across different lighting and environmental conditions.

## Integration with Main Application

This model repository is designed to be used as a submodule or API endpoint within the main Garbage Redressal System. For more information about the primary system, its features, and how the model fits into the larger process, visit the main repository: [Garbage Redressal System](https://github.com/sarfarajansari/garbageRedressal).

## Conclusion

The garbageRedressal.Model repository is an essential component of the larger Garbage Redressal System, providing automated, reliable image verification to support real-time waste management efforts. By validating reports and cleanups, it ensures only genuine requests are addressed, helping maintain clean, safe environments.

