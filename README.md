# common-eider-ml-pipeline


![Alt Text](https://github.com/lindsayveazey/common-eider-ml-pipeline/blob/main/150620AA_clip.gif?raw=true)

We are building a custom machine learning pipeline to accelerate imagery processing for avian researchers.

Our pipeline is **in development**. Read on for a brief overview of our methodology.


### Step 1: Generate a representative sample
We are using command line scripts and transfer learning via [EcoAssist](https://addaxdatascience.com/ecoassist/) to generate a sample of training data that broadly represents conditions present in our data set.

### Step 2: Data annotation
We are using [LabelStudio](https://labelstud.io), an open source data labeling platform, to annotate our species of interest.

![Alt Text](https://github.com/lindsayveazey/common-eider-ml-pipeline/blob/main/label-studio-example.png?raw=true)

### Step 3: Training the YOLO v7 model architecture (in progress)
We are training a custom You Only Look Once (YOLO) v7 object detection model to automatically detect and classify our species of interest. This model will be robust in confidently tracking animals in inclement weather, lighting, or crowded conditions.

### Step 4: Behavioral classification 
*More coming soon...*