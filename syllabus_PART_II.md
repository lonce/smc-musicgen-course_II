---
layout: default
title: Syllabus for CMC Part II
---
# Computational Music Creativity \- Part 2 Syllabus: Generative Audio

The second part of the Computational Music Creativity course focuses on raw audio generation techniques using deep learning-based methods.

- [Computational Music Creativity - Part 2 Syllabus](#computational-music-creativity---part-2-syllabus)
- [Learning Objectives](#learning-objectives)
  - [Concepts](#concepts) 
  - [Architectures](#architectures) 
- [Pre-requisites](#pre-requisites)
- [Classes](#classes)
  - [Class 2.1: Course Introduction](#class-21-audio-modeling-introduction)
  - [Class 2.2: Representation](#class-22-representation)
  - [Class 2.3: Codecs](#class-23-codecs)
  - [Class 2.4: DDSP & Rave](#class-24-ddsp-and-rave)
  - [Class 2.5: Transformers for Audio](#class-25-transformers-for-audio)
- [Teaching Approach](#teaching-approach)
- [Tools and Programming Languages](#tools-and-programming-languages)
- [Assignments](#assignments)
  - [Pre-class quizzes](#pre-class-quizzes)
  - [Coding Assignments](#coding-assignments)
- [Final Project](#final-project)
- [Deadlines](#deadlines)
- [Evaluation](#evaluation)
- [Office Hours](#office-hours)
- [Communication](#communication)
- [Learning Material](#learning-material)


# Learning Objectives

* Develop an understanding of the deep learning techniques used for generative audio. 
* Develop/deepen your ability to read and understand research papers in the field. 
* Understand not just how to use, but how to build or change networks to achieve your goals.  


## Concepts 

* Other “subsymbolic” audio representations
​	frame-based
​	codecs
* Conditioning 
* Managing long time dependencies 
* Latent spaces for creative interaction
* Managing computational overhead
* Playability
​	Offline vs online / Composition vs performance / Text vs RT Interaction

## Architectures

* Convolutional (e.g. Wavenet)
* GAN (e.g. Sound Model Factory)
* VAE (e.g. Rave)
* DDSP (e.g. DDSP)
* Transformers (Vampnet)
​	(Building on Part 1)


# Pre-requisites 

* Students are expected to have intermediate proficiency in Python programming.  

* A basic understanding of linear algebra (e.g., matrices, vectors, and matrix operations) will be helpful for classes focusing on deep learning concepts.  

* A basic knowledge of **PyTorch** will be helpful for deep learning techniques.  

# Classes

## Class 2.1: Audio modeling Introduction

When: 
Monday February 3 at 16:30:00-18:00h (rm# 52.427).
Wednesday February 5 at 17:00-18:00h (rm# 52.329).


What: 

* Introduction to the second part of the course on generative audio.   
* Discussion about the main ideas, audio representations, and architectures commonly used.
* Sound Model Factory approach to creating playable audio models 

Class preparation :

1. Engel, J., Agrawal, K. K., Chen, S., Gulrajani, I., Donahue, C., & Roberts, A. **(2019**). **Gansynth**: Adversarial neural audio synthesis. *arXiv preprint arXiv:1902.08710*.  [[Link]](https://arxiv.org/abs/1902.08710)
1. Wyse, L., Kamath, P., & Gupta, C. (2022, April). Sound model factory: An integrated system architecture for generative audio modelling. In *International Conference on Computational Intelligence in Music, Sound, Art and Design (Part of EvoStar)* (pp. 308-322). Cham: Springer International Publishing. [[Link]](https://arxiv.org/abs/2206.13085)

## Class 2.2: Representation

When: 
Monday February 10 at 16:30:00-18:00h (rm# 52.427).
Wednesday February 12 at 17:00-18:00h (rm# 52.329).

## Class 2.3: Codecs

When: 
Monday February 17 at 16:30:00-18:00h (rm# 52.427).
Wednesday February 19 at 17:00-18:00h (rm# 52.329).

## Class 2.4: DDSP and Rave

When: 
Monday February 24 at 16:30:00-18:00h (rm# 52.427).
Wednesday February 26 at 17:00-18:00h (rm# 52.329).

## Class 2.5: Transformers for Audio

When: 
Monday March 3 at 16:30:00-18:00h (rm# 52.427).
Wednesday March 5 at 17:00-18:00h (rm# 52.329).


# Teaching Approach

The course will cover both the theoretical and implementation aspects of  generative audio systems. 

The course main teaching principles are: 

* Theory (reading and lecture),  
* "hands on" in-class challenges (mostly using Collab).

Students are expected to come to class prepared having read the paper assignments. 

# Tools and Programming Languages

Part 2 of the course will use Python and PyTorch. 

# Assignments

## Pre-class quizzes

Students will be required to submit a quiz on the current technology before each class. The quizzes will your understanding of the concepts discussed in the assigned reading.

# Final Project

Students can choose to create a Final Project for either Part 1 or Part 2 of the course. The Final Project for Part 1 will focus on symbolic generative music, while the Final Project for Part 2 will focus on audio-based generative music.

For those opting for a Final Project in Part 1, the task will be to design and implement a symbolic generative music system. This project should demonstrate the adaptation and/or combination of one or more techniques covered during the course.

The final project can be done alone, or in a group of up to three people.

The system will generate symbolic scores, which will be sent to Ableton for sonification. The objective is to create a semi-realtime generative application with a strong focus on creative value.

The final project deliverables are: 

1. A GitHub repository link containing the implementation code.  
2. A 5-minute YouTube video presentation explaining how the model works.  
3. A 5-minute video demonstration showcasing the model in action.

# Deadlines

* The pre-class quizzes would be available as follows:  
  * Markov Chains quiz: January 12th noon \- January 13th noon  
  * Genetic Algorithms quiz: January 12th noon \- January 13th noon  
  * RNN/LSTM quiz: January 13th noon \- January 14th noon  
  * Transformer quiz: January 14th noon \- January 15th noon  
* The four code assignments are due by January 26th at midnight.  
* The paper implementation is due by January 27th at midnight.  
* The final project is due by Sunday March 29th at midnight (no extensions are possible!).

# Evaluation

Evaluation for the Computational Music Creativity course will be as follows:

* Part 1 (Valerio): 30% of the overall score.  
* Part 2 (Lonce): 30% of the overall score.  
* Final Project: 40% of the overall score.

## Final Project Evaluation (Part 2)

If a student chooses to complete the Final Project associated with Part 1 (accounting for 40% of the overall course score), their work will be graded on a scale of 1 to 10 based on the following criteria:

1. Soundness of code implementation  
2. Cleanliness of the implementation (e.g., [clean code](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29))  
3. Degree of thoughtfulness and innovation in the system  
4. Clarity of the presentation  (writeup)
5. Quality of the creative output

# Office Hours

Students can book 20-minute slots (individually or in groups) with Lonce via a DM on our Slack channel (\#smc24-musicgen, @lonce wyse), or email: lonce.wyse@upf.edu. 

# Communication

For general questions, please use the dedicated Slack channel on the MTG workspace: \#smc24-musicgen. This channel will serve as a hub for asynchronous communication and updates for all students, so make sure to check it regularly. 

For individual questions, doubts, or ideas, feel free to send a direct message to Valerio Velardo and Anmol Mishra in the MTG Slack (@Valerio Velardo, @Anmol Mishra, @lonce wyse).

# Learning Material


## A few good papers on Generative Audio 

* Van Den Oord, A., Dieleman, S., Zen, H., Simonyan, K., Vinyals, O., Graves, A., ... & Kavukcuoglu, K. (**2016**). **Wavenet**: A generative model for raw audio. *arXiv preprint arXiv:1609.03499*, *12*.

* Kumar, K., Kumar, R., De Boissiere, T., Gestin, L., Teoh, W. Z., Sotelo, J., ... & Courville, A. C. (**2019**). **Melgan**: Generative adversarial networks for conditional waveform synthesis. *Advances in neural information processing systems*, *32*.
​		[keywords: Vocoder; Phase construction]

* Engel, J., Agrawal, K. K., Chen, S., Gulrajani, I., Donahue, C., & Roberts, A. **(2019**). **Gansynth**: Adversarial neural audio synthesis. *arXiv preprint arXiv:1902.08710*.
​		[keywords: conditional training]

* Engel, J., Hantrakul, L., Gu, C., & Roberts, A. (**2020**). **DDSP**: Differentiable digital signal processing. *arXiv preprint arXiv:2001.04643*.

  ​		[keywords: inductive bias, signal processing units, real time]

* Caillon, A., & Esling, P. (**2021**). **RAVE**: A variational autoencoder for fast and high-quality neural audio synthesis. *arXiv preprint arXiv:2111.05011*.
​		[keywords: conditional training]

* Huzaifah, M., & Wyse, L. (2021). Deep generative models for musical audio synthesis. *Handbook of artificial intelligence for music: foundations, advanced approaches, and developments for creativity*, 639-678.

  ​		[keywords: "review" paper]

* Wyse, L., Kamath, P., & Gupta, C. (2022, April). Sound model factory: An integrated system architecture for generative audio modelling. In *International Conference on Computational Intelligence in Music, Sound, Art and Design (Part of EvoStar)* (pp. 308-322). Cham: Springer International Publishing.
  ​		[keywords: playability; latent space]

* Garcia, H. F., Seetharaman, P., Kumar, R., & Pardo, B. (2023). Vampnet: Music generation via masked acoustic token modeling. *arXiv preprint arXiv:2307.04686*.
  
  ​		[keywords: transformer, in-painting, masking for training, codecs]
  
* Evans, Z., Parker, J. D., Carr, C. J., Zukowski, Z., Taylor, J., & Pons, J. (**2024**). **Stable audio open**. *arXiv preprint arXiv:2407.14358*.
  ​		[keywords: Text-2-audio; Open (data, weights, code, latent diffusion]

* Rafael Valle, Rohan Badlani, Zhifeng Kong, Sang-gil Lee, Arushi Goel, Sungwon Kim, Joao Felipe Santos, Shuqi Dai, Siddharth Gururani, Aya AlJa’fari, Alex Liu, Kevin Shih, ˜ Wei Ping, Bryan Catanzaro (**2024**). **Fugatto** 1 Foundational Generative Audio Transformer Opus 1
