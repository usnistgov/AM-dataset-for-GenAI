<!-- # GenAI-AM-Bench

GenAI-AM-Bench is a dataset developed to evaluate Generative Artificial Intelligence (GenAI) models on various tasks related to Metal Additive Manufacturing (MAM). It includes detecting defects in melt pool images, identifying porosity labels, answering true/false queries, solving multiple-choice questions, and responding to free-form questions. 

# Dataset Overview
### 1. Melt Pool Image with Labels
- **Anomaly Detection**: Includes melt pool labeled images for identification defective and non-defective image based on features inlcuding melt pool area and intensity of the image.
![Printed Parts](Picture1.png)
Figure: Melt pool image (a) and (b) non-defective and (c) and (d) defective 

### 2. X-CT Image with Labels
- **Porosity Label**: Includes X-CT labeled image for identification large and small porosity data.
![Printed Parts](Picture2.png)
Figure: X-CT image (a) and (b) small porosity and (c) and (d) large porsity

### 2. Free-Form Questions
- **Form**: Questions are open ended qustions. 
- **Sample**: What is the differnce between AMF and STL file?
### 3. Multiple-choice questions (MCQs)
- **Form**:  Provide two choice of each question
- **Ground Truth**: Answer keys are included to assess model accuracy.
### 4. True/False Questions
- **Form**:  Provide a statement
- **Ground Truth**: Answer  should be true or false  that are included to assess model accuracy.

### 5. Prompts
- **Prompts**: Includes prompts for each type of task -->
# GenAI-AM-Bench

**GenAI-AM-Bench** is a dataset designed to evaluate **Generative Artificial Intelligence (GenAI)** models on a diverse set of tasks related to **Metal Additive Manufacturing (MAM)**.
It provides a comprehensive benchmark covering both visual and language-based reasoning tasks in the MAM domain.

The dataset includes:

* Defect detection in melt pool images
* Porosity identification from X-CT images
* True/False questions
* Multiple-choice questions (MCQs)
* Free-form question answering
* Structured prompts for consistent evaluation

---

# Dataset Overview

## 1. Melt Pool Image with Labels

**Task**: Anomaly Detection
**Description**: Labeled melt pool images for identifying *defective* vs. *non-defective* samples based on features such as melt pool area and image intensity.

**Example**:

![Melt Pool Images](Picture1.png)
**Figure**: Melt pool images — (a) and (b) non-defective; (c) and (d) defective

---

## 2. X-CT Image with Labels

**Task**: Porosity Classification
**Description**: Labeled X-CT images for identifying *large* vs. *small* porosity regions.

**Example**:

![X-CT Images](Picture2.png)
**Figure**: X-CT images — (a) and (b) small porosity; (c) and (d) large porosity

---

## 3. Free-Form Questions

**Task**: Open-ended Question Answering
**Description**: Questions that require generative responses in free text.

**Example**:

```markdown
Q: What is the difference between AMF and STL file formats?
```

---

## 4. Multiple-Choice Questions (MCQs)

**Task**: Multiple-Choice Question Answering
**Description**: Questions with **two answer choices** provided.
**Ground Truth**: Answer keys included for accuracy evaluation.

**Example**:

```markdown
Q: What type of laser is commonly used in metal powder bed fusion?  
A) CO2 Laser  
B) Fiber Laser
```

---

## 5. True/False Questions

**Task**: True/False Classification
**Description**: Statements for binary classification.
**Ground Truth**: Correct labels (True/False) are provided.

**Example**:

```markdown
Statement: Stainless steel 316L is commonly used in metal additive manufacturing.  
Answer: True
```

---

## 6. Prompts

**Task**: Prompted Evaluation
**Description**: Includes carefully designed prompts for each task type to ensure consistency across GenAI model evaluations.

---

# Citation

If you use **GenAI-AM-Bench** in your work, please cite the corresponding paper (TBD).

# License

TBD
