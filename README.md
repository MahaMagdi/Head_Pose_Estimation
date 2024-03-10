# Head_Pose_Estimation

This project aims to determine a person's head orientation in images or videos through head pose estimation, predicting the three-dimensional rotation angles of **Pitch, Yaw, and Roll.** This information holds significant value across diverse applications like human-computer interaction, facial recognition, virtual reality, and surveillance systems.

The **MediaPipe FaceMesh** module is instrumental in extracting facial landmarks, comprising 468 points on the face. These landmarks, coupled with pose parameters retrieved from MATLAB files, form the input features for a supervised machine learning model. Notably, the **AFLW2000-3D** dataset is utilized for training the model, where the ground truth encompasses the actual head pose angles corresponding to each input image. This comprehensive approach seeks to enhance accuracy and reliability in predicting head orientations, contributing to improved performance in applications reliant on precise head pose information.

[The _Intern.mp4](Untitled%20e96dbe17dbe54488a3f126b1de92988b/The__Intern.mp4)








https://github.com/MahaMagdi/Head_Pose_Estimation/assets/96911766/45e0c885-0a35-4e35-956e-aeace5e10b47

