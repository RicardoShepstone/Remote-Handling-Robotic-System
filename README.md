# Remote-Handling-Robotic-System

Abstract:

In this work, we present the implementation of a system based on convo-
lutional neural networks (CNN) for the localization and pose estimation of
objects from RGB images, applicable in real environments for robotic gras-
ping, considering the specific conditions of the IFMIF-DONES project. A
comprehensive study of state-of-the-art architectures was conducted to se-
lect the most suitable topology for this task, as well as a review of commonly
used datasets and metrics, for performance evaluation and comparison.
We developed a methodology that leverages simulation environments to
generate randomized synthetic RGB images and ground truth data using
CAD models provided by the IFMIF-DONES RH laboratory. These envi-
ronments facilitated the generation of a significant amount of training data,
reducing the reliance on hard to obtain real-world data in early stages. The
system was deployed and integrated with other technologies in a real sce-
nario, where it was employed for real-world data collection and processing
images of a physical 3D-printed mockup derived from one of the CAD mo-
dels.
The system’s performance was evaluated using standard pose estimation
metrics, using alternative technologies for comparison, such as the Vicon
motion capture system. The model demonstrated difficulties transitioning
to real scenario, especially for the low definition camera used to simulate
the poor image quality provided by rad-hard cameras. Additionally, impro-
vements were made to the model based on data collected in the real-world
laboratory setup, achieving satisfactory results and performance improve-
ments in the real scenario.
We analyzed the effects of radiation on camera sensors and the resulting
noise in the images, examining its impact on model accuracy. This analysis
introduced the concept of predictive maintenance, identifying the noise levels
at which the model’s performance significantly deteriorates, offering insights
into when the system may require intervention.
Lastly, a successful robotic grasping test was carried out utilizing the
system’s implementation and tuned models, proving the usefulness of this
technology for robotic grasping & handling tasks.

- TFM_RicardoShepstoneAramburu: This is the thesis report. It consists of a long document detailing the fundamentals of this proyect, the research methodology, the main carried out experiments and the obtained results, with an extensive analysis and commentary.
