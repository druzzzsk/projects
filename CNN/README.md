### Vegetables classification
As part of this project, an automated vegetable classification system was developed using deep learning methods. The goal was to classify images into one of 15 unique vegetable categories, including broccoli, pepper, bottle gourd, radish, tomato, eggplant, pumpkin, carrot, papaya, cabbage, bitter gourd, cauliflower, beans, cucumber, and potato.

Two model architectures were implemented and compared:

- VGG16-based model: A pre-trained network fine-tuned for the target task (transfer learning).
- Custom CNN: A lightweight convolutional neural network built from scratch with Conv2D, MaxPooling, and dense layers.
Both models were trained and validated on the same dataset. Classification performance was evaluated using validation accuracy and loss metrics.


