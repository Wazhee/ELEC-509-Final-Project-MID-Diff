# MID-Diff: **M**edical **I**mage **S**ynthesis using **D**istilled **Diff**usion Models
This goal of this project is to propose a novel method for fast medical image-to-image (I2I) synthesis.<br>
So far, I've accomplished the following tasks: (1) performed I2I synthesis using Brownian Bridge Diffusion Model (BBDM)<br>
and (2) evaluated the performance of BBDM under different parameters initializations. 

**Abstract:**

```
I present a novel method for Medical Image Synthesis using Distilled Diff usion Models
(MID-Diff). MID-Diff uses progressive distillation and denoising diffusion probabilistic
models (DDPM) for fast high quality medical image-to-image (I2I) translation. In this
paper, I discuss current state-of-art methods for medical I2I translation. I then discuss their
limitations and review methods for improving I2I translation quality and efficiency. Finally,
I review my plans for implementing MID-Diff and validating its efficacy. If validated on
larger sample size, MID-Diff has the potential to improve disease diagnosis and treatment
planning in low-resource clinical settings
```
## Preliminary Results
## Performance Evaluation of distilled diffusion models
<p align="center">
<img width="430" alt="table_distillation" src="https://github.com/user-attachments/assets/96d7aa55-e79c-4ccd-931b-a57676357afd">
</p>
<p align="center">
<img width="430" alt="speed_distillation" src="https://github.com/user-attachments/assets/99783904-6ce5-49bd-abce-55d100593900">
<img width="430" alt="table_distillation" src="https://github.com/user-attachments/assets/3aaaaa31-3b27-447c-b537-07d93a92e633">
</p>

<p align="center">
<img width="430" alt="table_distillation" src="https://github.com/user-attachments/assets/7adedf3b-77c8-4f81-ac47-b52ccac5632e">
</p>

