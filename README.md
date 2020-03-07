## Face-Generator

### Using GAN to generate human faces (Tensorflow).

Please read my [blog](https://medium.com/@shivajbd/generating-human-faces-using-adversarial-network-960863bc1deb) to get a detailed insight for this project.

### Introduction

In this project, I am generating human faces which probably does not exist in real life. I will be using the generative adversarial network(GAN) for the task. I am using CelebA dataset for training the network. This dataset contains 2,00,000 images of well-known people.

### Results

Following are the generated faces after training.

<img src=result/img.png>

We can generate more realistic images by making our network deeper, but it will take a lot of time to train the model. We can also modify our network to produce high-resolution images but again at the cost of training time.
