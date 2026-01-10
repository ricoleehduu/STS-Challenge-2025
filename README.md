README.md
# 🦷 STSR 2025: 3rd Semi-supervised Teeth Segmentation and Registration MICCAI Challenge  
**MICCAI 2025, Daejeon, Republic of Korea | September 23-27, 2025**  

[Challenge Main Website](https://songhen15.github.io/STSdevelop.github.io/miccai2025/index.html)

---

## 📖 Table of Contents
- [Introduction](#-introduction)
- [Tracks](#-tracks)
- [Rankings](#-rankings)
- [Important Dates](#-important-dates-pst)
- [Contact](#-contact)
- [Citation](#-citation)

---

## 📌 Introduction  
Computer-aided diagnosis tools are increasingly popular in modern dental practice, particularly for treatment planning or comprehensive prognosis evaluation. With the advancement of oral digitalization and three-dimensional scanning technology, cone-beam computed tomography (CBCT) and intraoral scanning (IOS) have been widely applied in clinical dental treatment. Intraoral scanning (IOS) models offer high resolution, relying solely on IOS data for treatment carries the risk of insufficient root information. Conversely, CBCT provides comprehensive information on both crowns and roots, but its scanning resolution is lower, and it contains more redundant information. Therefore, combining the two can better utilize their complementary strengths, enhancing the precision and efficiency of dental treatment. Furthermore, automated and precise evaluation of root pulp canals in CBCT images holds significant importance, as it can substantially enhance the precision and efficiency of root pulp canals treatment. Precise segmentation of the root pulp canal allows for a clearer visualization of its morphology, branches, and curvatures, facilitating the development of more refined filling strategies. However, the annotation of tooth root pulp canal regions in CBCT images is inherently labor-intensive, requiring a substantial investment of time and human resources.

In this year, building upon the previous semi-supervised challenge theme, we host two novel subtasks, which are semi-supervised CBCT-IOS registration and CBCT teeth and root pulp segmentation. We are proud to announce the launch of the challenge workshop. If you are interested in publishing a workshop paper, please 👉read the CfP and submit your paper.

---

## 🏁 Tracks  

### Track 1: CBCT teeth and root pulp canal segmentation
![panoramic-image](D:\work\2025-10-26\code\STS-Challenge-2025\assets\segmentation-1.png)
The segmentation algorithm is expected to segment all the teeth and root pulp canal accurately.

[CLICK ME TO JOIN🔥](#)

### Track 2: CBCT-IOS registration
![cbct-image](D:\work\2025-10-26\code\STS-Challenge-2025\assets\registration-1.png)
The registration algorithm is expected to register the teeth crown and the corresponding root.

[CLICK ME TO JOIN🔥](#)

---

## 📊 Rankings

### Track 1: CBCT teeth and root pulp canal segmentation

| Rank | Team ID | Title | Report | Code |
|------|---------|-------|--------|------|
| 1st | 21 | U-Mamba2 SSL for Semi Supervised | [PDF](./TechnicalReport/task1/rank01-21_U_Mamba2_SSL_for_Semi_Super.pdf) | [Code](./code/task1/rank01-Tan%20Zhi%20Qin.zip) |
| 2nd | 19 | Efficient nnU-Net for Tooth | [PDF](./TechnicalReport/task1/rank02-19_Efficient_nnU_Net_for_Tooth.pdf) | [Code](./code/task1/rank02-changkaiJi.zip) |
| 3rd | 23 | nnUNet for Semi supervised | [PDF](./TechnicalReport/task1/rank03-23_nnUNet_for_Semi_supervised_.pdf) | [Code](./code/task1/rank03-dicemed.zip) |
| 4th | 25 | TCM-UNet: A U-Net with Tri Attention | [PDF](./TechnicalReport/task1/rank04-25_TCM_UNet_A_U_Net_with_Tri_A.pdf) | - |

### Track 2: CBCT-IOS registration

| Rank | Team ID | Title | Report | Code |
|------|---------|-------|--------|------|
| 1st | 24 | Semi supervised Teeth Segme | [PDF](./TechnicalReport/task2/rank01-24_Semi_supervised_Teeth_Segme.pdf) | [Code](./code/task2/rank01-dicemed.zip) |
| 2nd | 20 | Learning based CBCT IOS Reg | [PDF](./TechnicalReport/task2/rank02-20_Learning_based_CBCT_IOS_Reg.pdf) | [Code](./code/task2/rank02-dicemed.zip) |

---

## 🗓️ Important Dates (PST)

| Event                                | Date         |
| ------------------------------------ | ------------ |
| Registration Open                    | April 25     |
| Challenge Validation Deadline        | August 15    |
| Challenge Final Deadline             | August 22    |
| Announcement of Challenge Winners    | August 31    |
| Conference Date                      | September 23-27 |

---

## 📧 Contact
For any inquiries, please feel free to reach out via email at SemiTeethSegChallenge@outlook.com or zhi.li@hdu.edu.cn. We welcome any questions, feedback, or requests for further information regarding the STSR 2025 Challenge. If you have urgent or additional needs, We look forward to meeting each one of you this year, face to face if possible. See you at Daejeon, Republic of Korea!

## 📚 Citation
If you use this challenge in your research, please cite it as follows:

```
@dataset{sts-challenge-2025,
  author = {STSR Challenge Organizers},
  title = {STSR 2025: 3rd Semi-supervised Teeth Segmentation and Registration MICCAI Challenge},
  year = {2025},
  publisher = {MICCAI 2025},
  url = {https://songhen15.github.io/STSdevelop.github.io/miccai2025/index.html}
}
```

Copyright @ College of Media Engineering, Communication University of Zhejiang, Hangzhou, 310018, China.