# Style Transfer functionality for StyleGAN 2 in PyTorch

Refer to [this](https://www.youtube.com/watch?v=kSLJriaOumA) video for understanding style transfer

Use the colab notebook [stylegan-2-style-transfer.ipynb](stylegan_2_style_transfer.ipynb) for complete implementation

#### Coarse Style transfer
Transfer posture and hair  
Refer `transfer_coarse_latent` in colab
![](sample/coarse_transfer_bearded-man.png)
![](sample/coarse_transfer_kid-worried.png)
![](sample/coarse_transfer_frontal-black-hair-female.png)

Transfer facial features such as eyes and nose  
Refer `transfer_middle_latent` in colab
![](sample/middle_transfer_bearded-man.png)
![](sample/middle_transfer_kid-worried.png)
![](sample/middle_transfer_frontal-black-hair-female.png)

Transfer minor features - mainly color scheme  
Refer `transfer_fine_latent` in colab
![](sample/fine_transfer_bearded-man.png)
![](sample/fine_transfer_kid-worried.png)
![](sample/fine_transfer_frontal-black-hair-female.png)
