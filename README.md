The tables below gives accuracy of each model for each magnification zoom presents in the dataset upto three decimal units. The values in brackets are F1 score

**CNN models with FCN at the end**

| Magnification/CNN Model -> | VGG-16 | VGG-19 | Xception | Resnet | Inception | Inception-Resnet-V3 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 40X | 0.802 (0.803) | 0.652 (0.685) | 0.831 (0.831) | 0.859 (0.858) | 0.853 (0.858) | 0.818 (0.813) |
| 100X | 0.867 (0.877) | 0.709 (0.708) | 0.786 (0.794) | 0.911 (0.917) | 0.834 (0.827) | 0.845 (0.837) |
| 200X | 0.841 (0.839) | 0.749 (0.756) | 0.812 (0.813) | 0.857 (0.853) | 0.799 (0.806) | 0.854 (0.859) |
| 400X | 0.871 (0.869) | 0.799 (0.799) | 0.761 (0.758) | 0.903 (0.907) | 0.799 (0.796) | 0.842 (0.844) |


**CV score on Logistic Regression Model trained on features extracted from CNN models**

| Magnification/CNN Model -> | VGG-16 | VGG-19 | Xception | Resnet | Inception | Inception-Resnet-V3 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 40X | 0.685 (0.675) | 0.565 (0.547) | 0.858 (0.856) | 0.908 (0.906) | 0.839 (0.836) | 0.854 (0.850) |
| 100X | 0.732 (0.725) | 0.633 (0.623) | 0.840 (0.837) | 0.902 (0.900) | 0.826 (0.822) | 0.863 (0.862) |
| 200X | 0.864 (0.862) | 0.725 (0.718) | 0.940 (0.954) | 0.959 (0.958) | 0.919 (0.917) | 0.961 (0.960) |
| 400X | 0.952 (0.952) | 0.876 (0.874) | 0.982 (0.982) | 0.983 (0.983) | 0.983 (0.983) | 0.982 (0.982) |

**CV score on Linear Support Vector Machine Model trained on features extracted from CNN models**

| Magnification/CNN Model -> | VGG-16 | VGG-19 | Xception | Resnet | Inception | Inception-Resnet-V3 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 40X | 0.644 (0.640) | 0.543 (0.530) | 0.857 (0.856) | 0.905 (0.905) | 0.855 (0.853) | 0.851 (0.849) |
| 100X | 0.711 (0.704) | 0.603 (0.595) | 0.830 (0.829) | 0.895 (0.894) | 0.826 (0.822) | 0.864 (0.863) |
| 200X | 0.848 (0.847) | 0.700 (0.693) | 0.943 (0.942) | 0.961 (0.961) | 0.916 (0.916) | 0.958 (0.958) |
| 400X | 0.950 (0.949) | 0.868 (0.867) | 0.983 (0.983) | 0.983 (0.983) | 0.983 (0.983) | 0.980 (0.980) |
