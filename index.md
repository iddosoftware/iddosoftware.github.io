---
layout: default
---

#### About Us
Iddo Software is currently comprised of Bogdan Budescu, Ștefan Ghivirigă and Dorian Stoica. We're, basically, three guys in a basement office writing computer vision and deep learning code for startups that need our skills to build their apps.

#### What we do
As I've stated above, we're (mostly) writing code. Many computer vision and machine learning apps share common functionality, so we strongly incentivize our clients (through substantial discounts to our own hourly rates) to allow us to reuse the code we write for them. This way, we don't write the same stuff over and over again (which leads to boredom and depression), and our clients get their code faster and cheaper.

We also have a network of other machine learning and computer vision engineers which we might be able to get on board if necessary, and other developers that can help us out with things like DevOps, web dev, mobile dev, sys admin and others.

#### What we want
We want to grow. We have a strong predilection towards stability and, hence, we value long term commitments from our clients. Reciprocally, we offer long term commitments to our clients in return. As such, we usually prefer, e.g., hiring new developers for new clients as opposed to switching devs from one customer to the next. We also like to put our money where our mouth is, so we generally offer a significant discount for long-term contracts with the clients we already have a good history with.

#### What we've done
As you can see, we don't have a proper portfolio web page yet, since we've been pretty busy doing what we do best for our clients, namely writing computer vision and deep learning code. We're actually working on the portfolio, but it's not ready yet. However, in the mean time, you can get a grip of what we've done until now by taking a look at our LinkedIn profiles. [Here](https://www.linkedin.com/in/bbudescu/) is Bogdan's, [here](https://www.linkedin.com/in/stefan-ghiviriga-93818913a/) is Ștefan's, and [here](https://www.linkedin.com/in/dorian-stoica-97716b112) is Dorian's.

#### What we can do
As you can find out if you browse our profiles, we're experienced with projects involving:
- mapping objects in images to their positions in the real world
- classifying, locating, segmenting and recognizing objects in images, mostly (but not only) using neural nets
- designing, training and deploying neural nets for the above purposes, and some others, too (e.g., improving video quality)

We're also used to having to read a lot (research). This way we've been able to tackle a large variety of projects, as you can see in our CVs.

**Note:** at some point, Bogdan took the time to write everything he could remember having used, in terms of tech, on his personal blog. It's a lengthy (and rather boring) read, but if you want you can access it [here](https://bbudescu.github.io/tech_specs/).

#### How we do what we do
We work closely with our clients throughout every stage of the process of making their ideas happen:
- understanding the business goals / processes
- identifying stages in the pipeline which might benefit from using a CV/ML approach
- researching the state of the art in the relevant field
- estimate the relative cost, time to market and expected performance of alternatives we find (or think of)
- solution design, implementation, testing, deployment and maintenance.

#### What we use
Over time, we've used several technologies (programming languages, libraries, frameworks etc.) to build the stuff we've built, and, in the process, we've grown more or less accustomed to some of them:
- Computer Vision: `OpenCV` (from both `Python` and `C++`), `mahotas`, `scikit-image`, `scipy.ndimage`
- Deep Learning: `TensorFlow` (`Python` for training & inference, `C` and `Java` for inference only), `Keras`, `HyperOpt`, `scikit-learn`, `Caffe` (`C++`, `Python`), `Theano`, `pylearn2` (really old framework)
- deployment: `Docker`, `OpenAPI`, `pipenv`
- generic data processing: `NumPy`
- statistics: `pandas`, `scipy.stats`, `statsmodels`
- data visualization: `matplotlib` (+`mpld3`), `seaborn`, `plotly`
- GUI: `Qt` for `Python` (`PyQt5`, `PyQt4`, `PySide`)

#### What we have

Currently we have a few NVidia GPUs at our disposal for training and deploying neural nets.

We also have some code that we wrote for our clients in the past, for which we have kept the right to re-sell to further clients. That code may be used for:
- training and applying neural nets:
   - (bounding box) detectors using TensorFlow's Object Detection API
   - keypoint detectors
   - object segmentation
- deploying TensorFlow nets using Python, C (so not necessarily C++) and Java
- deploying nets training and inference services easily and in a scalable fashion using docker
- generate http endpoints for our deployed inference services quickly and easily using OpenAPI
- quickly feeding data to the training process of neural nets defined in keras
- detecting paper documents on flat surfaces
- green screen removal (keying)
- accurately estimate the position of objects relative to the camera given a few recognized points which respect some constraints known _a priori_
- other stuff I can't remember now, but probably will, if a problem arises that can be solved using that code
