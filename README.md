# Object detection using Mask-RCNN using google colab.
Google Colab has access to free GPU. If you have a problem installing Cuda/cudnn google colab is the best option to work on a deep learning project.

1st- Change notebook setting to GPU
 Edit > Notebook setting > Hardware accelerator--> GPU

2nd- install cython and clone the colab with coco repository in git by using 
`!git clone https://github.com/waleedka/coco`

and Mask RCNN
`!git clone https://github.com/matterport/Mask_RCNN`

3rd-Install required packages and configure coco dataset

4th- set 1 image at a time in GPU

5th- List class name in dataset

6th- Visualize the image in the data set 

![image](https://user-images.githubusercontent.com/42100536/56345768-2bfac700-61de-11e9-8886-2ef87a95337f.png)

# How to upload and visualize  user input test image in google colab 

1st- Select Image from the folder
2nd- Upload in [imgbb](https://imgbb.com/)
3rd- Get the link from imgbb.
4th- paste it with !wget and -P./images
code- `!wget https://image.ibb.co/k62krp/London.jpg -P ./images`
Test Image: 

![London](https://user-images.githubusercontent.com/42100536/56346041-d96dda80-61de-11e9-955e-ada46bd4ac2b.jpg)

Output Image:

![image](https://user-images.githubusercontent.com/42100536/56346084-f3a7b880-61de-11e9-9051-9bd9aabf9c24.png)

Similarly:
This image is from the mobile camera....

![image](https://user-images.githubusercontent.com/42100536/56346155-1df97600-61df-11e9-8f47-a4c459146cce.png)


Stay Tuned!




