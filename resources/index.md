---
title: Fairness of AI in Medical Imaging
description: "Medical AI fairness resources"
layout: default
permalink: /resources/index.html
weight: -1
redirect_from: /resources/
toc:
  sidebar: left
---

### Getting started with research on AI fairness in medical imaging

FAIMI has put together this resource page to help researchers get started with research on the fairness of AI for medical imaging. 
We would like to see this as an organically evolving resource, so please <a href="mailto:faimi-organizers@googlegroups.com">get in touch with us</a> if you have any suggestions for additions or modifications.

### Literature
The literature body on fairness of AI in medical imaging is growing rapdily, and we do not attempt to provide an exhaustive list of related publications here. 
Rather, we list a few key references for specific areas of fairness research that can act as starting points for your own literature searches.

#### Review papers on AI fairness
- Mehrabi et al (2019)[^1]
- Du et al (2020)
- Chen et al (2023)

#### Seminal works on AI fairness
- Angwin et al (2016): COMPAS study in which racial bias was shown in a machine learning algorithm for predicting recidivism.
- Buolamwini et al (2018): Gender Shades study which was one of the earliest papers to uncover AI bias, in video classification.
- Obermeyer et al (2019): Demonstration that an algorithm actively used to distribute healthcare system resources was severely biased against black patients.

#### Perspectives on what constitutes AI fairness
- Corbett-Davies and Goel (2018): A Critical Review of Fair Machine Learning
- Rajkomar et al (2018): Discussion of fairness and health equity in the medical context.
- McCradden et al (2020): Ethical limitations of algorithmic fairness solutions in health care machine learning.
- Sambasivan et al (2021): Discussion of perspectives on fairness in the low and middle income country context.
- Ricci Lara et al (2022): Discussion of fairness in the medical imaging context.
- Petersen et al (2023): Discussion of (performance) fairness and the causes of performance disparities in the medical context.

#### Shortcut learning and fairness in medical AI
- Geirhos et al (2020): General overview of shortcut learning in deep neural networks (not medicine-specific).
- Yi et al (2021) and Gichoya et al (2022): AI recognition of patient age, sex, and race from medical images, which raises the possibility of bias in AI models trained using such images.
- Glocker et al (2023b): Does encoding of protected characteristics in an AI model necessarily lead to bias?
- Brown et al (2023): Detecting shortcut learning for fair medical AI using shortcut testing.
- Zou et al (2023): Implications of predicting race variables from medical images.

#### Quantitative comparisons
- Zhang et al (2022): Comparison of multiple approaches for addressing bias in chest X-ray classification and evaluation using different definitions of fairness.
- Lee et al (2023): Comparison of bias characteristics of different deep learning models including CNNs and a vision transformer.

#### Applied AI fairness research in medical imaging
##### AI fairness for chest x-rays
- Larrazabal et al (2020)
- Seyyed-Kalantari et al (2021)
- Zhang et al (2022)
- Lin et al (2023)
- Glocker et al (2023a)

##### AI fairness for dermatological images
- Abbasi-Sureshjani et al (2020)
- Kinyanjui et al (2020)
- Daneshjou et al (2022)
- Pakzad et al (2022)

##### AI fairness for brain MRI:
- Petersen et al (2022)
- Ioannou et al (2022)
- Wang et al (2023)
- Klingenberg et al (2023)

##### AI fairness for cardiac MRI:
- Puyol-Antón et al (2021)
- Puyol-Antón et al (2022)
- Lee et al (2022)
- Lee et al (2023)

##### AI fairness for ophthalmology:
- Burlina et al (2021)
- Lin et al (2023)

##### AI fairness for breast DCE-MRI:
- Huti et al (2023)

##### AI fairness for medical image segmentation:
- Puyol-Antón et al (2021): Cardiac MRI
- Puyol-Antón et al (2022): Cardiac MRI
- Lee et al (2022): Cardiac MRI
- Lee et al (2023): Cardiac MRI
- Ioannou et al (2022): Brain MRI
- Yuan et al (2022): Dermatology images

#### Miscellaneous
- Jones et al (2023): Relationship between causality and fairness.
- Schrouff et al (2022): Are bias mitigation strategies robust to real-world domain shifts?
- Wachter et al (2021, 2023): Legal perspective on fairness in AI and the “levelling down” phenomenon in “fair” machine learning.
- Simoiu et al (2017) and Kearns et al (2018): Fairness with respect to one protected attribute can hide aggravated unfairness with respect to another (a.k.a. inframarginality / fairness gerrymandering / subgroup fairness).
- Mukherjee et al (2022): Confounding factors need to be accounted for when assessing performance disparities.
- Ricci Lara et al (2023) and Petersen et al (2023b): Standard calibration error metrics (such as ECE) are biased with respect to sample size, which must be taken into account when comparing calibration between (protected) groups of different sizes.
- Lazar Reich and Vijaykumar (2020): Contrary to popular belief, equalised odds (i.e., equal TPR and FPR) and calibration by groups are compatible.

### Software toolkits
Although one can investigate fairness issues with standard software environments and packages, a number of researchers have made specialised toolkits aimed at facilitating fairness and bias assessments, and you may find it more efficient to make use of one of these.
- [AI Fairness 360](https://ai-fairness-360.org/), Bellamy et al, 2018. Initially created by IBM but now independent.
- [FairLearn](https://fairlearn.org/), Bird et al, 2020. Initially created by Microsoft but now independent.
- [Aequitas](http://www.datasciencepublicpolicy.org/our-work/tools-guides/aequitas/), Saleiro et al, 2018. Open source bias audit toolkit for machine learning developers (not imaging).
- [MEDFAIR](https://github.com/ys-zong/MEDFAIR), Zong et al, 2023. Fairness benchmarking suite for medical imaging.

### Initiatives, guidelines and legislation
Below are some resources related to data collection and research initiatives, guidelines on fairness in AI and information about government efforts to legislate on the use of AI, many of which include reference to fairness and bias.
#### Initiatives:
- [STANDING Together](https://www.datadiversity.org/), Ganapathi et al, 2022. Promotes the formation of inclusive, diverse and transparent medical datasets.
- [“All of Us” research programme](https://allofus.nih.gov/), All of Us Research Program Investigators, 2019. US initiative to acquire diverse medical data (not imaging).
- Fairness of AI in Medical Imaging (FAIMI): that's us, an independent academic initiative aimed at exploring and promoting fair AI in medical imaging.

#### Guidelines:
- [FUTURE-AI](https://future-ai.eu/) aims to establish guidelines for AI in healthcare, including fairness as a key principle.
- [Algorithmic Bias Playbook](https://www.chicagobooth.edu/-/media/project/chicago-booth/centers/caai/docs/algorithmic-bias-playbook-june-2021) (Obermeyer et al, 2021): A high-level discussion which addresses aspects such as label choice bias.

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
- [UK Biobank](https://www.ukbiobank.ac.uk/): Database of half a million patients from the UK population including approximately 100,000 with imaging consisting of heart, brain and abdominal MRI together with a wide range of demographic information. Available worldwide to approved projects upon payment of administration fee.
- [ADNI](https://adni.loni.usc.edu/data-samples/access-data/), Mueller et al, 2005: Multisite study of brain imaging (MRI), biochemical, and genetic data with Alzheimer’s diagnosis status and demographic information including race and sex.
- [ISIC challenge datasets](https://challenge.isic-archive.com/data/): The International Skin Imaging Collaboration (ISIC) runs yearly challenges for AI processing of dermatology images. Some of these have associated skin tone information.
- [PAD-UFES](https://data.mendeley.com/datasets/zr7vgbcyr2/1), Pacheco et al, 2020: skin lesion dataset, dermatology images with 22 clinical parameters including age and Fitzpatrick skin type.
- [Diverse Dermatology Images](https://ddi-dataset.github.io/), Daneshjou et al, 2022: Database of 656 dermatology images from 570 unique patients, approximately balanced by skin tone. Expert annotations of lesion diagnosis and Fitzpatrick skin tone. Freely available.
- [Fitzpatrick 17k dataset](https://github.com/mattgroh/fitzpatrick17k), Groh et al, 2021: Database of 17k dermatology images with algorithmically determined Fitzpatrick skin tone data.
- [NIH  chest X-ray  dataset](https://www.kaggle.com/datasets/nih-chest-xrays/data): 112,120  chest  X-ray  images  from  30,805  patients,  labelled  with  14  common  thorax  diseases  and demographic information including age and sex.
- [CheXpert chest X-ray dataset](https://stanfordmlgroup.github.io/competitions/chexpert/), Irvin et al, 2019: 224,316 chest X-rays of 65,240 patients with age and sex information.
- [PadChest](https://bimcv.cipf.es/bimcv-projects/padchest/), Bustos et al, 2020: chest X-ray dataset, 160,000 chest X-ray images from 67,000 patients, includes age.
- [Duke-Breast-Cancer-MRI](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226903), Saha et al, 2018: Dataset of Dynamic Contrast Enhanced MRI images of women with breast cancer, includes images, derived radiomics, tumour segmentations and patient demographics including race. Freely available upon registration.

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

### References
[^1]: Mehrabi et al (2019), “A Survey on Bias and Fairness in Machine Learning”, ...
