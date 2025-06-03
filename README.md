# Finding Feral Hogs
This project is a Computer Vision (CV) capstone project for the Deloitte AI Academy (formerly Deloitte AI Guild), completed in June 2023.

The Deloitte AI Academy is a training entity within Deloitte that upskills employees with machine learning expertise via hands-on experience. In my case, I had no prior machine learning experience at the start of the development of this capstone project. The completion of this capstone project was preceded by six months of data science, python, and machine learning training within the Deloitte AI Academy.

This was my first attempt at creating a functioning CV project and was done before beginning a Masters in Computer Science from Southern Methodist University.

## Background
This project is a binary image classification CV project that uses hunting trail camera (wildlife camera trap) images of white-tailed deer and feral hogs to label each individual image with the correct species name.

This project was created with the intention of exploring the possibility of integrating such a CV model into commercially available trail cameras so as to allow hunters to be alerted when their deployed cameras capture images of a specific target species (i.e., only deer). At the time of finishing this project, no commercially available trail cameras had this kind of AI-enabled functionality.

## Datasets Used
1. Training, Validation, & Initial Testing:

   Missouri Camera Traps dataset from the [Labeled Information Library of Alexandria](https://lila.science/datasets/missouricameratraps)

2. Final Testing:

   Personal images from my own trail cameras on a hunting property in Delta County, Texas.

## Technology Used
- TensorFlow
- Google Colab
- OpenCV (cv2)

## Lessons Learned
- Basic end-to-end machine learning pipeline (the _how_ of creating a functional CV pipeline)
- Experience gained in use of TensorFlow and OpenCV (first exposure to both)
- Understanding the need for preprocessing and feature extraction before model training (edge detection, surface texture - especially for juvenile wild hogs, bounding boxes, etc.)
- Importance of quality data for training - dataset used was comprised of dated trail camera images of poor quality
- Overcoming the problem of a bifurcated dataset - animal images were taken in both daytime sunlight and nighttime IR spectrum light
