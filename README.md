# ADiveIntoMindfulness
The repository provides basic components useful in order to analyze the movements and the breaths of an user in order to infer high level predictions about the movements (horizontal and vertical shifts + view rotations) exploitable 

## Installation and Execution
To install the necessary requirements, follow these steps:

1. Clone the repository.
2. Run the following command:
```bash
cd ADiveIntoMindfulness && pip install -r requirements.txt
```

It's possible to run the notebook on own data by:
- copying the desired breath-related audio files into the folder "RespiratoryFeatureResources"
- overwriting the video "video.mov" with an own one in the folder "GestureFeatureResources" (or, alternatively, by setting the variable "use_webcam" to True if the use of the webcam is desired)