# ELEC-509-Final-Project-MID-Diff
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

## Performance Evaluation of distilled diffusion models
<img width="430" alt="table_distillation" src="https://github.com/user-attachments/assets/96d7aa55-e79c-4ccd-931b-a57676357afd">
![speed_distillation](https://github.com/user-attachments/assets/71707a6d-d40f-43c4-9aa5-f9c621ad78f3)
![FID_distillation](https://github.com/user-attachments/assets/05684b00-aa8a-4036-bf8a-9b45611f5be0)
![lpips_distillation](https://github.com/user-attachments/assets/0801758e-5983-40b8-8772-ac49574727f1)

