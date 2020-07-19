# Face Generation with Generative Adversarial Neural Networks



! [Imgur](https://i.imgur.com/OrSV9by.png)

We define and train a DCGAN on a dataset of faces. We get a generator network to generate new images of faces that look as realistic as possible!

The project is broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, we are able to visualize the results of the trained Generator and see how it performs; our generated samples look like fairly realistic faces with small amounts of noise.
# Face Generation with Generative Adversarial Neural Networks
This projectwas developed under the udacity deep learning degree. We define and train a DCGAN on a dataset of faces. We get a generator network to generate new images of faces that look as realistic as possible!
\
\
\
![Imgur](https://i.imgur.com/OrSV9by.png)

\
\
The project is broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, we are able to visualize the results of the trained Generator and see how it performs; our generated samples look like fairly realistic faces with small amounts of noise.

## Dataset

We use the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks. However, some pre-procesing steps were previously done. Each of the CelebA images were cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images. You can download the dataset by [by clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)


### Details (from the dataset documentation)

*CelebFaces Attributes Dataset (CelebA) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including*
- *10,177 number of identities,*
- *202,599 number of face images, and*
- *5 landmark locations, 40 binary attributes annotations per image.*
*The dataset can be employed as the training and test sets for the following computer vision tasks: face attribute recognition, face detection, landmark (or facial part) localization, and face editing & synthesis.*


# Results

After trainning for 50 epochs we achieve a discriminator loss of 0.1972 and a generator loss of 4.0759. 
\
\
![Imgur](https://i.imgur.com/vHLnMl0.png)
\
\
The resulting faces are quite realistic:
\
\
![Imgur](https://i.imgur.com/YP7oNPA.png)


