# Gaussian Splatting Experiments
The goal of these experiments is to create high-quality 3D videos with few cameras.  
Click on videos for higher-resolution  
## Static Gaussian Experiments

### Vanilla 3D-Gaussian-Splatting (3DGS)
[![roses_colmap_gauss](https://github.com/user-attachments/assets/776cce9d-6d4a-4f86-a776-02d7a276797d)](https://youtu.be/O_t5jwG39uw)

### FSGS: 3DGS with depth priors
![og](https://github.com/user-attachments/assets/0ffbd0c3-dba5-4f21-8b2b-e38a9a347dec) ![depth](https://github.com/user-attachments/assets/f3932ff2-bb14-4687-b18f-340fecef90ab)


### 3DGS with dense pointcloud, obtained from Mast3r, as prior
[![roses_mast3r_gauss (1) (1)](https://github.com/user-attachments/assets/d47d3dc1-bd94-4a22-b09e-a064768d9752)](https://youtu.be/jNGTl8pLf7g)  

## Dynamic Gaussian Experiments

### 4DGS

### Spacetime Gaussians
[![4_cam_roses_colmap_spacetime-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/b95497dc-91ff-4451-9fa5-1ff3673aaf13)](https://youtu.be/eIgOtSkR4Ls)

#### Spacetime Gaussians with Mast3r
[![4_cam_roses_mast3r_spacetime2 (1)](https://github.com/user-attachments/assets/a00ab2bf-64c2-4068-8efe-4d963d5306d6)](https://youtu.be/JJ4vPwudxCc)




## Diffusion Experiments

## Comparison of different image-matching methods for pointcloud reconstruction
### Colmap
![colmap_roses](https://github.com/user-attachments/assets/df38e204-1e88-43e2-9deb-7c7e23ddfade)  
Incredibly sparse with 391 points

### Flowmap
[![flowmap_4_cam_roses](https://github.com/user-attachments/assets/26284a83-fd93-4de3-b924-1396e8c7847d)](https://youtu.be/9_5DGcGhbrA)  
Output is a dense cloud with ~205K points
### Dust3r
### Mast3r
[![4_cam_roses_mast3r](https://github.com/user-attachments/assets/08d840b5-696e-4b73-a9b7-cf7369d02fd8)](https://youtu.be/EXme5P8LEPc)  
Output is a dense cloud with ~188K points

