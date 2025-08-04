# Naturalistic Human Behavioral States (Rest vs. Active) Prediction using Machine Learning

Project Name: "Decoding Naturalistic Human Behavioral States (Rest vs. Active) from Neural Data"

Megapod: van

Pod: quetzalcoatl

Motivation: Neuroscience is a field of study that examines the structure and function of the human brain and nervous system. The field of neuroscience is growing at an exponential rate thanks to the new advances in imaging technology.

Abstract: 
While prior studies have advanced our understanding of the relationship between neural activity and naturalistic human movement, much of this research has focused on constrained, repetitive actions in highly controlled laboratory environments. Consequently, these findings often fail to generalize to complex, naturalistic behaviors encountered in everyday life, such as spontaneous arm-reaching movements (Steven et al., 2022). Emerging evidence suggests that neural activity in the beta frequency band (13–30 Hz) reflects the brain’s readiness state, modulating between rest and movement initiation (Seokyun et al., 2014; Preeya et al., 2024).

Building on this insight, the present study investigates whether naturalistic human behavioral states (specifically rest vs. active states), can be predicted from electrocorticography (ECoG) signals. I hypothesize that naturalistic behavioral activity is encoded in ECoG patterns, and that predictive models leveraging frequency band features will yield statistically significant performance. To test this hypothesis, I utilize the Annotated Joints in Long-Term Electrocorticography for 12 Human Participants (AJILE12) dataset, which includes long-term neural recordings, upper body pose trajectories, and relevant metadata from 12 individuals.

The analysis pipeline involves initial data exploration and visualization, followed by the construction of an input–output matrix comprising neural features (X) and a binary outcome vector (y), where the labels indicate 'Rest' or 'Active' states. A random forest model was trained and evaluated using common classification metrics, including accuracy, precision, recall, F1-score, and a confusion matrix.

Findings from this project underscore the potential of decoding naturalistic behavior from neural signals and suggest real-world applications in enhancing human wellbeing.

Dataset Name: Annotated Joints In Long-Term Electrocortiraphy for 12 Human Participants (AJLIE12)

Dataset Information: 
- https://www.bingbrunton.com/ajile-readme

Colab Notebook:
- https://drive.google.com/file/d/1vgrkX204gZPWoe_S_xDgF_E2a4zOcyAw/view?usp=sharing

Project Presentation:
- https://docs.google.com/presentation/d/1pflveRivBqAMBIECl9RTvInUjpLYvs0Afz-x0-ui2aM/edit?usp=sharing


