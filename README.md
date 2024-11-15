Using Google Teachable Machine to Make an Animal Species Identifier

1.Process of collecting and preparing data for training model—
Process of Collecting and Preparing Data for Training the ModelData Collection:
The dataset was sourced primarily from Google and wildlife-related websites. Images and videos representing various animal species were downloaded to ensure a diverse collection.
Data Annotation:
Each collected image or video frame was labeled with the respective species name for classification.
Data Preprocessing:
Cleaning: Removing duplicate or low-quality images.
Augmentation: Creating variations in the dataset (e.g., flipping or cropping) to improve the model's adaptability.
Normalization: Standardizing pixel values to ensure uniformity.
Effect on Accuracy and Reliability:
By using diverse images from various online sources, the model was trained to recognize animals in different environments and contexts, increasing accuracy and reliability for real-world application.
For a model to identify different animal species accurately, it’s essential to collect a diverse dataset of photos and videos representing the species in various environments, lighting conditions, angles, and poses. Images were sourced from open wildlife databases, field researchers, and camera trap footage. This diversity in data ensures the model can generalize well, improving accuracy and reliability in real-world settings, where animals may appear in different orientations and environmental contexts.
2.	Using Google’s Teachable Machine to Create the Model
Google’s Teachable Machine served as the platform for creating the model:
Images were uploaded into the tool for categorization by species.
The platform provided a straightforward interface to train the model using machine learning techniques.
The trained model was then exported for further use in wildlife monitoring systems.
Google's Teachable Machine simplifies the model-building process by allowing for quick dataset uploading, classification, and training without complex coding. By uploading images for each species category, the Teachable Machine processes and trains the model, which is then easily exportable for further customization or integration.
3.	Features and Functionalities Integrated into the Model
Key features include:
•	Real-Time Species Detection: The model is optimized for real-time predictions on incoming photo or video data streams.
•	Multi-Species Classification: It can identify various species accurately.
•	Environmental Adaptability: Thanks to diverse training data, the model performs well across different lighting and backgrounds.
Methods Used to Evaluate Model Performance
The model's performance was assessed using:
•	Accuracy and F1 Score: To measure the precision and recall balance across all species classes.
•	Confusion Matrix: To visualize which species were most commonly misclassified.
•	Real-World Testing: Field tests were conducted in varied environments to ensure the model performs effectively in practical conditions.
4.	Applications in Wildlife Monitoring and Real-World Use Cases
This model can be integrated into real-time wildlife monitoring systems. Camera traps or drones equipped with this model can automatically identify animal species in their natural habitats, enabling conservationists to monitor biodiversity, track animal movements, and prevent poaching. It also has applications in environmental studies and education, where instant species identification can aid field researchers and students in learning more about local wildlife populations.Wildlife Conservation:
Track endangered species and deter poaching.
Ecological Research:
Monitor biodiversity and animal movement patterns.
Human-Wildlife Conflict Mitigation:
Alerts farmers to potential threats from wildlife.
Education:
A tool for students and researchers to identify species in the field
Screenshots of workinbg model![Screenshot 2024-11-13 113905](https://github.com/user-attachments/assets/ad66666a-bfa0-4313-98fe-c450789fb960)
![Screenshot 2024-11-13 113856](https://github.com/user-attachments/assets/3414465e-03de-4481-9c32-8672b5650578)
