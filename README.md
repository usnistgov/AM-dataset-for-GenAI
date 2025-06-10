# GenAI-AM-Bench

GenAI-AM-Bench is a dataset developed to evaluate Generative Artificial Intelligence (GenAI) models on various tasks related to Metal Additive Manufacturing (MAM). It includes detecting defects in melt pool images, identifying porosity labels, answering true/false queries, solving multiple-choice questions, and responding to free-form questions. 

# Dataset Overview
### 1. Melt pool image with labels
- **Anomaly Detection**: Includes melt pool labeled images for identification defective and non-defective image based on features inlcuding melt pool area and intensity of the image.
![Printed Parts](Picture1.png)
Figure: Melt pool image (a) and (b) non-defective and (c) and (d) defective 

### 2. X-CT image with labels
- **Porosity Label**: Includes X-CT labeled image for identification large porosity data and small porosity data.
![Printed Parts](Picture2.png)
Figure: Melt pool image with label (a) and (b) small porosity and (c) and (d) large porsity

### 2. Free-Form Questions
- **Form**: Questions are open ended qustions. 
- **Sample**: What is the differnce between AMF and STL file?
### 3. Multiple-choice questions (MCQs)
- **Form**:  Provide two choice of each question
- **Ground Truths**: Answer keys are included to assess model accuracy.
### 4. True/False Questions
- **Form**:  Provide a statement
- **Ground Truths**: Answer  should be true or false  that are included to assess model accuracy.

### 4. Prompts
- **Prompts**: Includes prompts for each type of task
