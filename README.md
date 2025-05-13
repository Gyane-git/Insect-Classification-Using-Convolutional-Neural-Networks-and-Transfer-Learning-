🐞 Insect Species Classification using Deep Learning
This project presents an approach to automatic insect species classification using Convolutional Neural Networks (CNNs). The dataset contains images of 9 insect species, and our goal was to build a model capable of accurately identifying each class. The system can serve as a foundation for smart pest detection systems in agriculture.

🚀 Models Developed
Three CNN-based models were built and evaluated:

Baseline CNN
A simple convolutional neural network for initial performance benchmarking.

Deeper CNN with Regularization
Includes dropout and batch normalization to improve generalization and reduce overfitting.

Transfer Learning with VGG16
Fine-tuned pre-trained VGG16 model using ImageNet weights. Achieved the highest accuracy (~74%).

🧪 Techniques Used
Data Augmentation: Applied transformations like rotation, flipping, and scaling to enhance model robustness.

Fine-Tuning: In the VGG16 model, selected layers were unfrozen and retrained for better domain adaptation.

Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

📊 Results
Model	Accuracy	Precision	Recall	F1-Score
Baseline CNN	~61%	Moderate	Moderate	Moderate
Deep CNN + Regularization	~68%	Improved	Improved	Improved
VGG16 Transfer Learning	~74%	High	High	High

Conclusion: Transfer learning significantly outperformed custom-built CNNs, especially for small datasets. This demonstrates the value of leveraging pre-trained models for agricultural image classification tasks.

🌾 Applications
This model can be used as a starting point for building automated pest detection systems to support precision agriculture, pest management, and biodiversity research.

🛠️ Requirements
Python 3.8+

TensorFlow / Keras

NumPy

OpenCV

scikit-learn

Matplotlib


📬 Contact
For any queries or collaborations, please contact:
Gyanendra Kumar Sah
Email: gyanee750@gmail.com