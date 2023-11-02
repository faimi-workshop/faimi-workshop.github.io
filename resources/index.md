---
title: Fairness of AI in Medical Imaging
description: "Medical AI fairness resources"
layout: default
permalink: /resources/index.html
weight: -1
redirect_from: /resources/
---

### Getting started with research on AI fairness in medical imaging
FAIMI has put together this resource page to help researchers get started with research on the fairness of AI for medical imaging. 
We would like to see this as an organically evolving resource, so please <a href="mailto:faimi-organizers@googlegroups.com">get in touch with us</a> if you have any suggestions for additions or modifications.

### Literature
The literature body on fairness of AI in medical imaging is growing rapdily, and we do not attempt to provide an exhaustive list of related publications here. 
Rather, we list a few key references for specific areas of fairness research that can act as starting points for your own literature searches.

#### Review papers on AI fairness
- Mehrabi et al (2021), [A Survey on Bias and Fairness in Machine Learning](https://dl.acm.org/doi/10.1145/3457607), ACM Computing Surveys. ([arxiv](https://doi.org/10.48550/arXiv.1908.09635))
- Du et al (2020), [Fairness in Deep Learning: A Computational Perspective](https://ieeexplore.ieee.org/document/9113719), IEEE Intelligent Systems. ([arxiv](https://arxiv.org/abs/1908.08843))
- Chen et al (2023), [Algorithmic Fairness in Artificial Intelligence for Medicine and Healthcare](https://doi.org/10.1038/s41551-023-01056-8), Nature Biomedical Engineering.

#### Seminal works on AI fairness
- Angwin et al (2016), [Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing), ProPublica. *COMPAS study in which racial bias was shown in a machine learning algorithm for predicting recidivism.*
- Hardt et al (2016), [Equality of Opportunity in Supervised Learning](https://dl.acm.org/doi/10.5555/3157382.3157469), NeurIPS. ([arxiv](https://arxiv.org/abs/1610.02413)) *Introduced the concepts of equality of opportunity and equalized odds in algorithmic fairness. Characterizes trade-offs and provides optimal post-processing methods.*
- Chouldechova (2017), [Fair Prediction with Disparate Impact: A Study of Bias in Recidivism Prediction Instruments](https://www.liebertpub.com/doi/10.1089/big.2016.0047), Big Data. *A re-analysis and re-discussion of the COMPAS case. The key result here was that PPV equality and equal error rates are not compatible in the presence of base rate differences between groups.*
- Buolamwini et al (2018), [Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](https://proceedings.mlr.press/v81/buolamwini18a.html), FAccT. *One of the earliest papers to uncover AI bias in image classification.*
- Obermeyer et al (2019), [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://doi.org/10.1126/science.aax2342), Science. *Demonstration that an algorithm actively used to distribute healthcare system resources was severely biased against black patients.*
- Barocas et al (2019), [Fairness and Machine Learning: Limitations and Opportunities](https://fairmlbook.org/index.html). *Full book on algorithmic fairness, covers many aspects.*

#### Perspectives on what constitutes AI fairness
- Corbett-Davies and Goel (2018), [The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning](https://arxiv.org/abs/1808.00023), arXiv. (As of 2023, a version of this is now also in JMLR.)
- Rajkomar et al (2018), [Ensuring Fairness in Machine Learning to Advance Health Equity](https://doi.org/10.7326/M18-1990), Annals of Internal Medicine.
- McCradden et al (2020), [Ethical limitations of algorithmic fairness solutions in health care machine learning](https://doi.org/10.1016/s2589-7500(20)30065-0), The Lancet Digital Health.
- Sambasivan et al (2021), [Re-imagining Algorithmic Fairness in India and Beyond](https://doi.org/10.1145/3442188.3445896), FAccT.
- Ricci Lara et al (2022), [Addressing Fairness in Artificial Intelligence for Medical Imaging](https://doi.org/10.1038/s41467-022-32186-3), Nature Communications. 
- Petersen et al (2023), [The Path Toward Equal Performance in Medical Machine Learning](https://doi.org/10.1016/j.patter.2023.100790), Patterns.

#### Shortcut learning, models recognizing sensitive patient attributes, and fairness in medical AI
- Geirhos et al (2020), [Shortcut Learning in Deep Neural Networks](https://doi.org/10.1038/s42256-020-00257-z), Nature Machine Intelligence. *General overview of shortcut learning in deep neural networks, not medicine-specific.*
- Yi et al (2021), [Radiology “Forensics”: Determination of Age and Sex from Chest Radiographs Using Deep Learning](https://doi.org/10.1007/s10140-021-01953-y), Emergency Radiology, and Gichoya et al (2022), [AI Recognition of Patient Race in Medical Imaging: A Modelling Study](https://doi.org/10.1016/S2589-7500(22)00063-2), Lancet Digital Health. *AI recognition of patient age, sex, and race from chest x-rays, which raises the possibility of bias in AI models trained using such images.*
- Glocker et al (2023), [Algorithmic Encoding of Protected Characteristics in Chest X-ray Disease Detection Models](https://doi.org/10.1016/j.ebiom.2023.104467), eBiomedicine. *Does encoding of protected characteristics in an AI model necessarily lead to bias?*
- Brown et al (2023), [Detecting Shortcut Learning for Fair Medical AI Using Shortcut Testing](https://doi.org/10.1038/s41467-023-39902-7), Nature Communications. *Detecting shortcut learning for fair medical AI using shortcut testing.*
- Zou et al (2023), [Implications of Predicting Race Variables from Medical Images](https://doi.org/10.1126/science.adh4260), Science.

#### Quantitative comparisons
- Zhang et al (2022), [Improving the Fairness of Chest X-ray Classifiers](https://proceedings.mlr.press/v174/zhang22a.html), CHIL. *Comparison of multiple approaches for addressing bias in chest X-ray classification and evaluation using different definitions of fairness.*
- Lee et al (2023), [An Investigation Into the Impact of Deep Learning Model Choice on Sex and Race Bias in Cardiac MR Segmentation](https://doi.org/10.1007/978-3-031-45249-9_21), MICCAI FAIMI workshop. *Comparison of bias characteristics of different deep learning models including CNNs and a vision transformer.*
- Zong et al (2023), [MEDFAIR: Benchmarking Fairness for Medical Imaging](https://doi.org/10.48550/arXiv.2210.01725), ICLR. *Comparison of many standard fairness methods on ten medical image datasets, spanning chest x-rays, brain MRIs, retinal fundus images, dermatoscopic images, heart CT, lung CT, and SD-OCT.*

#### Applied AI fairness research in medical imaging
##### AI fairness for chest x-rays
- Larrazabal et al (2020), [Gender Imbalance in Medical Imaging Datasets Produces Biased Classifiers for Computer-aided Diagnosis](https://doi.org/10.1073/pnas.1919012117), Proceedings of the National Academy of Sciences (USA).
- Seyyed-Kalantari et al (2021), [Underdiagnosis Bias of Artificial Intelligence Algorithms Applied to Chest Radiographs in Under-served Patient Populations](https://doi.org/10.1038/s41591-021-01595-0), Nature Medicine. 
- Zhang et al (2022), [Improving the Fairness of Chest X-ray Classifiers](https://proceedings.mlr.press/v174/zhang22a.html), CHIL.
- Lin et al (2023), [Improving Model Fairness in Image-based Computer-aided Diagnosis](https://doi.org/10.1038/s41467-023-41974-4), Nature Communications.
- Glocker et al (2023), [Risk of Bias in Chest Radiography Deep Learning Foundation Models](https://doi.org/10.1148/ryai.230060), Radiology: Artificial Intelligence.

##### AI fairness for dermatoscopic images
- Abbasi-Sureshjani et al (2020), [Risk of Training Diagnostic Algorithms on Data with Demographic Bias](https://doi.org/10.1007/978-3-030-61166-8_20), MICCAI.
- Kinyanjui et al (2020), [Fairness of Classifiers Across Skin Tones in Dermatology](https://doi.org/10.1007/978-3-030-59725-2_31), MICCAI.
- Daneshjou et al (2022), [Disparities in Dermatology AI Performance on a Diverse, Curated Clinical Image Set](https://doi.org/10.1126/sciadv.abq6147), Science Advances.
- Pakzad et al (2022), [CIRCLe: Color Invariant Representation Learning for Unbiased Classification of Skin Lesions](https://doi.org/10.1007/978-3-031-25069-9_14), ECCV Workshop on Skin Image Analysis.

##### AI fairness for brain MRI:
- Petersen et al (2022), [Feature Robustness and Sex Differences in Medical Imaging: A Case Study in MRI-Based Alzheimer’s Disease Detection](https://doi.org/10.1007/978-3-031-16431-6_9), MICCAI.
- Ioannou et al (2022), [A Study of Demographic Bias in CNN-Based Brain MR Segmentation](https://doi.org/10.1007/978-3-031-17899-3_2), MICCAI workshop on Machine Learning in Clinical Neuroimaging.
- Wang et al (2023), [Bias in Machine Learning Models can be Significantly Mitigated by Careful Training: Evidence from Neuroimaging Studies](https://doi.org/10.1073/pnas.2211613120), Proceedings of the National Academy of Sciences (USA).
- Klingenberg et al (2023), [Higher Performance for Women than Men in MRI-based Alzheimer's Disease Detection](https://doi.org/10.1186/s13195-023-01225-6), Alzheimer’s Research & Therapy.

##### AI fairness for cardiac MRI:
- Puyol-Antón et al (2021), [Fairness in Cardiac MR Image Analysis: An Investigation of Bias Due to Data Imbalance in Deep Learning Based Segmentation](https://doi.org/10.1007/978-3-030-87199-4_39), MICCAI.
- Puyol-Antón et al (2022), [Fairness in Cardiac Magnetic Resonance Imaging: Assessing Sex and Racial Bias in Deep Learning-Based Segmentation](https://doi.org/10.3389/fcvm.2022.859310), Frontiers in Cardiovascular Medicine.
- Lee et al (2022), [A Systematic Study of Race and Sex Bias in CNN-Based Cardiac MR Segmentation](https://doi.org/10.1007/978-3-031-23443-9_22), MICCAI Workshop on Statistical Atlases and Computational Models of the Heart.
- Lee et al (2023), [An Investigation Into the Impact of Deep Learning Model Choice on Sex and Race Bias in Cardiac MR Segmentation](https://doi.org/10.1007/978-3-031-45249-9_21), MICCAI FAIMI workshop.

##### AI fairness for ophthalmology:
- Burlina et al (2021), [Addressing Artificial Intelligence Bias in Retinal Diagnostics](https://doi.org/10.1167/tvst.10.2.13), Translational Vision Science & Technology.
- Lin et al (2023), [Improving Model Fairness in Image-based Computer-aided Diagnosis](https://doi.org/10.1038/s41467-023-41974-4), Nature Communications.

##### AI fairness for breast DCE-MRI:
- Huti et al (2023), [An Investigation Into Race Bias in Random Forest Models Based on Breast DCE-MRI Derived Radiomics Features](https://doi.org/10.1007/978-3-031-45249-9_22), MICCAI FAIMI workshop.

##### AI fairness for medical image segmentation:
- Puyol-Antón et al (2021), [Fairness in Cardiac MR Image Analysis: An Investigation of Bias Due to Data Imbalance in Deep Learning Based Segmentation](https://doi.org/10.1007/978-3-030-87199-4_39), MICCAI.
- Puyol-Antón et al (2022), [Fairness in Cardiac Magnetic Resonance Imaging: Assessing Sex and Racial Bias in Deep Learning-Based Segmentation](https://doi.org/10.3389/fcvm.2022.859310), Frontiers in Cardiovascular Medicine.
- Lee et al (2022), [A Systematic Study of Race and Sex Bias in CNN-Based Cardiac MR Segmentation](https://doi.org/10.1007/978-3-031-23443-9_22), MICCAI Workshop on Statistical Atlases and Computational Models of the Heart.
- Lee et al (2023), [An Investigation Into the Impact of Deep Learning Model Choice on Sex and Race Bias in Cardiac MR Segmentation](https://doi.org/10.1007/978-3-031-45249-9_21), MICCAI FAIMI workshop.
- Ioannou et al (2022), [A Study of Demographic Bias in CNN-Based Brain MR Segmentation](https://doi.org/10.1007/978-3-031-17899-3_2), MICCAI workshop on Machine Learning in Clinical Neuroimaging.
- Yuan et al (2022), [EdgeMixup: Improving Fairness for Skin Disease Classification and Segmentation](https://doi.org/10.48550/arXiv.2202.13883), arXiv.

#### Miscellaneous
- Simoiu et al (2017), [The Problem of Infra-Marginality in Outcome Tests for Discrimination](https://dx.doi.org/10.2139/ssrn.2811449), The Annals of Applied Statistics, and Kearns et al (2018), [Preventing Fairness Gerrymandering: Auditing and Learning for Subgroup Fairness](https://proceedings.mlr.press/v80/kearns18a.html), ICML: Fairness with respect to one protected attribute can hide aggravated unfairness with respect to another (a.k.a. inframarginality / fairness gerrymandering / subgroup fairness).
- Wick et al (2019), [Unlocking Fairness: a Trade-off Revisited](https://papers.nips.cc/paper/2019/hash/373e4c5d8edfa8b74fd4b6791d0cf6dc-Abstract.html), NeurIPS, and Dutta et al (2020), [Is There a Trade-Off Between Fairness and Accuracy? A Perspective Using Mismatched Hypothesis Testing](https://proceedings.mlr.press/v119/dutta20a.html), ICML: *Observed fairness-accuracy trade-offs may be illusory and purely a result of label bias. Optimizing for fairness may also yield performance-optimal models, even if evaluations on (equally biased) test data suggests otherwise.* Also see Sharma et al (2023), [On Testing and Comparing Fair classifiers under Data Bias](https://arxiv.org/abs/2302.05906), arxiv, on this subject.
- Lazar Reich and Vijaykumar (2020), [A Possibility in Algorithmic Fairness: Can Calibration and Equal Error Rates be Reconciled?](https://drops.dagstuhl.de/opus/volltexte/2021/13872/), FORC. *Contrary to popular belief, equalized odds (i.e., equal TPR and FPR) and calibration by groups **are** compatible.*
- Wachter et al (2021), [Bias Preservation in Machine Learning: The Legality of Fairness Metrics Under EU Non-Discrimination Law](https://dx.doi.org/10.2139/ssrn.3792772), West Virginia Law Review, and Wachter et al (2023), [The Unfairness of Fair Machine Learning: Levelling Down and Strict Egalitarianism by Default](https://ssrn.com/abstract=4331652), Michigan Technology Law Review: *A legal perspective on AI fairness and the “levelling down” phenomenon in “fair” machine learning*.
- Mukherjee et al (2022), [Confounding Factors Need to be Accounted for in Assessing Bias by Machine Learning Algorithms](https://doi.org/10.1038/s41591-022-01847-7), Nature Medicine.
- Schrouff et al (2022), [Diagnosing Failures of Fairness Transfer Across Distribution Shift in Real-world Medical Settings](https://doi.org/10.48550/arXiv.2202.01034), NeurIPS: *Are bias mitigation strategies robust to real-world domain shifts?*
- Zhao and Gordon (2022), [Inherent Tradeoffs in Learning Fair Representations](https://jmlr.org/papers/v23/21-1427.html), JMLR: *Theoretical analysis of how group-invariant representations and statistical/demographic parity hurt accuracy in the presence of base rate differences between groups.*
- Ricci Lara et al (2023), [Towards Unraveling Calibration Biases in Medical Image Analysis](https://doi.org/10.1007/978-3-031-45249-9_13), MICCAI FAIMI workshop, and Petersen et al (2023), [On (Assessing) the Fairness of Risk Score Models](https://doi.org/10.1145/3593013.3594045), FAccT: *Standard calibration error metrics (such as ECE) are biased with respect to the evaluation sample size, which must be taken into account when comparing calibration between (protected) groups of different sizes.*
- Jones et al (2023), [No Fair Lunch: A Causal Perspective on Dataset Bias in Machine Learning for Medical Imaging](https://doi.org/10.48550/arXiv.2307.16526), arXiv.

### Software toolkits
Although one can investigate fairness issues with standard software environments and packages, a number of researchers have made specialised toolkits aimed at facilitating fairness and bias assessments, and you may find it more efficient to make use of one of these.
- [AI Fairness 360](https://ai-fairness-360.org/), [Bellamy et al (2018)](https://doi.org/10.48550/arXiv.1810.01943). Initially created by IBM, now independent.
- [FairLearn](https://fairlearn.org/), [Bird et al (2020)](https://www.microsoft.com/en-us/research/uploads/prod/2020/05/Fairlearn_WhitePaper-2020-09-22.pdf). *Initially created by Microsoft, now independent.*
- [Aequitas](http://www.datasciencepublicpolicy.org/our-work/tools-guides/aequitas/), [Saleiro et al (2018)](https://doi.org/10.48550/arXiv.1811.05577). *Open source bias audit toolkit for machine learning developers (not imaging).*
- [MEDFAIR](https://github.com/ys-zong/MEDFAIR), [Zong et al (2023)](https://doi.org/10.48550/arXiv.2210.01725), ICLR. *Fairness benchmarking suite for medical imaging.*

### Initiatives, guidelines and legislation
Below are some resources related to data collection and research initiatives, guidelines on fairness in AI and information about government efforts to legislate on the use of AI, many of which include reference to fairness and bias.
#### Initiatives:
- [STANDING Together](https://www.datadiversity.org/), [Ganapathi et al (2022)](https://doi.org/10.1038/s41591-022-01987-w), Nature Medicine. *Promotes the formation of inclusive, diverse and transparent medical datasets.*
- [“All of Us” research programme](https://allofus.nih.gov/), [All of Us Research Program Investigators (2019)](https://doi.org/10.1056/NEJMsr1809937), NEJM. *US initiative to acquire diverse medical data.*
- Fairness of AI in Medical Imaging (FAIMI): *that's us, an independent academic initiative aimed at exploring and promoting fair AI in medical imaging*.

#### Guidelines:
- [FUTURE-AI](https://future-ai.eu/) *aims to establish guidelines for AI in healthcare, including fairness as a key principle.*
- [Algorithmic Bias Playbook](https://www.chicagobooth.edu/-/media/project/chicago-booth/centers/caai/docs/algorithmic-bias-playbook-june-2021) (Obermeyer et al, 2021): *high-level discussion addressing aspects such as label choice bias.*

#### Legislation/white papers on regulation of AI:
- [Global AI Legislation Tracker](https://iapp.org/resources/article/global-ai-legislation-tracker/)
- [European Commission, “Proposal for a Regulation of the European Parliament and of the Council Laying Down Harmonised Rules on Artificial Intelligence (Artificial Intelligence Act) and Amending Certain Union Legislative Acts,” 2021](https://ec.europa.eu/newsroom/dae/redirection/document/75788)
- [UK Government Department for Science Innovation and Technology and Office for Artificial Intelligence, “A Pro-innovation Approach to AI Regulation,” 2023](https://www.gov.uk/government/publications/ai-regulation-a-pro-innovation-approach)
- [USA Government, “Blueprint for an AI Bill of Rights,” 2023](https://www.whitehouse.gov/ostp/ai-bill-of-rights/)
- State-by-state summary of AI legislation can be found [here](https://epic.org/the-state-of-state-ai-laws-2023/)
- [ISO has a technical standard on AI bias](https://www.iso.org/standard/77607.html), [IEEE has one under development](https://standards-dev21.ieee.org/ieee/7003/6980/), [NIST has a proposal document as well](https://doi.org/10.6028/NIST.SP.1270)

### Datasets
Unfortunately, most currently available databases of medical imaging data do not feature associated demographic information such as sex and race, which is essential for much work in fairness of AI. 
Below we have put together a summary of the most commonly used datasets that do feature such information.
- [UK Biobank](https://www.ukbiobank.ac.uk/). *Database of half a million patients from the UK population including approximately 100,000 with imaging consisting of heart, brain and abdominal MRI together with a wide range of demographic information. Available worldwide to approved projects upon payment of administration fee.*
- [ADNI](https://adni.loni.usc.edu/data-samples/access-data/), [Mueller et al (2005)](https://doi.org/10.1016/j.nic.2005.09.008), Neuroimaging Clinics of North America: *Multisite study of brain imaging (MRI), biochemical, and genetic data with Alzheimer’s diagnosis status and demographic information including race and sex.*
- [ISIC challenge datasets](https://challenge.isic-archive.com/data/). *The International Skin Imaging Collaboration (ISIC) runs yearly challenges for AI processing of dermatology images. Some of these have associated skin tone information.*
- [PAD-UFES](https://data.mendeley.com/datasets/zr7vgbcyr2/1), [Pacheco et al (2020)](https://doi.org/10.17632/zr7vgbcyr2.1), Data in Brief: *skin lesion dataset, dermatology images with 22 clinical parameters including age and Fitzpatrick skin type.*
- [Diverse Dermatology Images](https://ddi-dataset.github.io/), [Daneshjou et al (2022)](https://doi.org/10.1126/sciadv.abq6147), Science Advances. *Database of 656 dermatology images from 570 unique patients, approximately balanced by skin tone. Expert annotations of lesion diagnosis and Fitzpatrick skin tone. Freely available.*
- [Fitzpatrick 17k dataset](https://github.com/mattgroh/fitzpatrick17k), [Groh et al (2021)](https://openaccess.thecvf.com/content/CVPR2021W/ISIC/html/Groh_Evaluating_Deep_Neural_Networks_Trained_on_Clinical_Images_in_Dermatology_CVPRW_2021_paper.html), CVPR workshops. *Database of 17k dermatology images with algorithmically determined Fitzpatrick skin tone data.*
- [NIH  chest X-ray  dataset](https://www.kaggle.com/datasets/nih-chest-xrays/data). *112,120  chest  X-ray  images  from  30,805  patients,  labelled  with  14  common  thorax  diseases  and demographic information including age and sex.*
- [CheXpert chest X-ray dataset](https://stanfordmlgroup.github.io/competitions/chexpert/), [Irvin et al (2019)](https://doi.org/10.1609/aaai.v33i01.3301590), AAAI. *224,316 chest X-rays of 65,240 patients with age and sex information.*
- [PadChest](https://bimcv.cipf.es/bimcv-projects/padchest/), [Bustos et al (2020)](https://doi.org/10.1016/j.media.2020.101797). *Chest X-ray dataset, 160,000 chest X-ray images from 67,000 patients, includes age*.
- [Duke-Breast-Cancer-MRI](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226903), [Saha et al (2018)](https://doi.org/10.1038%2Fs41416-018-0185-8), British Journal of Cancer. *Dataset of dynamic contrast-enhanced MRI images of women with breast cancer, includes images, derived radiomics, tumour segmentations and patient demographics including race. Freely available upon registration.*

### Talks
#### 2016
- [Joy Buolamwini (TED talk), “How I’m Fighting Bias in Algorithms”](https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms)

#### 2019
- [Sandra Wachter, “When AI Disrupts the Law: Fairness, Privacy and Advertising in an Algorithmic World”](https://www.youtube.com/watch?v=cSQrd4H3kOU)

#### 2021
- [Marzyeh Ghassemi, “The Fairest of Them All: Privacy, Data and Machine Learning for Health”](https://www.youtube.com/watch?v=_F8cBeVEedE)
- [Eran Tal, “Accuracy and Fairness in Machine Learning: Lessons From Measurement”](https://www.youtube.com/watch?v=iVqQ4MlIG0o)
- [Natalia Martinez, “Blind Pareto Fairness and Subgroup Robustness”](https://slideslive.com/38959193/blind-pareto-fairness-and-subgroup-robustness)
- [Nithya Sambasivan, “Reimagining ML Fairness in India and Beyond”](https://www.youtube.com/watch?v=MX9qgLclb_I)
- [Abeba Birhane, “The Limits of Fairness”](https://www.youtube.com/watch?v=ekA2z3Xpzpw)
- [Sara Gerke, “Legal Issues of Artificial Intelligence in Healthcare in the US”](https://www.youtube.com/watch?v=zwONJAxK_AA)

#### 2022
- [FAIMI 2022 Online Symposium talks](https://www.youtube.com/playlist?list=PLgwux8eqIFKdWYJTgeoCU4vZ0s6GZtc6e)
- [Judy Wawira Gichoya, “Hidden in Plain Sight: An Update to the Reading Race Project”](https://www.youtube.com/watch?v=Lm7Ir0K43Us)
- Sanmi Koyejo, “Algorithmic Fairness: Why it's Hard, and Why it's Interesting”, CVPR Tutorial: [Part 1](https://www.youtube.com/watch?v=nR4nfpXNtpg), [Part 2](https://www.youtube.com/watch?v=h_aAtC8zvKo&t=0s)
- [Jessica Schrouff, “Maintaining Fairness Under Distributions Shift”](https://www.youtube.com/watch?v=eEREC-WDHAI)
