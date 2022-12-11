# ViSpEr
# Visual Speech and Emotion Recognition (ViSpEr)

## Abstract:

Hearing loss affects around 466 million people globally. Students who are deaf or hard of hearing rely on lip reading to grasp what is being said. 
Hearing challenged students confront a number of problems, including a lack of skilled sign language facilitators and the expensive cost of assistive technology.
Visual speech recognition (also known as lip reading) is considered to be one of the most futuristic applications. In the case of an image sequence of a person speaking a word, a complete image analysis system would segment the mouth area, extract important features, and utilize them to identify the word based on those visual features. Visual speech recognition gives machines the ability to interpret languages in noisy environments, and it can also be used for biometric authentication and enhanced hearing aids. Lip-reading is the task of decoding text from the movement of a speaker’s mouth. Traditional approaches separated the problem into two stages: designing or learning visual features, and prediction. Most existing methods equate VSR with automatic lip-reading, which analyses lip motion to attempt to recognise speech. However, human experience and psychological studies reveal that during a face-to-face conversation, we do not always fix our gaze on each other's lips, but instead scan the entire face repeatedly. When analysing human expressions from multimodal forms such as texts, physiology, audio or video, the accuracy of emotion recognition is frequently increased. The combination of information from facial expressions, bodily movement 
and gestures and voice allows different emotion types to be recognised. The technology is considered to have aided in the development of the emotional Internet. 

We designed and trained an integrated visual speech and emotion recognition system consisting of a video processing pipeline that maps raw video to stable videos of lips and sequences of phonemes, and a scalable deep neural network that maps the lip videos to words. The proposed system for visual speech recognition achieves an accuracy of 91.34% as measured on a test set. Facial emotion recognition model gives a satisfactory performance of 63.17% on the test set. In the dataset we used, our method outperforms certain other lip reading methods existing significantly.
<br>
## Visual Speech Recognition – MODEL PERFORMANCE:
![image](https://user-images.githubusercontent.com/66003584/206933881-60cf46dd-3613-4774-9c03-d9e311a8064a.png)
![image](https://user-images.githubusercontent.com/66003584/206933883-d5970778-0b86-42d8-a59b-f34dc7ada9ad.png)<br>
Model Accuracy & Loss for Visual Speech Recognition 
      Training Accuracy = 99.50 % <br>
      Validation Accuracy = 84.67 % <br>
      Testing Accuracy = 91.33 % <br>
<br>
### Classification Report for Visual Speech Recognition (Test Set):
![image](https://user-images.githubusercontent.com/66003584/206933934-8edd2391-3bdd-4dad-a66c-62941f5e8071.png)
<br>
### Confusion Matrix for Visual Speech Recognition (Test Set):
![image](https://user-images.githubusercontent.com/66003584/206933937-03543fcd-a8ae-440a-83a2-75296b424865.png=250x250)
<br>
## Demo:
![image](https://user-images.githubusercontent.com/66003584/206933789-97440b56-f783-42c5-89de-006fe50e1550.png)
<br>
![image](https://user-images.githubusercontent.com/66003584/206933797-9d4a7ce0-f18d-4f29-b360-d3154259e173.png)

## Results and Conclusion:

In this work we have successfully demonstrated the capability and feasibility of designing an end-to-end neural network for the low-resource visual speech and facial emotion recognition task using 3D CNNs and LSTMs. We were able to achieve a state-of-the-art accuracy of 91.34 % for visual speech with 10 recognizable classes and 63.17% for facial emotion recognition with 7 recognizable classes. We presented two level recognition pipelines for visual level and facial emotion recognition and tested our systems on real-word data of different scenarios.
The framework that has been developed is trained and tested on a limited amount of data for lip reading. The merging of visual and audio speech modalities, as well as speaker adaptation, will be the focus of future research. When compared to a single modality, we believe that fused multi-modal information will help to boost recognition performance even more. Another alternative option is to investigate various NN-based architectures in order to better tackle the end-to-end lip-reading task.
With mouth region picture inputs, we demonstrated that the CNN functions as a phoneme recognition technique. Our present results, on the other hand, were obtained by creating a separate CNN for each speaker. The volume and variety of training samples are crucial for maximising a DNN's generalisation capabilities, as previously addressed in earlier deep learning studies. A DNN (CNN) framework is scalable, but it necessitates a large enough training dataset to avoid overfitting. As a result, we must investigate the possibility of realising a VSR system applicable to multiple speakers with a single CNN model in future work by training and evaluating our current mechanism with a more diverse audio-visual speech dataset with large variations, especially for mouth region images. 
