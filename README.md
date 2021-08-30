# Dataset for ICIP-2020 Challenge titled "Real-time distortion classification in laparoscopic videos"

## Challenge Site
The challenge was hosted at CodaLab and can be accessed at the following link

[Challenge Link](https://competitions.codalab.org/competitions/25104)

## Train Dataset 
[Download Link for Training Set](https://drive.google.com/drive/folders/1Hq6omtZAOqAdUl9H3tJvoRp7gzpDoAl8?usp=sharing)

The password for the 7z archive is: lvq_icip20

The train dataset folder includes: 
- ICIP Laparoscopic Video Quality Challenge dataset:
  - 80 videos resulting from adding ADDITIVE WHITE GAUSSAIAN NOISE (AWGN) at 4 different levels as distortion to each reference video
  - 80 videos resulting from adding BLUR DUE TO DEFOCUS at 4 different levels as distortion to each reference video
  - 80 videos resulting from adding MOTION BLUR at 4 different levels as distortion to each reference video
  - 80 videos resulting from adding UNEVEN ILLUMINATION at 4 different levels as distortion to each reference video
  - 80 videos resulting from adding SMOKE at 4 different levels as distortion to each reference video
  - 100 videos resulting from adding both SMOKE and UNEVEN ILLUMINATION at 5 different combinations of severity levels 
  - 80 videos resulting from adding both BLUR DUE TO DEFOCUS and UNEVEN ILLUMINATION at 4 different combinations of severity levels 
  - 80 videos resulting from adding both AWGN and UNEVEN ILLUMINATION at 4 different combinations of severity levels 
  - 80 videos resulting from adding both AWGN and SMOKE at 4 different combinations of severity levels 
  - 60 videos resulting from adding AWGN, SMOKE and UNEVEN ILLUMINATION at 3 different combinations of severity levels 
  
 ## Dataset Description
 
This ICIP LVQ Challenge dataset consists of a total of 800 distorted videos, each of 10 seconds which have been generated using a set of 20 reference videos. These videos are extracted from Cholec80 dataset (http://camma.u-strasbg.fr/datasets). The selection of the videos is made with an attempt to include maximum possible variations of scene content and temporal information. For scene content, ten different categories are chosen. These are bleeding (BL), grasping and burning(GB), multiple instruments (MI), irrigation (IR), clipping (CL), stretching away (SA), cutting (CU), stretching forward (SF), organ extraction (OE) and burning (BU).

Each reference video is distorted by five different kinds of distortions (single or multiple distortions) with four different levels, resulting in a total of 800 videos. The resolution of the videos is 512 × 288 with a 16:9 aspect ratio and a frame-rate of 25 fps. We have used uncompressed avi format for the videos so as to avoid any kind of unwanted compression artefacts like blocking.

## Test Dataset

[Download Link for Test Set](https://drive.google.com/drive/folders/1i_zOEPmoLRicGMSwk8wHThL1TGW9p4lN)

The test dataset consists of 200 videos with individual as well as mixture of distortions.

## LICENCE AND REFERENCES

In case you publish any results based on the use of this database, please cite the following papers:

- **Khan, Z.A., Beghdadi, A., Cheikh, F.A., Kaaniche, M., Pelanis, E., Palomar, R., Fretland, Å.A., Edwin, B. and Elle, O.J., 2020, March. Towards a video quality assessment based framework for enhancement of laparoscopic videos. In Medical Imaging 2020: Image Perception, Observer Performance, and Technology Assessment (Vol. 11316, p. 113160P). International Society for Optics and Photonics.** 
- **Khan, Z.A., Beghdadi, A., Kaaniche, M. and Cheikh, F.A., 2020, October. Residual networks based distortion classification and ranking for laparoscopic image quality assessment. In 2020 IEEE International Conference on Image Processing (ICIP) (pp. 176-180). IEEE.**

And please also cite the following paper that led to the generation of the original dataset of Cholec80:

- A.P. Twinanda, S. Shehata, D. Mutter, J. Marescaux, M. de Mathelin, N. Padoy. EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos. IEEE Trans. on Medical Imaging 2016.

The ICIP LVQ Challenge dataset is publicly released under the Creative Commons licence **CC-BY-NC-SA 4.0**. This implies that:
- the dataset cannot be used for commercial purposes,
- the dataset can be transformed (additional annotations, etc.),
- the dataset can be redistributed as long as it is redistributed under the same license with the obligation to cite the contributing work which led to the generation of the LVQ and cholec80 datasets (mentioned above).

By downloading and using this dataset, you agree on these terms and conditions.

