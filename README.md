# udacity-aipnd-project1
Udacity AI Programming with Python Nanodegree Project 1 repo.  Image classifier using Pytorch, to identify dog breeds.

Use run_models_batch.sh to call the actual python code, which is in check_images.py.
```
# PROGRAMMER: Perry Brandiezs
# DATE CREATED: December 22, 2018                    
# REVISED DATE: December 29, 2018
# PURPOSE: Classifies pet images using a pretrained CNN model, compares these
#          classifications to the true identity of the pets in the images, and
#          summarizes how well the CNN performed on the image classification task. 
#          Note that the true identity of the pet (or object) in the image is 
#          indicated by the filename of the image. Therefore, your program must
#          first extract the pet image label from the filename before
#          classifying the images using the pretrained CNN model. With this 
#          program we will be comparing the performance of 3 different CNN model
#          architectures to determine which provides the 'best' classification.
#
# Use argparse Expected Call with <> indicating expected user input:
#      python check_images.py --dir <directory with images> --arch <model>
#             --dogfile <file that contains dognames>
#   Example call:
#    python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
##
```
