# TransGAN: Two Transformers Can Make One Strong GAN
Code used for [TransGAN: Two Transformers Can Make One Strong GAN](https://https://github.com/yueruchen/TransGAN). 

## Main Pipeline
![Main Pipeline](assets/TransGAN.png)

## Visual Results
![Visual Results](assets/Visual_results.pdf)

### prepare fid statistic file
 ```bash
mkdir fid_stat
 ```
Download the pre-calculated statistics
([Google Drive](https://drive.google.com/drive/folders/1UUQVT2Zj-kW1c2FJOFIdGdlDHA3gFJJd?usp=sharing)) to `./fid_stat`.


## Acknowledgement
1. Inception Score code from [OpenAI's Improved GAN](https://github.com/openai/improved-gan/tree/master/inception_score) (official).
2. FID code and CIFAR-10 statistics file from [https://github.com/bioinf-jku/TTUR](https://github.com/bioinf-jku/TTUR) (official).
3. Codebase from [AutoGAN](https://github.com/VITA-Group/AutoGAN)
