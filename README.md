# cameratraps-imageclassification
## Project Motivations
Automated surveillance systems called camera traps have helped conservationists study and monitor a wide range of ecologies while limiting human interference. Camera traps are triggered by motion or heat, and passively record the behavior of species in the area without significantly disturbing their natural tendencies.

However, camera traps also generate a vast amount of data that quickly exceeds the capacity of humans to sift through. That's where machine learning can help! Advances in computer vision can help automate tasks like species detection and classification, localization, depth estimation, and individual identification so humans can more effectively learn from and protect these ecologies. The objective of the project is to explore the transfer learning technique through convoluted neural network to detect and classify different class of animal species.
## Dataset
This is a real world dataset of wildlife images from [Tai National Park](https://en.wikipedia.org/wiki/Taï_National_Park) in Côte d'Ivoire, there are 8 classes of animal species with over 16,488 image files in train dataset and 4,464 image files in test dataset. The pre-trained ResNet152 model has over 80% accuracy on image classification and localization. Thanks to [drivendata](https://arxiv.org/abs/1606.07781) for providing the dataset and support needed to make this project come to life.

