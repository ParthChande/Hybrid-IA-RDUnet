# Hybrid-IA-RDUnet
 Image and video dehazing are essential tasks in Image Reconstruction, crucial for restoring the visibility and clarity of scenes obscured by haze, fog, or smoke. Unlike conventional methods, which often struggle with preserving fine details and color fidelity, the Hybrid IA-RDUNet excels in enhancing image quality by leveraging advanced feature extraction and reconstruction techniques. The model combines the encoder-decoder structure of UNet with the advanced feature extraction capabilities of Residual Dense Networks (RDN), augmented by Intensity Attention Blocks to emphasize critical features and Sub-Pixel Upsampling for precise image reconstruction. Comprehensive evaluations on benchmark datasets, including REVIDE, NH-HAZE, SOTS, D-Hazy, and I-Haze, reveal that our approach significantly outperforms existing methods in terms of PSNR, SSIM, and color accuracy. The Hybrid IA-RDUNet model offers a robust, efficient, and perceptually superior solution for enhancing visual content under hazy conditions.

## Model Architecture
![Architecture (4)](https://github.com/user-attachments/assets/78f0a376-dd70-4944-bb2c-b53c511c7359)
![Model (4)](https://github.com/user-attachments/assets/7c1896ef-a2a1-4e3f-a849-06b98a1cdd68)


## Datasets can be downloaded from below given links

[REVIDE-inside](https://www.kaggle.com/datasets/hannahkamundson/revide-indoor/data) 
[NH-HAZE](https://paperswithcode.com/dataset/nh-haze) 
[SOTS](https://www.kaggle.com/datasets/balraj98/synthetic-objective-testing-set-sots-reside) 
[D-Hazy](https://paperswithcode.com/dataset/d-hazy) 
[I-Haze](https://paperswithcode.com/dataset/i-haze-1) 

## Qualitative Results
### REVIDE-inside
![OUTPUT_REVIDE (4)](https://github.com/user-attachments/assets/caf605c3-bb58-465c-8bde-6df4de431bea)

### SOTS
![OUTPUT_SOTS (4)](https://github.com/user-attachments/assets/a85f6eae-3fda-4592-aedc-e70aac88602a)

