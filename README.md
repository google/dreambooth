# DreamBooth Dataset
## DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation

![teaser](docs/teaser_static.jpg)

### [project page](https://dreambooth.github.io/) | [arxiv](https://arxiv.org/abs/2208.12242)

This is the official repository for the dataset of the Google paper DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation.

## Dataset

The dataset includes 30 subjects of 15 different classes. 9 out of these subjects are live subjects (dogs and cats) and 21 are objects. The dataset contains a variable number of images per subject (4-6). Images of the subjects are usually captured in different conditions, environments and under different angles.

We include a file dataset/prompts\_and\_classes.txt which contains all of the prompts used in the paper for live subjects and objects, as well as the class name used for the subjects.

The images have either been captured by the paper authors, or sourced from www.unsplash.com

The dataset/references\_and\_licenses.txt file contains a list of all the reference links to the images in www.unsplash.com - and attribution to the photographer, along with the license of the image.

## Academic Citation

If you use this work please cite:
```
@inproceedings{ruiz2023dreambooth,
  title={Dreambooth: Fine tuning text-to-image diffusion models for subject-driven generation},
  author={Ruiz, Nataniel and Li, Yuanzhen and Jampani, Varun and Pritch, Yael and Rubinstein, Michael and Aberman, Kfir},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2023}
}
```

## Disclaimer

This is not an officially supported Google product.
