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
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Experiments Layout</title>
<style>
  body {
    background: #0d0d0d;
    font-family: Arial, sans-serif;
    color: white;
    margin: 0;
    padding: 20px;
  }

  .container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
  }

  .experiment-card {
    background: #1a1a1a;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(255,255,255,0.1);
  }

  .experiment-title {
    font-size: 22px;
    font-weight: bold;
    margin-bottom: 15px;
  }

  .description {
    font-size: 15px;
    margin-bottom: 20px;
  }

  .btn-container {
    display: flex;
    gap: 10px;
  }

  .dataset-btn {
    background: #0066ff;
    color: white;
    padding: 10px 15px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
  }

  .exp-btn {
    background: #ff8800;
    color: white;
    padding: 10px 15px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
  }
</style>
</head>
<body>
<h1 style="text-align:center; font-size:40px; margin-bottom:30px;">Deep Learning Lab Experiments</h1>

<div class="container">

  <!-- Experiment 1 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 1: Comparative Study of Deep Learning Frameworks</div>
    <div class="description">Comparison of popular DL frameworks focusing on performance, usability, and workflow differences.</div>
    <div class="btn-container">
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp1.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 2 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 2: Building Neural Networks from Scratch</div>
    <div class="description">Implement AND gate neuron, FFNN for XOR/AND, and full MLP model from scratch.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1HJFzCnNx4SdC9UR_LKa7-P2xKUz8Fp06?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp2.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 3 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 3: Classification with DL Frameworks</div>
    <div class="description">MNIST / Fashion-MNIST classification with preprocessing, training, and evaluation.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/118MaTGKLMyaXpPgBYVWlM-KWyYa0DA_b?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp3.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 4 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 4: Transfer Learning for Image Classification</div>
    <div class="description">Feature extraction & fine-tuning using pretrained CNNs on Cats vs Dogs / CIFAR-10.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1nuBfkQNFDtnJE9527N61rzPJR_hPSxAL?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp4.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 5 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 5: Training Deep Networks</div>
    <div class="description">Activation & loss visualization, backpropagation, and optimizer comparison.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1qqk3nwOxXuC7JZLGj-FkJHQOUcg3JhEn?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp5.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 6 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 6: Implementation of MLP</div>
    <div class="description">Design, train, and evaluate a multilayer perceptron model.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1wPi0ayzv74nrS3TQgt9ZD37-ByxF8kfz?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp6.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 7 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 7: Implementing CNN</div>
    <div class="description">Convolution, pooling, and visualization of feature maps.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1hzq6UM7t5qeuRAvvEkLb7sR-Ky32Tt7O?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp7.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 8 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 8: CNN with Data Augmentation</div>
    <div class="description">Image classification using CNN enhanced with augmentation strategies.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1xQwsFCUmMHiIsYeeT-QX0pMUdW_EYrwO?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp8.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- Experiment 9 -->
  <div class="experiment-card">
    <div class="experiment-title">Experiment 9: CNN Object Detection</div>
    <div class="description">Object detection using bounding box prediction and CNN architecture.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1De4B6xDq_skp8m5gOIUQ5V9gSa_YX20c?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp9.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <!-- The rest (10–14) already present and previously generated -->

</div>
    <div class="description">Description for Experiment 1 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 2</div>
    <div class="description">Description for Experiment 2 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 3</div>
    <div class="description">Description for Experiment 3 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 4</div>
    <div class="description">Description for Experiment 4 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 5</div>
    <div class="description">Description for Experiment 5 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 6</div>
    <div class="description">Description for Experiment 6 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 7</div>
    <div class="description">Description for Experiment 7 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 8</div>
    <div class="description">Description for Experiment 8 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 9</div>
    <div class="description">Description for Experiment 9 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 10</div>
    <div class="description">Description for Experiment 10 goes here...</div>
    <div class="btn-container">
      <a href="#" class="dataset-btn">Dataset</a>
      <a href="#" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 11</div>
    <div class="description">Image Segmentation with UNet – Semantic segmentation using encoder‑decoder UNet architecture for pixel‑wise predictions.</div>
    <div class="btn-container">
      <a href="https://www.kaggle.com/api/v1/datasets/download/pushkar007/vaihingendataann?dataset_version_number=1" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp11.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 12</div>
    <div class="description">Autoencoders for Image Reconstruction – Dimensionality reduction, feature compression, latent space learning.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/10iflWSc4i78Z2SDtdpkwN4Ab1XUJrvHf?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp12.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 13</div>
    <div class="description">Variational Autoencoders – Probabilistic modeling, latent distribution learning, novel image generation.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1aVWVPN9fC18fc3aM9JjRFOCLH90MLcSJ?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp13.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

  <div class="experiment-card">
    <div class="experiment-title">Experiment 14</div>
    <div class="description">Generative Adversarial Networks – Adversarial training, generator–discriminator architecture, synthetic image generation.</div>
    <div class="btn-container">
      <a href="https://drive.google.com/drive/folders/1eaKCYKqI8ZzTxTHHxi5iDvrVUvgS6tze?usp=drive_link" class="dataset-btn">Dataset</a>
      <a href="https://github.com/AbhinavDwivediii/DL_LAB_500121151_ABHINAV_DWIVEDI/blob/main/DL_Exp14.ipynb" class="exp-btn">Open Experiment</a>
    </div>
  </div>

</div>

</body>
</html>
