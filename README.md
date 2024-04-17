# DATENeRF: Depth-Aware Text-based Editing of NeRFs

Welcome to the official repository for DATENeRF.

Abstract. Recent advancements in diffusion models have shown remarkable proficiency in editing 2D images based on text prompts. However, extending these techniques to edit scenes in Neural Radiance Fields (NeRF) is complex, as editing individual 2D frames can result in inconsistencies across multiple views. Our crucial insight is that a NeRF scene's geometry can serve as a bridge to integrate these 2D edits. Utilizing this geometry, we employ a depth-conditioned ControlNet to enhance the coherence of each 2D image modification. Moreover, we introduce an inpainting approach that leverages the depth information of NeRF scenes to distribute 2D edits across different images, ensuring robustness against errors and resampling challenges. Our results reveal that this methodology achieves more consistent, lifelike, and detailed edits than existing leading methods for text-driven NeRF scene editing.

## Pipeline

![DATENeRF Pipeline](https://github.com/sararoma95/DATENeRF/blob/main/pipeline.png)

## Resources and Setup

- **ArXiv Paper**: Access our detailed research paper [here](https://arxiv.org/abs/2404.04526).


## Checklist

- [x] Read the **ArXiv paper**
- [x] Clone the **GitHub repo**
- [ ] Setup **Our Version of Nerfstudio**
- [ ] Learn **How to get the masks**
- [ ] Learn **How to get the distance maps**
- [ ] Learn **How to get robust masks**
- [ ] Explore **ControlNet**
- [ ] Try out **Commands for DATENeRF**
- [ ] Practice **How to insert objects**

