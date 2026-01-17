[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![Survey Paper](https://img.shields.io/badge/Paper-arXiv-blue.svg?style=flat)](https://arxiv.org/abs/2403.04279) 
[![visitors](https://visitor-badge.laobi.icu/badge?page_id=Chengyuann.Awesome-Anomalous-Sound-Detection-Methods)](https://visitor-badge.laobi.icu/badge?page_id=Chengyuann.Awesome-Anomalous-Sound-Detection-Methods)

![Anomalous-Sound-Detection](Anomalous-sound-detection.png)
## 🔖 News!!!

📌 We are actively tracking the latest research and welcome contributions to our repository and survey paper. If your studies are relevant, please feel free to contact us.

## 🎁 How to contribute to this repository?
Since the following content is generated based on our database, please provide the following information in the **issue** to help us fill in the database to add new papers (please do not submit a PR directly).
```text
1. Paper title
2. arXiv ID (if any)
3. Publication status (if any)
```

## Review and Count

|  Pub | Year      |Datasets                                                 | Note       |
| :--: | --------- | ------------------------------------------------------------ |---------- |
| ICASSP | 2020-2025   | DCASE2020 /DCASE2022        |           |
| TSALP | 2023、2025 |DCSASE |          |
| SPL | 2025 |DCSASE |          |
| Applied Acoustics | 2023  | DCASE |        |
| ArXiv   | ArXiv     | DCASE | ...|
| DCASE | 2020-2024 | DCASE |            |
| EUSIPCO| 2018、2021 | Sound Ideas Series 6000 General Sound Effects Library 、DCASE |            |
|ICCE| 2020 | MIMII  |            |
|Digital Signal Processing| 2023 | DCASE |            |


<details>
  <summary>🗂️ Table of Contents</summary>
  <ol>
    <li><a href="#papers">📝 Papers</a>
      <ul>
        <li><a href="#diffusion-models">Dual Models</a></li>
        <li><a href="#consistency-models">Generative Models</a></li>
      </ul>
    </li>
    <li><a href="#other-resources">🔗 Other Resources</a></li>
    <li><a href="#contributing">✍️ Contributing</a></li>
  </ol>
</details>

# 🗂️ dataset 

## DCASE20

Download the dataset from **[Audio dataset.](https://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds)**

 
# 📝 Papers

## ICASSP

### Dual Models


 
1. **[SW-WAVENET: Learning Representation from Spectrogram and Wavegram Using Wavenet for Anomalous Sound Detection.](https://ieeexplore.ieee.org/document/10096742)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/f28cb505-0edb-4525-9fff-dbc68e1f8311)


    *H. Chen, L. Ran, X. Sun and C. Cai.* ICASSP'24. 🔥
  


1. **[NOISY-ARCMIX: ADDITIVE NOISY ANGULAR MARGIN LOSS COMBINED WITH MIXUP FOR ANOMALOUS SOUND DETECTION.](https://arxiv.org/pdf/2310.06364)** **[CODE.](https://github.com/soonhyeon/Noisy-ArcMix)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/28b5f3af-3a5e-4998-807c-2455818d5b92)


   *Soonhyeon Choi, Jung-Woo Choi.* ICASSP'24. 🔥



1. **[A DUAL-PATH FRAMEWORK WITH FREQUENCY-AND-TIME EXCITED NETWORK FOR ANOMALOUS SOUND DETECTION.](https://ieeexplore.ieee.org/document/10448126)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/2c6d35a5-a985-4752-94be-a08c27066db8)


    *Yucong Zhang, Juan Liu, Yao Tian, Haifeng Liu, Ming Li.* ICASSP'24. 🔥

1. **[Hierarchical Metadata Information Constrained Self-Supervised Learning for Anomalous Sound Detection under Domain Shift.](https://ieeexplore.ieee.org/document/10446044)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/ca477908-5818-4462-a578-dfb968fb2240)


    *H. Lan, Q. Zhu, J. Guan, Y. Wei and W. Wang.* ICASSP'24. 🔥


1. **[DP-MAE: A Dual-Path Masked Autoencoder Based Self-Supervised Learning Method for Anomalous Sound Detection.](https://ieeexplore.ieee.org/document/10447859)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/ce768e73-eeb3-495c-9993-99735b557023)



    *Z. -L. Liu, Y. Song, X. -M. Zeng, L. -R. Dai and I. McLoughlin.* ICASSP'24. 🔥
   

1. **[Anomalous Sound Detection Using Audio Representation with Machine ID Based Contrastive Learning Pretraining.](https://arxiv.org/pdf/2304.03588v1)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/9f92cedf-d330-4898-9b4f-50c8c03030ff)




    *J. Guan, F. Xiao, Y. Liu, Q. Zhu and W. Wang.* ICASSP'23. 🔥


1. **[Anomalous Sound Detection Using Spectral-Temporal Information Fusion.](https://ieeexplore.ieee.org/document/9747868)**
*[code](https://github.com/liuyoude/STgram_MFN)*

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/18ecfb5e-e7a7-40aa-bc6e-b87aa46817fa)





    *Youde Liu; Jian Guan; Qiaoxi Zhu; Wenwu Wang.* ICASSP'22. 🔥
   
## Generative Models

1. **[UNSUPERVISED ANOMALY DETECTION AND LOCALIZATION OF MACHINE AUDIO: A GAN-BASED APPROACH.](https://arxiv.org/pdf/2303.17949)**
2. **[\[CODE\]](https://github.com/jianganbai/AEGAN-AD)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/ef858605-5df5-426e-9a23-c7c56cbed4c7)



    *A. Jiang, W. -Q. Zhang, Y. Deng, P. Fan and J. Liu.* ICASSP'23. 🔥


## GMM Models


1. **[Time-Weighted Frequency Domain Audio Representation with GMM Estimator for Anomalous Sound Detection.](https://ieeexplore.ieee.org/document/10096356)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/957fbe31-43f3-4429-b0e9-41af4925c900)




    *A. Jiang, W. -Q. Zhang, Y. Deng, P. Fan and J. Liu.* ICASSP'23. 🔥


### Other Models

1. **[Improvements of Discriminative Feature Space Training for Anomalous Sound Detection in Unlabeled Conditions.](https://ieeexplore.ieee.org/document/10890020)**


    *Takuya Fujimura et al.* ICASSP'25. 🔥

1. **[An Effective Anomalous Sound Detection Method Based on Representation Learning with Simulated Anomalies.](https://ieeexplore.ieee.org/document/10095398)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/a2ef8ad6-bf70-443b-8a15-001601ff7b36)




    *H. Chen et al.* ICASSP'23. 🔥

1. **[Self-Supervised Representation Learning for Unsupervised Anomalous Sound Detection Under Domain Shift.](https://ieeexplore.ieee.org/document/9747863)**

    ![image](https://github.com/Chengyuann/Awesome-Anomalous-Sound-Detection-Methods/assets/91605267/c2f87fcc-9582-440b-80d6-91c8b296b2a2)

    


    *H. Chen, Y. Song, L. -R. Dai, I. McLoughlin and L. Liu.* ICASSP'23. 🔥

1. **[Noise Supervised Contrastive Learning and Feature-Perturbed for Anomalous Sound Detection.](https://arxiv.org/abs/2509.13853)**



    <img width="1572" height="348" alt="image" src="https://github.com/user-attachments/assets/fd22716b-f72f-45f9-9a78-2b25295df67f" />



    *S. Huang, Z. Fang, L. and L. He.* ICASSP'25. 🔥
   
## SPL

1. **[ESTM: An Enhanced Dual-Branch Spectral-Temporal Mamba for Anomalous Sound Detection](https://ieeexplore.ieee.org/abstract/document/10329432)**

    <img width="1406" height="518" alt="image" src="https://github.com/user-attachments/assets/3db6e040-f730-41f2-8687-a3687cb8b090" />

*C. Ma, P. Jia  and W. Yang.* SPL'25. 🔥

## TASLP

1. **[Why Do Angular Margin Losses Work Well for Semi-Supervised Anomalous Sound Detection?](https://ieeexplore.ieee.org/document/11152580)**

    ![image](https://github.com/user-attachments/assets/3467a877-8782-4f39-a199-b6ebaf1a043e)





    *HK. Wilkinghoff and F. Kurth.* IEEE/ACM Transactions on Audio, Speech, and Language Processing 2023. 🔥

1. **[Why Do Angular Margin Losses Work Well for Semi-Supervised Anomalous Sound Detection?](https://ieeexplore.ieee.org/abstract/document/10329432)**

    ![image](https://github.com/user-attachments/assets/3467a877-8782-4f39-a199-b6ebaf1a043e)





    *HK. Wilkinghoff and F. Kurth.* IEEE/ACM Transactions on Audio, Speech, and Language Processing 2023. 🔥


1. **[AdaProj: Adaptively Scaled Angular Margin Subspace Projections for Anomalous Sound Detection with Auxiliary Classification Tasks](https://arxiv.org/abs/2403.14179)**

    ![image](https://github.com/user-attachments/assets/5122fb5a-9a12-46d1-9eff-53e572065293)






    *Kevin Wilkinghoff.* DCASE 2024. 🔥


## Applied Acoustics
 
   1. **[Unsupervised anomalous sound detection for industrial monitoring based on ArcFace classifier and gaussian mixture model](https://www.sciencedirect.com/science/article/pii/S0003682X2200562X)**

![image](https://github.com/user-attachments/assets/f02cb36a-67a6-4a46-b654-1d238828109f)

  *Ji Wu ,Fei Yang .* Applied Acoustics Volume 203, 28 February 2023, 109188. 🔥


<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>
