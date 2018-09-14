# MedicalDataAugmentationTool
This tool allows on-the-fly augmentation and training for networks in the medical imaging domain. It uses [SimpleITK](http://www.simpleitk.org/) to load and augment input data, and [Tensorflow](https://www.tensorflow.org/) to define and train networks.
Some example applications are under `bin/experiments`. I will add more examples the near future.
As this framework is mainly used for research, some files are not well documented. However, I'm working on improving this.
If you have problems or find any bugs, don't hesitate to send me a message.

## Citation
If you use this code for your research, please cite any of our papers.

[Instance Segmentation and Tracking with Cosine Embeddings and Recurrent Hourglass Networks](https://doi.org/10.1007/978-3-030-00934-2_1):

```
@inproceedings{Payer2018b,
  title     = {Instance Segmentation and Tracking with Cosine Embeddings and Recurrent Hourglass Networks},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Neff, Thomas and Bischof, Horst and Urschler, Martin},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention - {MICCAI} 2018},
  doi       = {10.1007/978-3-030-00934-2_1},
  pages     = {3--11},
  year      = {2018},
}
```

[Multi-label Whole Heart Segmentation Using CNNs and Anatomical Label Configurations](https://doi.org/10.1007/978-3-319-75541-0_20):

```
@inproceedings{Payer2018a,
  title     = {Multi-label Whole Heart Segmentation Using {CNNs} and Anatomical Label Configurations},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Statistical Atlases and Computational Models of the Heart. ACDC and MMWHS Challenges. STACOM 2017},
  doi       = {10.1007/978-3-319-75541-0_20},
  pages     = {190--198},
  year      = {2018},
}
```

[Regressing Heatmaps for Multiple Landmark Localization Using CNNs](https://doi.org/10.1007/978-3-319-75541-0_20):

```
@inproceedings{Payer2016,
  title     = {Regressing Heatmaps for Multiple Landmark Localization Using {CNNs}},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention - {MICCAI} 2016},
  doi       = {10.1007/978-3-319-46723-8_27},
  pages     = {230--238},
  year      = {2016},
}
```
