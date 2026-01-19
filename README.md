# SEN12-season Dataset

SEN12-season is a SAR–optical paired dataset derived from the SEN1-2 dataset and curated in the paper:

**DOGAN: DINO-based Optical Prior-driven GAN for SAR-to-Optical Image Translation**

---

## Dataset Description

Due to the presence of duplicated regions and low-quality images in the original SEN1-2 dataset, such samples were excluded.
From the remaining data, 4,000 SAR–optical image pairs were selected based on two criteria: (1) scene diversity and (2) balanced seasonal distribution.

The selected subset was divided into:
- **3,200 image pairs for training**
- **800 image pairs for testing**

---

## Dataset Structure

The dataset is organized as follows:
 
```text
SEN12-season/
├── train/
│   ├── A/              # SAR images (Input)
│   └── B/              # Optical images (Target)
├── test/
│   ├── A/              # SAR images
│   └── B/              # Optical images
├── train.txt           # List of training image filenames
└── test.txt            # List of testing image filenames
 ```

---

## Download

The dataset is available via **Baidu Netdisk**:

- **Download link**:  
  https://pan.baidu.com/s/1gwdn4wWADaGcO8e-Bp1x0g?pwd=1qaz 

- **Extraction code**:  
  1qaz 

---

## Citation

If you use the SEN12-season dataset in your research, please cite the following paper:

```bibtex
@ARTICLE{11153532,
  author={He, Jingfei and Chen, Liang and Shi, Hao and Chen, Yuhang and Yang, Jingyi and Li, Wei},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={DOGAN: DINO-Based Optical-Prior-Driven GAN for SAR-to-Optical Image Translation}, 
  year={2025},
  volume={63},
  pages={1--16},
  doi={10.1109/TGRS.2025.3606979}
}

