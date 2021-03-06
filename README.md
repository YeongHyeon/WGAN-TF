[TensorFlow] Wasserstein GAN (WGAN)
=====
TensorFlow implementation of Wasserstein GAN (WGAN) with MNIST dataset.  

### Training algorithm
<div align="center">
  <img src="./figures/algorithm.png" width="500">  
  <p>The algorithm for training WGAN [1].</p>
</div>

### WGAN architecture
<div align="center">
  <img src="./figures/wgan.png" width="500">  
  <p>The architecture of WGAN [1].</p>
</div>

### Graph in TensorBoard
<div align="center">
  <img src="./figures/graph.png" width="650">  
  <p>Graph of WGAN.</p>
</div>

## Results

### Training Procedure
<div align="center">
  <p>
    <img src="./figures/WGAN_loss_d.svg" width="300">
    <img src="./figures/WGAN_loss_g.svg" width="300">
  </p>
  <p>Loss graph in the training procedure. </br> Each graph shows loss of the discriminator and loss of the generator respectively.</p>
</div>

### Test Procedure
<div align="center">

|z:2|z:2 (latent space walking)|
|:---:|:---:|
|<img src="./figures/z02.png" width="300">|<img src="./figures/z02_lw.png" width="300">|

|z:64|z:128|
|:---:|:---:|
|<img src="./figures/z64.png" width="300">|<img src="./figures/z128.png" width="300">|

</div>

## Environment
* Python 3.7.4  
* Tensorflow 1.14.0  
* Numpy 1.17.1  
* Matplotlib 3.1.1  
* Scikit Learn (sklearn) 0.21.3  


## Reference
[1] Martin Arjovsky et al. (2017). <a href="https://arxiv.org/abs/1701.07875">Wasserstein GAN</a>. arXiv preprint arXiv:1701.07875.  
