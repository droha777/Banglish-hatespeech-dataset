# Banglish Hate Speech Detection: Benchmark Dataset
**Authors:** Droha Deb, Moloy Kumar Ghosh, Md. Fojlea Rabbi, Durjoy Saha, Oishi Jyoti, Pratyay Gope Tarapdar

## Overview
The widespread use of social media in Bangladesh has led to a growing volume of user-generated content written in Banglish (Bangla expressed in English alphabets). This repository contains a manually annotated Banglish hate speech dataset designed to address the lack of dedicated linguistic resources for this low-resource language.

The dataset provides a comparative framework supporting both binary and fine-grained multi-class classification, collected from public user comments on Facebook and YouTube.

## Dataset Paper
The official dataset paper has been published in the 2026 IEEE 2nd International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN). 

**Read the full paper on IEEE Xplore:** 
https://ieeexplore.ieee.org/document/11546128/

## Dataset Statistics
### Binary Classification
The binary dataset consists of 31,834 total samples:
* **Not hate:** 18,757 samples
* **Hate:** 13,077 samples

### Multi-class Classification
The 13,077 hate instances are categorized into six fine-grained classes:
* **Personal:** 2,791 samples
* **Religious:** 2,305 samples
* **Sexual:** 2,247 samples
* **Geopolitical:** 2,077 samples
* **Crime:** 1,981 samples
* **Political:** 1,676 samples

## Dataset Samples
Figure 1 and Figure 2 show sample annotated Banglish hate speech comments from the proposed dataset.

#### Figure 1 : Multi-class dataset sample
<img width="507" height="203" alt="WhatsApp Image 2026-09-18 at 18 53 59" src="https://github.com/user-attachments/assets/603d9c38-e60c-4fc7-aaed-09bc4adba6c7" />

#### Figure 2 : Binary-class dataset sample
<img width="507" height="113" alt="WhatsApp Image 2026-09-18 at 18 58 24" src="https://github.com/user-attachments/assets/db4cc13b-95d9-4c9d-b46b-ced535fe5601" />

## Citation
If you use this dataset in your research, please cite our paper:

```bibtex
@inproceedings{deb2026banglish,
  title={Banglish Hate Speech Detection: A Benchmark Dataset \& Comparative Framework for Binary \& Multi-Class Classification},
  author={Deb, Droha and Rabbi, Md Fojlea and Jyoti, Oishi and Ghosh, Moloy Kumar and Saha, Durjoy and Tarapdar, Pratyay Gope},
  booktitle={2026 IEEE 2nd International Conference on Quantum Photonics, Artificial Intelligence \& Networking (QPAIN)},
  pages={1--6},
  year={2026},
  organization={IEEE}
}
