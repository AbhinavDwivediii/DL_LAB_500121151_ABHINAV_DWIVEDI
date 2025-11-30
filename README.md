# 📦 Deep-Learning-Experiments

┣ 📂 Exp_1

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_2

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 [Exp_3]

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_4

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_5

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_6

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_7

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_8

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_9

┃ ┣ 📓 convolutional-neural-network-cnn-tutorial.ipynb

┃ ┣ 📂 test

┃ ┗ 📂 train


┣ 📂 Exp_10

┃ ┣ 📓 Exp10_FasterRCNN_ObjectDetection.ipynb

┃ ┣ 📂 Pascal_voc

┃ ┣ 📄 detection_results.png

┃ ┗ 📄 sample_annotations.png


┣ 📂 Exp_11

┃ ┣ 📓 unet_segmentation.ipynb

┃ ┗ 📄 best_unet_model.pth


┣ 📂 Exp_12

┃ ┣ 📓 Pre_process.ipynb

┃ ┣ 📄 model.py

┃ ┣ 📄 autoencoder_celeba.pth

┃ ┣ 📄 latent_space.png

┃ ┣ 📄 reconstruction_results.png

┃ ┗ 📄 training_loss.png


┣ 📂 Exp_13

┃ ┣ 📄 model.py

┃ ┣ 📄 vae_fashion_mnist.pth

┃ ┣ 📄 vae_generated_samples.png

┃ ┣ 📄 vae_interpolation.png

┃ ┣ 📄 vae_latent_space.png

┃ ┣ 📄 vae_manifold.png

┃ ┣ 📄 vae_reconstruction.png

┃ ┗ 📄 vae_training_loss.png


┣ 📂 Exp_14

┃ ┗ 📄 model.py

┗ 📄 README.md


<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #0d0d0d;
    font-family: Arial, sans-serif;
    color: white;
}

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 25px;
    padding: 20px;
}

.card {
    background: #1a1a1a;
    padding: 20px;
    border-radius: 14px;
    box-shadow: 0 0 15px rgba(255,255,255,0.08);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 25px rgba(255,255,255,0.15);
}

h2 {
    color: white;
    margin-bottom: 10px;
}

p {
    color: #e6e6e6;
    line-height: 1.5;
}

.btn {
    display: inline-block;
    padding: 10px 14px;
    margin-top: 10px;
    border-radius: 8px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.exp-btn {
    background-color: #ff7b00;
}

.dataset-btn {
    background-color: #007bff;
}
</style>
</head>

<body>

<h1 style="text-align:center; color:white;">Deep Learning Lab – All Experiments (1–14)</h1>

<div class="container">

<!-- EXP 1 -->
<div class="card">
    <h2>Experiment 1 — Comparative Study of Deep Learning Frameworks</h2>
    <p>Comparison of PyTorch, TensorFlow, and Keras for model building, training, and deployment workflows.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp1.ipynb">Experiment Link</a>
</div>

<!-- EXP 2 -->
<div class="card">
    <h2>Experiment 2 — Building Neural Networks from Scratch</h2>
    <p>
        • Implement neuron for AND gate<br>
        • FFNN for XOR/AND<br>
        • Full MLP implementation
    </p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp2.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1HJFzCnNx4SdC9UR_LKa7-P2xKUz8Fp06?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 3 -->
<div class="card">
    <h2>Experiment 3 — Classification with DL Frameworks</h2>
    <p>MNIST/Fashion-MNIST preprocessing, training, validation, and performance evaluation.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp3.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/118MaTGKLMyaXpPgBYVWlM-KWyYa0DA_b?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 4 -->
<div class="card">
    <h2>Experiment 4 — Transfer Learning for Image Classification</h2>
    <p>Feature extraction, fine-tuning strategies using pretrained CNNs on CIFAR-10 or Cats vs Dogs.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp4.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1nuBfkQNFDtnJE9527N61rzPJR_hPSxAL?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 5 -->
<div class="card">
    <h2>Experiment 5 — Training Deep Networks</h2>
    <p>
        • Activation & Loss Function Visualization<br>
        • Backpropagation Implementation<br>
        • Optimizer Comparison
    </p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp5.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1qqk3nwOxXuC7JZLGj-FkJHQOUcg3JhEn?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 6 -->
<div class="card">
    <h2>Experiment 6 — Implementation of MLP</h2>
    <p>Fully connected neural network creation, training, evaluation and visualization.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp6.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1wPi0ayzv74nrS3TQgt9ZD37-ByxF8kfz?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 7 -->
<div class="card">
    <h2>Experiment 7 — Implementing CNN</h2>
    <p>Convolution, pooling, feature map visualization for understanding CNN architectures.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp7.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1hzq6UM7t5qeuRAvvEkLb7sR-Ky32Tt7O?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 8 -->
<div class="card">
    <h2>Experiment 8 — CNN with Data Augmentation</h2>
    <p>Enhanced image classification using augmentation techniques like rotation, zoom, shift.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp8.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1xQwsFCUmMHiIsYeeT-QX0pMUdW_EYrwO?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 9 -->
<div class="card">
    <h2>Experiment 9 — CNN Object Detection</h2>
    <p>Bounding box prediction, detection pipelines, and evaluation techniques.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp9.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1De4B6xDq_skp8m5gOIUQ5V9gSa_YX20c?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 10 -->
<div class="card">
    <h2>Experiment 10 — Basic Object Detection using R-CNN</h2>
    <p>R-CNN pipeline: Selective search, region proposal, feature extraction, classification.</p>
</div>

<!-- EXP 11 -->
<div class="card">
    <h2>Experiment 11 — Image Segmentation with UNet</h2>
    <p>Encoder-decoder UNet framework for pixel-wise semantic segmentation.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp11.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://www.kaggle.com/api/v1/datasets/download/pushkar007/vaihingendataann?dataset_version_number=1">Dataset Link</a>
</div>

<!-- EXP 12 -->
<div class="card">
    <h2>Experiment 12 — Autoencoders for Image Reconstruction</h2>
    <p>Latent space visualization, dimensionality reduction, reconstruction learning.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp12.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/10iflWSc4i78Z2SDtdpkwN4Ab1XUJrvHf?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 13 -->
<div class="card">
    <h2>Experiment 13 — Variational Autoencoders (VAEs)</h2>
    <p>Probabilistic modeling, latent distribution learning and novel image generation.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp13.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1aVWVPN9fC18fc3aM9JjRFOCLH90MLcSJ?usp=drive_link">Dataset Link</a>
</div>

<!-- EXP 14 -->
<div class="card">
    <h2>Experiment 14 — Generative Adversarial Networks (GANs)</h2>
    <p>GAN training, generator–discriminator design, realistic synthetic image generation.</p>
    <a class="btn exp-btn" href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp14.ipynb">Experiment Link</a>
    <a class="btn dataset-btn" href="https://drive.google.com/drive/folders/1eaKCYKqI8ZzTxTHHxi5iDvrVUvgS6tze?usp=drive_link">Dataset Link</a>
</div>

</div>

</body>
</html>
