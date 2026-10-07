<p align="center">
  <img src="assets/profile-banner.svg" width="100%" alt="Williams Ayivi, Ph.D. — Reliable, explainable, and efficient AI for medical imaging" />
</p>
<p align="center">
  <a href="mailto:williamsayivi@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-167D8D?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Research-Medical_AI-14384D?style=flat-square" alt="Medical AI research" />
  <img src="https://img.shields.io/badge/Location-Vienna,_Austria-14384D?style=flat-square" alt="Vienna, Austria" />
</p>
<p align="center">
  <a href="#featured-research">Research</a> &nbsp; / &nbsp;
  <a href="#technical-toolkit">Toolkit</a> &nbsp; / &nbsp;
  <a href="#selected-publications">Publications</a> &nbsp; / &nbsp;
  <a href="#research-and-professional-experience">Experience</a> &nbsp; / &nbsp;
  <a href="#education">Education</a>
</p>
---
Research with a practical purpose
I am an AI researcher with a Ph.D. in Information and Communication Engineering from the University of Electronic Science and Technology of China (UESTC). My research focuses on deep learning for biomedical image analysis, with particular interests in reliability, interpretability, lightweight architectures, and generalisation across heterogeneous imaging datasets.
My work spans medical image classification and segmentation, attention mechanisms, federated learning, and ultrasound image enhancement. I combine model development with ablation studies, class-wise evaluation, robustness analysis, and deployment-oriented assessment.
Alongside research, I work as an IT Manager at Viewpointsystem GmbH in Vienna, supporting enterprise systems, device management, and IT operations.
Research focus
Reliable medical AI · Explainable learning · Edge deployment  
Image classification & segmentation · Federated learning · Domain generalisation
Featured research
<table>
<tr>
<td width="50%" valign="top">
<h3>01 / LIVRA-Net</h3>
<p><strong>Efficient AI at the edge</strong></p>
<p>Ultra-lightweight attention with bounded, feature-space variance reweighting. The architecture is trained independently on MRI, CT, and X-ray.</p>
<p><code>Lightweight networks</code> <code>Robustness</code> <code>Edge AI</code></p>
</td>
<td width="50%" valign="top">
<h3>02 / Brain-EffNet</h3>
<p><strong>Interpretable brain tumour classification</strong></p>
<p>EfficientNetV2-S combined with texture and shape radiomics, with Grad-CAM++ visualisations for inspecting MRI predictions.</p>
<p><code>MRI</code> <code>Radiomics</code> <code>Explainability</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>03 / MedFeNet</h3>
<p><strong>Collaborative medical image segmentation</strong></p>
<p>Federated learning algorithms tailored to automated segmentation across different medical imaging modalities.</p>
<p><code>Federated learning</code> <code>Segmentation</code></p>
</td>
<td width="50%" valign="top">
<h3>04 / ST-AWT</h3>
<p><strong>Structure-aware ultrasound enhancement</strong></p>
<p>Structure tensor-guided wavelet thresholding, learned coherence refinement, and residual-preserving spatial fusion.</p>
<p><code>Ultrasound</code> <code>Wavelets</code> <code>U-Net</code></p>
</td>
</tr>
</table>
<details>
<summary><strong>Explore the methods and evaluation</strong></summary>
LIVRA-Net
A Native Ultra-Lightweight Variance-Reweighted Attention Architecture for Edge Medical Image Classification Across Independent Modalities
Uses separate learned projections for average- and max-pooled channel descriptors, followed by independent sigmoid activations and multiplicative fusion.
Introduces bounded, feature-space local variance-weighted sample reweighting to address intra-class heterogeneity.
Applies the same architecture and training template independently to MRI, CT, and X-ray, training from scratch and adapting the output head. These experiments assess structural generality across modalities; they do not imply multimodal fusion or weight transfer.
Includes repeated-run baseline comparisons, component ablations, exploratory statistical analysis, synthetic-corruption evaluation, and latency/power measurements on Raspberry Pi 4, smartphone CPU, and Edge TPU.
Tools: Python · PyTorch · Jupyter Notebook · Image preprocessing
Brain-EffNet
A Lightweight and Explainable EfficientNet Framework for Multi-Class Brain Tumour Classification from MRI Images
Combines EfficientNetV2-S with handcrafted texture and shape radiomic descriptors for MRI classification.
Integrates deep representations with domain-specific imaging features.
Uses Grad-CAM++ to visualise regions associated with model predictions and support inspection of model behaviour.
Tools: Python · PyTorch · Jupyter Notebook · Radiomic features · Grad-CAM++
MedFeNet
Medical Federated Learning Network
Develops federated learning methods tailored to automated medical image segmentation.
Applies the approach across different medical imaging modalities.
Tools: Python · PyTorch · Jupyter Notebook · Image preprocessing
ST-AWT
Structure Tensor-Guided Adaptive Wavelet Thresholding for Edge-Preserving Speckle Suppression in Ultrasound Imaging
Uses local structure tensor coherence to control the spatial strength of wavelet coefficient attenuation.
Restricts a U-Net learning branch to coherence refinement, retaining an interpretable signal-processing pathway.
Introduces residual-preserving spatial fusion through a learned mask to reduce suppression of weak tissue patterns.

</details>
Technical toolkit
Category	Technologies and methods
Programming	Python
Deep learning	PyTorch; model development, fine-tuning, hyperparameter optimisation, and deployment
Image processing and machine learning	OpenCV · scikit-learn
Data analysis and visualisation	Pandas · NumPy · Seaborn · Matplotlib · Excel
Architectures and methods	CNNs · RNNs · GANs · Graph neural networks · U-Net · Transformers · Autoencoders · Attention · Transfer learning · Multitask learning · Lightweight models
Research workflows	Jupyter Notebook · Data preprocessing · Data quality control · Basic statistical analysis · Ablation studies · Class-wise evaluation
Operating environments	UNIX/Linux command line · Windows
Enterprise IT	Microsoft 365 · Miradore MDM · Asset lifecycle management · User access administration
Additional familiarity: MONAI, FuseMedML, Flower, FSL, SPM, FreeSurfer, ANT, and BrainSuite. My CV lists these medical frameworks and imaging tools at a basic level of proficiency.
Selected publications
8 selected publications across medical imaging, biomedical signals, navigation, and economic modelling. Expand a year below to view the full citations.
<details>
<summary><strong>2026 — Medical imaging, efficient learning, and biomedical signals</strong></summary>
A compact and interpretable multi-source framework for heterogeneous medical image classification. Williams Ayivi, Xiaoling Zhang, Wisdom Xornam Ativi, Francis Sam, and Amil Aligayev. Scientific Reports, 2026.
Multisite T1-weighted MRI classification of Alzheimer’s disease using 3D-CNN-HSCAM architecture with contrastive domain adaptation. Francis Sam, Zhiguang Qin, Collins Sey, Joseph Roger Arhin, Daniel Addo, Linda Delali Fiasam, Williams Ayivi, and Gladys Wavinya Muoka. Biomedical Signal Processing and Control, 2026.
SLEA: a stochastic saccadic lightweight efficient attention framework with MobileNetV2 for robust and explainable 2D medical image classification. Williams Ayivi, Xiaoling Zhang, and Amil Aligayev. Physica Scripta, 2026.
Classification of Gesture Electromyography by Dynamic Mode Decomposition. Alberta Ashitey, Ayivi Williams, J. A. Toluwani, and R. Peng. IEEE Access, 2026.
CMAF-Net: cross-modal attention fusion with information-theoretic regularization for imbalanced breast cancer histopathology. Wisdom Xornam Ativi, Wenyu Chen, Lazarus Kwao, Williams Ayivi, Francis Sam, Ali Alqahtani, Yeong Hyeon Gu, and Mugahed A. Al-Antari. Scientific Reports, 2026.
</details>
<details>
<summary><strong>2025 — Lightweight lung cancer classification</strong></summary>
Dynamic–attentive pooling networks: A hybrid lightweight deep model for lung cancer classification. Williams Ayivi, Xiaoling Zhang, Wisdom Xornam Ativi, Francis Sam, and Franck A. P. Kouassi. Journal of Imaging, 2025.
</details>
<details>
<summary><strong>2022–2021 — Navigation and economic modelling</strong></summary>
RPNet: Rotational pooling net for efficient micro aerial vehicle trail navigation. Isaac Osei Agyemang, Xiaoling Zhang, Daniel Acheampong, Isaac Adjei-Mensah, Enoch Opanin Gyamfi, Joseph Roger Arhin, Williams Ayivi, and Chikwendu Ijeoma Amuche. Engineering Applications of Artificial Intelligence, 2022.
Quantitative dynamics effects of belt and road economies trade using structural gravity and neural networks. Koffi Dumor, Li Yao, Jean-Paul Ainam, Edem Koffi Amouzou, and Williams Ayivi. SAGE Open, 2021.
</details>
Research and professional experience
Ph.D. Graduate Researcher · UESTC, China
Radar Detection and Imaging Technology Lab | 2022–2026
Developed and evaluated machine learning models for high-dimensional biomedical imaging data, focusing on robust, interpretable, and reliable prediction.
Investigated class imbalance, dataset variation, and cross-domain generalisation.
Collaborated on multisite MRI classification using contrastive domain adaptation.
Evaluated model behaviour through statistical analysis, ablation studies, class-wise metrics, and interpretability methods.
Master’s Graduate Research Assistant · UESTC, China
Media Lab | 2020–2022
Developed an Attention U-Net architecture for glioblastoma multiforme segmentation.
Used BraTS 2020 and 2021 for tumour sub-region training and validation.
Implemented preprocessing pipelines incorporating bias field correction and skull stripping.
IT Manager · Viewpointsystem GmbH, Austria
Vienna | 2024–Present
Diagnose and resolve staff hardware, software, and network issues across Windows and Linux environments.
Manage IT assets, inventory, licensing, and access rights throughout the asset lifecycle.
Administer Microsoft 365 user provisioning and permissions.
Manage the device fleet using Miradore Mobile Device Management.
Coordinate employee IT onboarding, software installation, and offboarding.
<details>
<summary><strong>Teaching experience</strong></summary>
Teaching Assistant — Embedded Systems Design
UESTC | Fall 2022
Supported undergraduate teaching and laboratory sessions, supervised practical activities, assessed coursework, and provided academic feedback. Prepared resources and maintained laboratory materials, records, and equipment readiness.
Teaching Assistant — Cultural Difference and Cross-Culture Communication I
UESTC | Spring 2021
Supported graduate seminars on intercultural theory, global communication, and cross-cultural competence. Guided group work, presentations, and analytical reflections; assisted with assessment and teaching materials.
</details>
Education
All degrees were completed at the University of Electronic Science and Technology of China.
Qualification	Period	Academic record
Ph.D. in Information and Communication Engineering	September 2022–June 2026	GPA 3.86/4.0 · Rank 1
Master of Engineering in Information and Communication Engineering	September 2020–June 2022	GPA 3.92/4.0 · Rank 1
Bachelor of Business Administration	September 2016–June 2020	GPA 3.53/4.0
Doctoral dissertation: Analysis and Diagnosis of Biomedical Images Based on Deep Learning Techniques
Master’s thesis: Segmentation of Glioblastoma Multiforme Via Attention Neural Networks
Academic service
Editorial service: Scholar Council Member (Editor), ETERNO PRESS.
Peer reviewer for:
Biomedical Signal Processing and Control
Scientific Reports
Engineering Applications of Artificial Intelligence
Intelligence-Based Medicine
Neural Networks
BMC Medical Imaging
<details>
<summary><strong>Awards and honours</strong></summary>
Year	Award
2022–2026	Chinese Government Scholarship for doctoral study
2022	Certificate of Honour for Student Assistant service, Office of International Cooperation and Exchanges, School of Information and Communication Engineering; service period September 2020–February 2022
2021	Master’s Academic Achievement Award, Second Prize, UESTC, for the 2020–2021 academic year
2020–2022	Chinese University Scholarship for master’s study
</details>
<details>
<summary><strong>Leadership and community involvement</strong></summary>
Academic year	Position
2022–2023	Vice President for P.R.O. and Welfare, International Students’ Union, UESTC
2021–2022	Vice President for P.R.O. and Welfare, International Students’ Union, UESTC
2020–2021	Welfare Officer, International Students’ Union, UESTC
2019–2020	General Secretary, NUGS Chengdu Chapter, National Union of Ghana Students in China
2018–2019	General Secretary, NUGS Chengdu Chapter, National Union of Ghana Students in China
I value clear technical communication, cross-functional collaboration, analytical problem-solving, and community service, including helping new students settle into university life.
</details>
Beyond research
Languages: English · Chinese (HSK 4) · German (basic)
Interests: Hiking, volunteering, and reading scientific literature on AI, machine learning, business, and economics.
---
<div align="center">
Let’s connect
For research discussions and collaboration enquiries:
williamsayivi@gmail.com
</div>
<!-- Add verified Google Scholar, ORCID, GitHub, LinkedIn, and project repository links when available. -->
