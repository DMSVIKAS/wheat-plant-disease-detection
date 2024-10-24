Training a DenseNet121 model on wheat leaf images! 🌿📊

Code Summary:
1. **Image Augmentation**: You're using `ImageDataGenerator` for rescaling and augmentations like shear, zoom, and flip ✨, with a training/validation split. 📂
2. **Pre-trained Model**: You’re leveraging the DenseNet121 model 🧠 pre-trained on ImageNet, and adapting it for your 3-class output 🌾🔍.
3. **Training Setup**: The model is compiled with Adam optimizer 🚀, categorical cross-entropy as the loss function, and training for 3 epochs ⏳.

Suggestions:
- **Monitor Training 📈**: You might want to add callbacks like `ModelCheckpoint` or `EarlyStopping` to save the best model and prevent overfitting!
- **Increase Epochs 🏋️**: Depending on the dataset size, consider running the model for more epochs to achieve better accuracy.

Everything looks working stay awesome 😎👍

dataset link : mail me
