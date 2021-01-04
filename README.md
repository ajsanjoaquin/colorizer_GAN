# colorizer_GAN w/ Lightning

This repository is primarily meant to showcase the features of Pytorch Lightning and how it can streamline three different training tasks. 
The training tasks in order are: </br>

1. Self-Supervized Training  of the Generator Backbone (Resnet 18) </br>
2. Supervized Training of the Generator </br>
3. GAN Training </br>


<img src="sample.jpg"> 
### GAN Colorizer from Scratch (No Pretrained weights used!)

You can train your own GAN Colorizer, or use the given weights to colorize your own images. The model that produced the images above was trained for a total of 70 epochs all within 3 hours. Most of the GAN architecture code and generator training implementation was adapted from [Moein's GAN Colorizer training](https://colab.research.google.com/github/moein-shariatnia/Deep-Learning/blob/main/Image%20Colorization%20Tutorial/Image%20Colorization%20with%20U-Net%20and%20GAN%20Tutorial.ipynb#scrollTo=S_b9HzPgYTpq). I also took most of the Self-Supervized dataset code from [Ian's Implementation of Self-Supervized Learning](https://snappishproductions.com/blog/2020/05/25/image-self-supervised-training-with-pytorch-lightning.html.html).
