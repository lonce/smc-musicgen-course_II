# Computational Music Creativity \- Part 1 Syllabus

The first part of the Computational Music Creativity course focuses on exploring, implementing, and critically evaluating symbolic music generation techniques, including both traditional approaches and deep learning-based methods.

# Learning Objectives

* Understand the theoretical foundations and principles of symbolic generative music techniques, including Markov chains, cellular automata, genetic algorithms, RNNs/LSTMs, and transformers.  
* Analyze the strengths and limitations of both traditional and machine-learning-based symbolic generative music techniques in terms of creativity, coherence, and practical application.  
* Code generative music systems from scratch, demonstrating the ability to translate theoretical concepts into functional implementations.  
* Connect theory to practice by exploring how generative music techniques are applied in research, industry, and artistic projects, and discussing real-world challenges and hurdles in the field.  
* Combine, adapt, and implement generative techniques to design symbolic music systems tailored to specific creative tasks and musical objectives.  
* Recreate and implement generative systems described in research papers.  
* Run inference and fine-tune pre-trained symbolic models by leveraging the Hugging Face Transformers library for generative music tasks.  
* Leverage cloud platforms like AWS, GCP, or Azure to run generative music models on remote servers with GPU acceleration for scalable and efficient computation.  
* Discuss the skills, knowledge, and steps required to become a generative music AI engineer.

# Pre-requisites 

* Students are expected to have intermediate proficiency in Python programming.  
* A basic understanding of linear algebra (e.g., matrices, vectors, and matrix operations) will be helpful for classes focusing on deep learning concepts.  
* A basic knowledge of TensorFlow/Keras will be helpful for deep learning techniques.  
* **Before each class, students should watch the assigned video lectures from The Sound of AI Generative Music AI Course, covering both theory and implementation.** The specific videos for each class are listed below.   

# Classes

## Class 1: Course Introduction

When: January 8th at 17:00-18:00h (online).

What: 

* Introduction to the course, its structure, philosophy, and evaluation.  
* Discussion about the history of generative music, ethical aspects, music representation, and generative techniques.

Before taking this class, students are expected to have watched the following videos from The Sound of AI’s *Generative Music AI Course*:

1. [What's Generative Music?](https://www.youtube.com/watch?v=9QNG56fc_l8&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=2)  
2. [History of Generative Music](https://www.youtube.com/watch?v=3znKoIUrgDI&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=3)  
3. [Use Cases](https://www.youtube.com/watch?v=Fg3TGfbEL64&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=4)  
4. [Ethical Implications](https://www.youtube.com/watch?v=DCaE5776Rqg&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=5)  
5. [Symbolic Vs Audio Generation](https://www.youtube.com/watch?v=VYxcHHJNTR0&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=6)  
6. [Generative Techniques](https://www.youtube.com/watch?v=W-_eWSrQ_vU&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=7)  
7. [Limitations and Future Vision](https://www.youtube.com/watch?v=viR9q61wV4Q&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=8)

## Class 2: Genetic Algorithms

When: January 13th at 16:00-17:10h (in presence).

What: 

* Genetic algorithms for music generation.  
* Real-world experience / challenges implementing this technique.  
* Discuss GenJam system.  
* Exercises and practical challenges.

Before taking this class, students are expected to have watched the following videos and coded along the code walkthrough from The Sound of AI’s *Generative Music AI Course:*

1. Genetic Algorithms \[[video](https://www.youtube.com/watch?v=CAVy7OZ87mE&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=15)\] \[[slides](https://github.com/musikalkemist/generativemusicaicourse/blob/main/15.%20Genetic%20algorithms/Slides/15.%20Genetic%20algorithms.pdf)\]  
2. Melody Harmonization with Genetic Algorithms \[[video](https://www.youtube.com/watch?v=AmtLrd-cYSY&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=16)\] \[[code](https://github.com/musikalkemist/generativemusicaicourse/blob/main/16.%20Melody%20harmonization%20with%20genetic%20algorithms/Code/geneticmelodyharmonizer.py)\]

## Class 3: Markov Chains

When: January 13th at 17:20-18:30h (in presence).

What: 

* Markov chains models for music generation.  
* Real-world experience / challenges implementing this technique.  
* Discuss GEDMAS system.  
* Exercises and practical challenges.

Before taking this class, students are expected to have watched the following videos and coded along the code walkthrough from The Sound of AI’s *Generative Music AI Course:*

1. Markov Chains \[[video](https://www.youtube.com/watch?v=gn-_ocUaGYo&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=11)\] \[[slides](https://github.com/musikalkemist/generativemusicaicourse/blob/main/11.%20Markov%20chains/Slides/11.%20Markov%20chains.pdf)\]  
2. Melody Generation with Markov Chains \[[video](https://www.youtube.com/watch?v=V7OPB6zmSdM&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=12)\] \[[code](https://github.com/musikalkemist/generativemusicaicourse/blob/main/12.%20Melody%20generation%20with%20Markov%20chains/Code/markovchain.py)\]

## Class 4: RNN/LSTMs

When: January 14th at 16:00-18:30h (in presence).

What: 

* RNN/LSTMs for music generation.  
* Real-world experience / challenges implementing this technique.  
* Discuss BachBot system.  
* Exercises and practical challenges.

Before taking this class, students are expected to have watched the following videos and coded along the code walkthroughs from The Sound of AI YouTube channel*:*

1. Recurrent Neural Networks Explained Easily \[[video](https://www.youtube.com/watch?v=DY82Goknf0s)\] \[[slides](https://github.com/musikalkemist/DeepLearningForAudioWithPython/tree/master/17-%20Recurrent%20Neural%20Networks%20explained%20easily/slides)\]  
2. Long Short Term Memory (LSTM) Networks Explained Easily \[[video](https://www.youtube.com/watch?v=eCvz-kB4yko)\] \[[slides](https://github.com/musikalkemist/DeepLearningForAudioWithPython/tree/master/18-%20LSTM%20networks%20explained%20easily/slides)\]  
3. *Generating Melodies with LSTM Nets Course*:  
   1. [Video lectures (theory \+ implementation)](https://www.youtube.com/watch?v=FLr0r-QhqH0&list=PL-wATfeyAMNr0KMutwtbeDCmpwvtul-Xz)  
   2. [Code \+ slides](https://github.com/musikalkemist/generating-melodies-with-rnn-lstm/tree/master)

## Class 5: Transformers

When: January 15th at 16:00-18:30h (in presence).

What: 

* Transformers for music generation.  
* Real-world experience / challenges implementing this technique.  
* Focus on Music Transformer.  
* Exercises and practical challenges.

Before taking this class, students are expected to have watched the following videos and coded along the code walkthrough from The Sound of AI’s *Generative Music AI Course:*

1. Transformers Explained Easily: Part 1 \[[video](https://www.youtube.com/watch?v=FtXT-AFzSvg&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=17)\] \[[slides](https://github.com/musikalkemist/generativemusicaicourse/blob/main/17.%20Transformers%20-%20Part%201/Slides/17.%20Transformers%20-%20Part%201.pdf)\]  
2. Transformers Explained Easily: Part 2 \[[video](https://www.youtube.com/watch?v=ctbvMnbylsA&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=18)\] \[[slides](https://github.com/musikalkemist/generativemusicaicourse/blob/main/18.%20Transformers%20-%20Part%202/Slides/18.%20Transformers%20Part%202.pdf)\]  
3. Melody Generation with Transformers \[[video](https://www.youtube.com/watch?v=j4LABY2d7k4&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D&index=19)\] \[[code](https://github.com/musikalkemist/generativemusicaicourse/tree/main/19.%20Melody%20generation%20with%20transformers/Code)\]

## Class 6: Transformers Hack Session

When: January 21st (or 23rd) at time TBD for 1:30h (in presence).

What: 

* Inference \+ Fine Tuning with Hugging Face Transformers.  
* Using pre-trained symbolic models  (no details, only what they do, as a user rather than a "researcher").  
* On one of the cloud providers \- AWS, Azure, GCP.

Before taking this class, students are expected to have installed the following libraries and coded along the code walkthrough:

1. Set up an account on cloud computing platforms \[AWS/GCP/Azure (TBD)\]  
2. Hugging Face Transformers \[[blog](https://huggingface.co/docs/transformers/en/quicktour)\]  
3. Hugging Face MuPT \[[blog](https://huggingface.co/m-a-p/MuPT-v1-8192-190M)\]

## Class 7: Assignments Review

When: January 27th at 16:00-18:30h (online).

What: 

* Discuss four code assignments.  
* Check solutions together.

## Class 8: Paper Implementation

When: January 28th at 16:30-18:30h (online).

What: 

* How to implement a generative AI music paper.  
* Check paper implementation together. 

## Class 9: Creative Reverse Engineering \+ Wrap-up

When: January 29th at 16:30-18:30h (online).

What: 

* Reverse engineer the output of a generative music system.  
* During the class, in groups of three people, design a generative music system that can come up with the presented music output.  
* Reflect on Part 1 of the course, ask questions, tips to get a job as a gen AI music engineer. 

# Teaching Approach

The course will cover both the theoretical and implementation aspects of symbolic generative music systems. 

The course main teaching principles are: 

* learning by doing,  
* fostering proactivity and independent learning.

Students are expected to study the theory and basic implementation of the techniques independently by watching The Sound of AI's Generative Music AI Course and its corresponding implementations.

Theory classes will focus on advanced aspects of the techniques, building on the video lectures. These sessions will emphasize real-world applications, presenting one industry or academic system that leverages the technique being studied. The classes will be interactive, with activities designed to encourage problem-solving and critical thinking.

Practical classes will center on code implementation of the assignments. Students’ solutions will be reviewed and discussed in detail. Additionally, students will be tasked with reverse-engineering a generative music system, applying the knowledge and skills acquired throughout the course.

# Tools and Programming Languages

Part 1 of the course will use Python. All coding assignments should be coded in Python 3.10. The deep learning implementation will be done in TensorFlow/Keras.

# Assignments

## Pre-class quizzes

Students will be required to submit a quiz on the current technology before each class. The quizzes will test their understanding of the concepts discussed in the assigned pre-class videos. There will be four quizzes, covering Markov Chains, Genetic Algorithms, RNN/LSTMs, and Transformers.

## Coding Assignments

There will be four coding assignments—one for each technique introduced in the course. Coding assignments will be done in groups of two people.

These assignments will require students to implement variations or extensions of the techniques they have learned to address a specific musical challenge (e.g., melody generation).

## Paper Implementation

This will involve implementing a generative music research paper from scratch, applying the concepts and skills gained throughout the course. Paper implementation will be done in groups of two people.

## Deliverables

The deliverable for the code assignments and paper implementation is a link to a GitHub repository containing the implementation code. 

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

* The pre-class quizzes are due as follows:  
  * Markov Chains quiz: January 12th at midnight  
  * Genetic Algorithms quiz: January 12th at midnight  
  * RNN/LSTM quiz: January 13th at midnight  
  * Transformer quiz: January 14th at midnight  
* The four code assignments are due by January 26th at midnight.  
* The paper implementation is due by January 27th at midnight.  
* The final project is due by \[insert date\] at midnight.

# Evaluation

Evaluation for the Computational Music Creativity course will be as follows:

* Part 1 (Valerio): 30% of the overall score.  
* Part 2 (Lonce): 30% of the overall score.  
* Final Project: 40% of the overall score.

## Part 1 Evaluation

* Pre-class Quizzes (20% of Part 1 score):  
  Four quizzes, each contributing equally.  
* Coding Assignments and Paper Implementation (80% of Part 1 score):  
  These will be graded on a “pass” or “fail” basis, with each assignment contributing equally to this portion.

## Final Project Evaluation (Part 1\)

If a student chooses to complete the Final Project associated with Part 1 (accounting for 40% of the overall course score), their work will be graded on a scale of 1 to 10 based on the following criteria:

1. Soundness of the implementation  
2. Cleanliness of the implementation (e.g., [clean code](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29))  
3. Degree of innovation in the system  
4. Clarity of the presentation  
5. Quality of the creative output

# Office Hours

Students can book 20-minute slots (individually or in groups) with Dr. Valerio Velardo via this Calendly page, during the following times:

* January 17th, 18:30–20:30  
* January 22nd, 18:30–20:30  
* February 13th, 18:30–20:30  
* March 6th, 18:30–20:30

# Learning Material

## Required

### Generative Music AI Theory \+ Implementation

* The Sound of AI’s *Generative Music AI Course*:  
  * [Video lectures (theory \+ implementations)](https://www.youtube.com/watch?v=NpJWprrqlFw&list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D)  
  * [Code \+ slides](https://github.com/musikalkemist/generativemusicaicourse/tree/main)  
* Theory behind RNNs/LSTMs as covered in the following videos of the *Deep Learning (for Audio) with Python*:  
  * [Recurrent Neural Networks Explained Easily](https://www.youtube.com/watch?v=DY82Goknf0s)  
  * [Long Short Term Memory (LSTM) Networks Explained Easily](https://www.youtube.com/watch?v=eCvz-kB4yko)  
* The Sound of AI’s *Generating Melodies with LSTM Nets Course*:  
  * [Video lectures (theory \+ implementation)](https://www.youtube.com/watch?v=FLr0r-QhqH0&list=PL-wATfeyAMNr0KMutwtbeDCmpwvtul-Xz)  
  * [Code \+ slides](https://github.com/musikalkemist/generating-melodies-with-rnn-lstm/tree/master)

### Generative Music AI Papers

* [The Generative Electronic Dance Music Algorithmic System (GEDMAS)](https://www.academia.edu/101959323/The_Generative_Electronic_Dance_Music_Algorithmic_System_GEDMAS_)  
* [On the evolution of music in a society of self-taught digital creatures](https://www.researchgate.net/publication/228609658_On_the_evolution_of_music_in_a_society_of_self-taught_digital_creatures)  
* [GenJam: Evolution of a Jazz Improviser](https://www.researchgate.net/profile/John-Biles-2/publication/262370988_GenJam_evolution_of_a_jazz_improviser/links/54dedf3b0cf2966637880809/GenJam-evolution-of-a-jazz-improviser.pdf)  
* Automatic Stylistic Composition of Bach Chorales with Deep LSTM (aka BachBot) \[[presentation](https://www.youtube.com/watch?v=yu3DZuxxV7c)\] \[[paper](https://archives.ismir.net/ismir2017/paper/000156.pdf)\]  
* Music Transformer: Generating Music with Long-Term Structure \[[blog](https://magenta.tensorflow.org/music-transformer)\] \[[paper](https://arxiv.org/pdf/1809.04281)\]

### Symbolic Music Representation Formats

* \[TODO\] Course Doc and implementation for MIDI and abc notation   
* Basic MIDI tokenizations such as [MIDI-Like](https://miditok.readthedocs.io/en/latest/tokenizations.html#midi-like) from MIDITok

## Optional (but suggested, for real\!)

### Deep Learning

* The Sound of AI’s *Deep Learning (for Audio) with Python*:  
  * [Video lectures (theory \+ implementation)](https://www.youtube.com/watch?v=fMqL5vckiU0&list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf)  
  * [Code \+ slides](https://github.com/musikalkemist/DeepLearningForAudioWithPython/tree/master)

### Clean Code

* The Sound of AI’s  *Uncle Bob’ SOLID Principles for Machine Learning Engineers Course:*  
  * [Video lectures (theory \+ implementation)](https://www.youtube.com/watch?v=ul8LLiFY0Dw&list=PL-wATfeyAMNpZ6-ESiXK9BnZmGLjqECt9)  
  * [Code \+ slides](https://github.com/musikalkemist/solidforml/tree/main/solidforml)  
* [Clean Code in Python \- Second Edition: Develop maintainable and efficient code](https://www.amazon.es/Clean-Code-Python-maintainable-efficient/dp/1800560214)
