# Siamese_Network
Siamese network using Tensorflow 

# Siamese network concept

A Siamese neural network (sometimes called a twin neural network) is an artificial neural network that uses the same weights while working in tandem on two different input vectors to compute comparable output vectors. Often one of the output vectors is precomputed, thus forming a baseline against which the other output vector is compared. This is similar to comparing fingerprints but can be described more technically as a distance function for locality-sensitive hashing.
It is possible to build an architecture that is functionally similar to a siamese network but implements a slightly different function. This is typically used for comparing similar instances in different type sets. Uses of similarity measures where a twin network might be used are such things as recognizing handwritten checks, automatic detection of faces in camera images, and matching queries with indexed documents. The perhaps most well-known application of twin networks are face recognition, where known images of people are precomputed and compared to an image from a turnstile or similar. It is not obvious at first, but there are two slightly different problems. One is recognizing a person among a large number of other persons, that is the facial recognition problem. DeepFace is an example of such a system. In its most extreme form this is recognizing a single person at a train station or airport. The other is face verification, that is to verify whether the photo in a pass is the same as the person claiming he or she is the same person. The twin network might be the same, but the implementation can be quite different.

## Objectives

1- Building a siamese network to measure the similarity between The fashion mnist dataset categories.

2- Modifying the data set to fit the problem.

3- Building customized Loss function.
