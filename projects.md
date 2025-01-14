---
layout: page
title: Projects
permalink: /projects/
---
This is my portfolio of significant research projects. Feel free to reach out to me with any questions or comments. 

# Research at Northeastern University
As an AI Master's student at Khoury College of Computer Sciences, my work can be segregated into 3 sub-research groups

### Bau Lab (Generative AI Researcher)
1. Erasing Concepts from Diffusion Models: In this work, we aim to erase artistic styles, copyrighted images and harmful content from the diffusion model weights using their own knowledge. Given just the text of the concept to be erased, our method can edit the model weights to erase the concept while minimizing the inteference with other concepts. This type of fine-tuning has an advantage over previous methods: it is not easy to circumvent because it modifies weights, yet it is fast and practical because it avoids the expense of retraining the whole model on filtered training data. [[Project Website]](https://erasing.baulab.info)
2. Collaboration to work on Lighting editing using Diffusion models. This work is collaboration with the amazing team at Signify research. We aim to explore the applications of diffusion models in relighting the scenes.

### AISkunkWorks@NEU (Volunteer Research Student Club)
1. Best Practices to implement DC-GAN (Deep Convolutional Generative Adversarial Networks). This work primarily focuses on various challenges that come with training a DC-GAN for procedural content generation. The work also concentrates on training tricks and architectural recommendations for an efficient model on a personal laptop. The research paper and code can be found [here](https://github.com/aiskunks/AI_Research/tree/main/dc-gan-best-practices)
2. Implementation of Progressively Growing GAN in keras. This work maily attempts to implement progressively growing GAN architectural training. This work is an extension to DC-GANs as it follows the path of best practices to train a GAN effectively. The project is open-sourced [here](https://github.com/aiskunks/AI_Research/tree/main/growing-gan-best-practices)

3. Denoising Diffusion Model architecure with Markov Additive Noise Process. This work is the state-of-the-art implementation of denoising model in PyTorch. Our work has generated hyper-realisitic fake images of animals and human faces. The results can be found [here](https://github.com/aiskunks/AI_Research/tree/main/diffusion-model-best-practices)

4. Deep Reinforcement Learning with Double Deep-Q Networks for function approximation to learn Atari Games (Space Invaders). This work uses openAI gym library for game environment and keras for deep architectures. The code repository can be found [here](https://github.com/RohitGandikota/Deep-Reinforcement-Learning-with-Double-Q-Networks-on-Atari-Games)

### AI for Health (Research Scientist)
1. Prediction of efficacy and Overall survivability of drugs using state-of-the-art data interpretation models. This work is being carried out remotely for Northeastern Seattle Campus. 


# Research at Indian Space Research Organization
As a scientist at National Remote Sensing Center, ISRO, my primary research interest includes deep learning, image processing, data analysis, and natural language processing.
### Deep Learning
1. RTC-GAN: A novel generative adversarial network design for infusing spectral information into the spatial features for real-time semantic LULC segmentation of satellite data [[**Published at IEEE International Geoscience and Remote Sensing Symposium (IGARSS'20)**]](https://ieeexplore.ieee.org/document/9323363)  <br />
Summary: This project aims to design a novel GAN architecture for the real-time classification of satellite images.   <br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

2. DisMon-GAN: A 24x7, all-weather disaster monitoring tool for assisting ministries and rescue teams by providing seamless synthesized optical images from the information collected by microwave SAR data. [[**Under Review at IEEE International Geoscience and Remote Sensing Symposium (IGARSS'22)**]](https://www.igarss2022.org/)<br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

3. Satellite images to Map layer translation using conditional GAN with Patch-GAN discriminator. This work automatically generates crisp map layer with both higher and lower frequency features from satellite images. [[**Source Code**]](https://github.com/RohitGandikota/Satellite-Images-to-Map-Layer-Translation-Using-Conditional-Patch-GAN)<br />
Technology Used: Python, Keras, Scipy, PIL

4. Land Use Land Cover Classification of Satellite Images using Deep Learning: This work discusses how high-resolution satellite images are classified into various classes like cloud, vegetation, water, and miscellaneous, using a feed-forward neural network. [[**Source Code**]](https://github.com/RohitGandikota/Land-Use-Land-Cover-Classification-of-Satellite-Images-using-Deep-Learning) <br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

5. Thematic layer generation from Sentinel Images using M2TGAN: In this work, we generate the thematic maps from satellite images. Here, we generate water bodies thematic and use both traditional Autoencoder and a Generative Adversarial Network (M2TGAN). [[**Source Code**]](https://github.com/RohitGandikota/Satellite-Images-to-thematic-maps-using-Generative-Adversarial-Networks)<br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

### Image Processing
1. Automatic Satellite Quality Data Evaluation Algorithms: Automatic Image Quality Analysis (AIQA) has become a crucial module in the remote sensing industry. With increasing competition and institutions that provide remote sensing images, the quality of images provided to the users has a huge impact. This work provides advanced quality parameters like noise density, histogram statistics, radiometry, geometry, and LULC thematic information. [[**Sample Source Code**]](https://github.com/RohitGandikota/Automatic-Image-Quality-Analysis) <br />
Technology Used: Python, Scipy, Sci-kit, Numba, PIL, GDAL, RasterIO

2. A Novel Approach for Pixel Dropouts Localization: Commonly known as salt and pepper noise in the image processing terminology, pixel dropouts can be detected with many existing algorithms that usually tend to detect edges as noise falsely. A novel 2-stage algorithm has been designed to detect salt and pepper noise in raw satellite imagery to overcome this common problem. [[**Under Review at IEEE International Geoscience and Remote Sensing Symposium (IGARSS'22)**]](https://www.igarss2022.org/)<br />
Technology Used: Python, Sci-kit, Numba, Scipy, PIL, GDAL, RasterIO

### Data Analysis
1. Data Mining of ISRO's production history and analyzing the data for identifying gaps to improve efficiency. I formulated an optimization problem to improve production efficiency by considering dynamic resource allocation problems in a stochastic environment.  A 2.4 folds improvement in production time was observed. <br />
Tools used: Python, Seaborn, Plotly, Matplotlib, Pandas, Oracle. 

2. Analysis and Visualization of radiometry parameters automatically calculated for ~2000 images(512GB) per day to assess the quality and monitor the products delivered to users. <br />
Tools used: Python, Seaborn, Plotly, Matplotlib, Pandas, Postgres. 

### Natural Language Processing 
1. NLP solutions for automatic satellite ordering using voice search commands for [ISRO's open data website, Bhoondihi](https://bhoonidhi.nrsc.gov.in/bhoonidhi/index.html) and provided an [API package for the same on PyPI](https://pypi.org/project/bhoonidhi/) [[**Source Code**]](https://github.com/RohitGandikota/NLP-based-Smart-Search-for-Satellite-Data-Ordering)

2. Developing speech recognition extension for satellite-specific lingo. We are using open-sourced pre-trained LSTM networks to fine-tune satellite data-specific jargon. 

3. API for bhoonidhi, ISRO's open data dissemination portal. [[**Source Code**]](https://github.com/RohitGandikota/BhoonidhiAPI)

# Research at Indian Institute of Space Science and Technology
This is where my passion for machine learning was shaped into research. My work here mainly focused on the fundamental understanding of deep learning architectures, their computer vision applications (data hiding, image detection, autonomous vehicle vision, and face recognition), and a little bit of text processing and NLP. I will divide my research into a summer internship, course projects, final year thesis, and AIML club projects.

### Summer Internship
1. Understanding and developing Q-value-based Reinforcement learning algorithms. Developing a deep-reinforcement learning network for image detection.<br />
Technology Used: Python, Keras, PIL, openCV<br />

2. Understanding Convolutional Neural Networks through a novel approach. The input pixels responsible for classification are identified by back-tracking the activations of neurons at each layer. [[**Published at IEEE Region 10 International Conference (TENCON'19)**]](https://ieeexplore.ieee.org/document/8929603)  <br />
Technology Used: Python, Tensorflow, Keras, Matplotlib, Numba<br />

### Course Projects
1. Developing image processing algorithms for autonomous vehicle vision systems. This work focuses on developing basic image processing algorithms and fine-tuning them for usage in vision systems. [[**Report published in Arxiv**]](https://arxiv.org/abs/1812.02542)<br />
Technology Used: Python, OpenCV, PIL, Sci-kit, Numpy<br />

2. Worked on infusing the InceptionNet concept in Res Modules. This work was on architectural design to see if inception module advantages can help Res modules bottlenecks. <br />
Technology Used: Python, Tensorflow<br />

3. Comprehensive Study on WiFi protocols such as IEEE 802.11ac, 802.11ad, and 802.11ax and summarize a few of the works that discuss the abovementioned protocol standards of WiFi that brought a significant improvement in WiFi's performance. [[**Report published in Arxiv**]](https://arxiv.org/abs/1811.09391)<br />

4. Worked on job-shop scheduling optimization protocols and developed a scheduling protocol for the xv6 operating system.<br />

### Final Year Thesis
1. Designed VoI-GAN, the first end-to-end trainable model of Generative Adversarial Networks (GAN) engineered to hide audio data in images [[**Published at Springer's International Conference on Pattern Recognition and Machine Intelligence (PReMI'19)**]](https://link.springer.com/chapter/10.1007/978-3-030-34872-4_43) [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Audio-in-Images-using-Deep-Generative-Network-with-Adversarial-Training) <br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

2. Introduced the first models to hide video data inside images that can also be recognized as compression techniques: Vid-in-Img-3D-GAN and Vid-in-Img-RAN using 3D CNNs and bi-directional LSTMs [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Video-in-Images-using-Deep-Generative-Adversarial-Networks)<br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

3. Designed WM-GAN for watermarking images using GAN and VAE architectures [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Images-using-VAE-Genarative-Adversarial-Networks)<br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

### AIML Club
1. Built a device with Intel's Neural Compute Stick and a camera module, using the Siamese network for one-shot learning to perform automatic facial recognition to mark students' attendance inside classrooms.<br />
Technology Used: Python, Keras, Tensorflow, PIL, Intel Openvino<br />

2. Extended computer vision work on autonomous vehicles for IIST's mail delivery robot.<br />
Technology Used: Python, OpenCV, PIL<br />

3. Developed NLP solutions for campus enquiry chatbot. <br />
Technology Used: Python, NLTK, Numpy<br />
