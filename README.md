ABSTRACT

Acoustic components for the audio classification is an important topic in the field of deep learning because it helps to perceive the sounds from the environment. Several literature models rely on signals time structure, generated frames and learned features which are not fully defined ie MFCC and LPCC, we cannot just rely on these features due to the complicated and variable nature of the environment sounds. In this paper, we propose an end to end approach for environmental sound classification based on a Convolution Neural Network~(CNN) model that learns a general and robust representation of four expressive (extracted) features from the audio signals that are relevant for classification task by maintaining the quality of the audio signal. Our approach can deal with any length and type of audio signals. We evaluated our model using different configurations by considering several input combinations of four features (\ie MFCC, CENS, SC, and SN) and found out that they help significantly as compared to the handcrafted features or simple 2D representations(input). We demonstrate the performance of our proposed approach on two UrbanSound8k and TUT Urban Acoustic Scenes 2018 Development datasets. Furthermore, the proposed approach has a small number of parameters as compared to literature architectures, which reduces the amount of time or data required for training.