# Challenges, evaluation and opportunities for open-world learning

* OWL: Weak/Semi-Strong/Strong, should be antifragile and robust
* OWL and GenAI have a symbiotic relationship

## Weak OWL

* Detect environmental changes such as anomaly detection and changepoint detection

| Paradigm                             | Definition                                                   | Related methods                                              | Applications and use-cases                                   |
| :----------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| **Metalearning**(元学习)             | Learning to learn, to make learning progress faster with more experience ‘via the acquisition of inductive biases or knowledge that allows for more efficient learning in the future’ | Lifelong learning, metacognitive methods , brain-inspired global-local learning, hierarchical memory in deep reinforcement learning | Hand-task recognition; cognitive and neuroscientific applications; complex gameplaying, strategic adaptation and agent modelling |
| **Anomaly detection**(异常检测)      | Finding patterns in data that do not conform to expected behavior | Out-of-distribution detection, changepoint detection, concept drift | Detection of frauds and cyberattacks; abnormal class detection in computer vision; military surveillance for enemy activities; detecting statistical shifts |
| **Multitask learning**(多任务学习)   | Inductive transfer that improves generalization by using the domain information contained in the training signals of related tasks as an inductive bias | Parallel transfer in neural networks, multi-label learning, transfer learning, multi-output regression | Health informatics and bioinformatics; time-series prediction; robotics; autonomous vehicles and driving |
| **Few-shot learning**(少样本学习)    | Rapidly generalize to new tasks containing only a few samples with supervised information | Zero-shot learning, learning with fewer labels, open-set recognition, one-shot learning, open-world recognition, classification with reject option | Image captioning; handwriting recognition; object tracking; robotics applications such as continuous control, multi-armed bandits and one-shot imitation; cold-start item recommendation; acoustic signal processing |
| **Test-time adaptation**(测试时适应) | Generalize to new and different data during testing given only its parameters and the target data | Online and incremental learning, entropy minimization, test-time normalization, feature modulation | Computer vision applications, such as reducing generalization error on corrupted images, source-free domain adaptation and semantic segmentation |

* Classification: Active/Passive
* Active: State models, policy learning, not independent and identically distributed(i.i.d.) 

## Semi-Strong OWL

* Describe or characterize the environmental change to predict tis properties with some specificity

## Strong OWL

* Adapt to environmental changes in real time <mark>generalized adaptation capabilities</mark>
* Challenge: Lifelong learning -> self-paced, OWL -> adapting to change asap

![image-20250702193312482](OWL.png)

## Robust OWL VS Antifragile OWL

* Antifragile gets better while robust stays the same, antifragile is best suited to strong OWL, can also be applied to others.

## Evaluating OWL

* Evaluation Firewall

## Perspective

* Continuous Deployment Evaluation
* OWL-compatible Engineering
* Anomaly detection, changepoint analysis, AMOC(at most one change) -> weak OWL, lifelong learning -> strong OWL
* Research priority: develop a standardized repository of benchmarks and metrics modelled