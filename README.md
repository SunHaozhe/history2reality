# history2reality

## Description

Author: Haozhe Sun

Dataset for conversion between historical portraits and contemporary portraits. It has been used to reproduce photo-realistic portraits based on portrait paintings in the framework of [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).

The majority of the data are collected from Google Image Search. The collecting pipeline mainly consists of 4 stages: choosing a list of key words to search, web image scraping, automatic image filtering based on format, manual image filtering based on content. Some of the key words used are old fashioned portrait painting, historical portrait painting, historical portrait, Chinese historical portrait, 18th Historical period drama. The manual image filtering is done one by one by hand to ensure the quality of the dataset. 

The dataset, named history2reality, counts 1294 images in total as the criterion is relatively strict, historical portrait collection consists of 614 training images and 9 test images, realistic portrait collection consists of 662 training images and 9 test images. 1057 out of these 1294 images are collected from Google Image Search, however 237 images are taken from Helen dataset [1](http://www.ifp.illinois.edu/~vuongle2/helen/). These 237 images are picked randomly with probability 0.1 from the whole collection of Helen dataset.

## Citation

If you use this dataset for your research, please cite the following.

@misc{history2reality,
  author = {Haozhe Sun},
  title = {history2reality: Dataset for conversion between historical portraits and contemporary portraits.},
  howpublished = {https://github.com/SunHaozhe/history2reality}
}


## References

[1](http://www.ifp.illinois.edu/~vuongle2/helen/) V. Le, J. Brandt, Z. Lin, L. Bourdev, and T. S. Huang. Interactive facial feature localization. In Proceedings of the 12th European Conference on Computer Vision - Volume Part III, ECCV’12, pages 679–692, Berlin, Heidelberg, 2012.
Springer-Verlag.
