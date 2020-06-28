---
layout: post
comments: true
title: Learning OpenCV 3 Application Development
---

I am excited to announce that my first book - "Learning OpenCV 3 Application Development" is now available for pre-order on Packt Publishers' [website](https://www.packtpub.com/application-development/learning-opencv-3-application-development) as well as [Amazon](https://www.amazon.in/Learning-OpenCV-Samyak-Datta-ebook/dp/B01IF8J2CK)!

<div style="text-align:center">
	<img style="padding:10px;" src="/image/learning_opencv3_cover.jpg" alt="Learning OpenCV 3 - Cover" width="300" height="400">
</div>

Over the last few years, Computer Vision (and AI, in general) seems to have taken the world by storm! We are in the midst of self-driving cars, our smartphone apps somehow seem to already know the content of our photos and they even seggregate them into albums on the basis of that! This is indeed a great time to be alive! But where does someone who wants to start out with the absolute basics go? *Learning OpenCV 3 Application Development* is meant to serve as a gentle introduction into the world of Image Processing (IP), Computer Vision (CV) and Machine Learning (ML) using my favorite combination of OpenCV and C++. 

OpenCV recently came out with its 3.x version which changed the landscape by a significant measure. There has been a non-trivial amount of modifications to the ML module (among other small changes). Also, SIFT and SURF have been moved to the `opencv_contrib` repository. This has rendered a lot of the current literature on this topic obsolete. The book is based on the latest, and the currently most popular (as of August 2016) version - 3.1. The best part about the book is that it doesn't assume any prior IP/CV/ML knowledge. If you have a basic, working knowledge of C++ and a proclivity to explore, you are good to go! This makes it ideal for students, professionals or inter-disciplinary researchers who want to enter into the exciting world of "Visual Learning" and need a good place to build their foundations.

The book starts off with the absolute basics - pixels, color spaces and channels and by the end of the ~250 page journey, you would be writing algorithms that perform some fairly sophisticated visual analysis such as predicting the gender of a person by looking at the image of his/her face! Here is a very brief, chapter-wise gist of what you can expect.

+ **Chapter 1** : Image Processing Basics, fundamental OpenCV data structures (Mat, Point, Scalar etc) and your first, "Hello World program". Pixel-wise traversal of images through the Mat object, implementation of image enhancement algorithms as a practical use-case of pixel-wise image traversals.

+ **Chapter 2** : Introduction to slightly more challenging form of image enhancement techniques, the concept of image filters and convolution. First contact with the all-important and ubiquitous Gaussian distribution, image smoothing (using Box and Gausian filters). We also implement a cool image enhancement hack that is found in apps such as Instagram!

+ **Chapter 3** : Image thresholding ad the concept of binary images. We also discuss some common morphological operations such as erosion and dilation which are performed as post-processing step after thresholding algorithms.

+ **Chapter 4** : From working at a per-pixel level, we move to the concept of aggregating pixel values into histograms. This chapter discusses how to build histograms from grayscale as well as RGB images and also some cool stuff you can do with them.

+ **Chapter 5** : Moving upwards from pixel-based transformations, we now enter the domain of what is called - "mid-level vision". We discuss the concept of image derivatives and see how derivatives can help us in detecting edges in images.

+ **Chapter 6** : This is one of the most exciting chapters in the book where we get to witness OpenCV's true power as it compresses fairly complicated algorithms for a difficult task such as face detection into a single line of API code! You would learn to appreciate the fact that tasks which are trivial for human beings (such as detecting and recognizing faces), often involve a fair amount of number crunching and processing for computers. In fact, this is a theme that would be reinforced throughout the remaining parts of the book.

+ **Chapter 7** : Having detected faces, we now look at some affine Transformations and their applications in pre-processing the face images. We essentially make the faces ready for the subsequent feature extraction steps.

+ **Chapter 8** : Image descriptors - tools for converting images from a matrix of pixel intensities to a vector of real-values features. Specifically, we discuss and implement local binary pattern (LBP) features.

+ **Chapter 9** : Machine Learning with OpenCV - supervised and unsupervised learning, kMeans, kNN, SVMs, overfitting, validation and PR curves. We demonstrate how to apply the feature vectors from Chapter 8 to the ML algorithms discussed here and build a facial gender detection system.

The book is more than a simple collection of chapters. It contains tips, tricks and other nuggets of information that I have picked up over the years as a result of my experiences with the library. Scattered across the text, you will find useful information that I wish somebody had told me when I had started out. I have tried to strike a balance between exposition of the subject matter, code samples that demonstrate the theory in action and a chronicle of a few "good practices" sampled from my own experiences. It is due to these reasons that the project is quite close to my heart. As of August 2016, I have been working on the first draft since the last 3 months. My tryst with OpenCV began in my final year in college while I was working towards my Masters thesis. The book, I believe, is my way of giving back to the wonderful community!

Since this is my very first book, some mistakes may have inadvertently crept in. Please feel free to shoot an email in case you notice any error(s). Constructive criticism is always welcome. Happy reading!

