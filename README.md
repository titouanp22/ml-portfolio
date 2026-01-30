# ml-portfolio

# Machine Learning Portfolio – Titouan Pottier

MVA – ENS Paris-Saclay  

I am interested in research-oriented ML and applied problems, with a focus on
representation learning, evaluation, and reproducibility.


## MVA Projects

### Audio Super-Resolution
**Course:** [Deep learning and signal processing] – Prof. [T. COURTAT]  
**Collaborator:** [Maxime Muhlethaler]  

Upsampling low-resolution audio signals (4 kHz → 8 kHz) using deep learning models.  
- **Approaches:** Audio U-Net (encoder-decoder with skip connections), GAN with multi-band discriminator.  
- **Data:** ~2100 training samples, ~780 test samples; normalized to [-1, 1].  
- **Evaluation:** RMSD, LSD, SNR, STOI; visual and auditory inspection.  
- **Key Idea:** Neural networks reconstruct high-frequency content lost during downsampling.

Repo: [Mini-Project ML Audio Super-Resolution](https://github.com/titouanp22/Mini-Project-ML-Audio-Super-Resolution)  

---

### Semi-Supervised Medical Image Segmentation
**Course:** [Medical image analysis based on generative, geometric and biophysical models] – Prof. [H. DELINGETTE, X. PENNEC]  
**Collaborators:** [Nicolas Beaujoin, Maxime Muhlethaler]  

PyTorch reimplementation of a semi-supervised medical image segmentation method using local contrastive loss and pseudo-labeling.  
- **Architecture:** U-Net backbone with supervised Dice loss branch and contrastive branch on unlabeled images.  
- **Data:** ACDC, MSD Heart, CHAOS datasets; small labeled set + unlabeled images.  
- **Key Idea:** Contrastive learning improves feature representations when labeled data is limited.  
- **Tools:** Modular PyTorch framework, YAML configuration files, t-SNE visualizations.

Repo: [Contrastive MedSeg PyTorch Project](https://github.com/MaximeMuh/contrastive-medseg-pytorch_project)  

---

### Multi-scale Time–Frequency Denoising (BIRD)
**Course:** [Machine learning for time series] – Prof. [L. OUDRE]  
**Collaborator:** [Maxime Muhlethaler]  

Denoising neurophysiological (MEG) time-series using multi-scale MDCT-based greedy algorithms.  
- **Algorithms:** BIRD (mono-channel) and S-BIRD (structured multi-channel).  
- **Key Idea:** Iterative selection of the most relevant MDCT atoms across multiple scales, with automatic stopping criterion.  
- **Evaluation:** MSE, time-domain reconstruction quality, visual inspection.  
- **Application:** Noisy MEG signals.

Repo: [Mini-Project ML for Time Series](https://github.com/titouanp22/Mini-Project-ML-for-Time-Series)  

---

## Contact
- Email: titouan.pottier22@gmail.com
- LinkedIn: www.linkedin.com/in/titouan-pottier-ba744826a
