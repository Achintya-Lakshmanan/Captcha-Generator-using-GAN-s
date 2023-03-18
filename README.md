# Captcha-Generator-using-GAN-s
A captcha image generator using GAN's

## Generator for Numbers Training GIF
![](generator_images_num.gif)


## Generator for Alphabets Training GIF
![](generator_images_char.gif)

NOTE: Both were trained for 500 epochs, with a BCE loss function and Adam optimizer.

## Final Generated Image for Both
![](/outputs_mnist/test.png)    ![](/outputs_emnist/test.png)

## Generated Captcha Images
![](/generated_captcha/captcha_0.png) ![](/generated_captcha/captcha_1.png) ![](/generated_captcha/captcha_2.png) ![](/generated_captcha/captcha_3.png)
![](/generated_captcha/captcha_4.png) ![](/generated_captcha/captcha_5.png) ![](/generated_captcha/captcha_6.png) ![](/generated_captcha/captcha_7.png)
![](/generated_captcha/captcha_8.png) ![](/generated_captcha/captcha_9.png)

## To Run
1) Clone git repo.
2) Data is downloaded automatically from pytorch.
3) Make sure to change paths as necessary.
4) Run MNIST.ipynb to train GAN on MNIST and last 3 cells to generate image.
5) Similarly do the same with EMNIST.ipynb for alphabets.
6) Finally run Captcha_Generator.ipynb which generates 10 images in generated_captcha folder.

# To Do
1) Find better NN's for the GAN mainly for Alphabets.
2) Make model to get orientation of generated characters correct (wherever wrong).
3) Find way to get answer of generated captcha.
4) Make interface to evaluate input answer.
