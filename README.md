# watermark-removal
Removing watermarks from images using fastai and No-GAN approach

To use my weights, download all the rar files and extract the .pth file for gan weights. 
you will need to install fastai according to the tutorial on fastai's website.
 
Put the images from which you want to remove watermark into a folder, and create imageList from that folder. THen you can predict results from that ImageList. To see how to create ImageList check fastai tutorial.

To change what kind of watermarks are removed, 
1. change the crappify file to include your kind of watermark
2. Run watermark_removal with the crappify images you create.
3. Save results of watermark_removal, and train critic
4. Run GAN with critic and watermark_removal models. 
5. Do inference with trained generator of GAN


For more detailed tutorial, follow fastai's No-GAN approach or fastai lesson 7. 

This is a modified version of the project Jeremy Howard does in lesson 7 of fastai's lectures.

Code credits: Fastai lesson 7
