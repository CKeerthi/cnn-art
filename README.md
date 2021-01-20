# cnn-tensorflow-art

## Motivation
There are many research papers on this idea, I came across one that stuck to the basics and explained it throughly: https://openaccess.thecvf.com/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html

## Tools
I used tensorflow and Keras VGG-19 deep neural network to acomplish this. Primarily being that the Keras API available for tensorflow 2.0 make it really easy to implement funtions. 

## Improving Performance
The device I ran doesn't have a dedicated GPU so I could only run a 100 iterations. If you have a dedicated GPU, go ahead and run for a 1000 iterations to really get the combination of the style and content of the 2 images. You could also experiement and choose other optimizers, I played safe for now and stuck with Adam's optimizer(using Keras API).

## Output
The output folder has the final picture and the image at the end of each batch of iteration

