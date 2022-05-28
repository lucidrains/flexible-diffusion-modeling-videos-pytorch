## Flexible Diffusion Modeling of Long Videos - Pytorch (wip)

Implementation of the video diffusion model and training scheme presented in the paper, <a href="https://arxiv.org/abs/2205.11495">Flexible Diffusion Modeling of Long Videos</a>, in Pytorch. While the Unet architecture does not look that novel (quite similar to <a href="https://github.com/lucidrains/video-diffusion-pytorch">Space-time factored unets</a>, where they do attention across time) they achieved up to 25 minutes of coherent video with their specific frame sampling conditioning scheme during training.

## Citations

```bibtex
@inproceedings{Harvey2022FlexibleDM,
    title   = {Flexible Diffusion Modeling of Long Videos},
    author  = {William Harvey and Saeid Naderiparizi and Vaden Masrani and Christian Weilbach and Frank Wood},
    year    = {2022}
}
```
