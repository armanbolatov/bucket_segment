# Semantic Segmentation of Excavator Buckets

This repository contains an example of semantic segmentation of excavator bucket teeth using the [`keras-segmentation`](https://github.com/divamgupta/image-segmentation-keras) library.

In order to run this notebook, you need to put it inside this [folder with dataset](https://disk.yandex.com/d/2Y5Xq_45jbQjww).

## Project structure

    .
    ├───checkpoints             # checkpoints of the model
    ├───dataset
    │   ├───imgs                # training dataset images
    │   ├───masks               # training dataset masks
    │   └───new_masks           # transformed masks
    ├───test
    │   ├───imgs                # images for testing dataset
    │   ├───masks               # testing dataset masks
    │   └───new_masks           # detransformed masks
    ├───buckets.ipynb           # main .ipynb code file
    ├───.gitignore              # git ignore source file
    └───README.md
