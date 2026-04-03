# Portfolio — Bhanu Prakash KN

> **Clinical AI Engineer | Medical Imaging | Deployable ML Systems | Singapore**
>
> I design, build, and deploy AI systems that operate at the intersection of clinical medicine, data engineering, and regulatory practice.
> Not prototypes. Working systems — validated, deployed, and trusted by clinicians.

---

## Table of Contents
- [Who I Am](#who-i-am)
- [Flagship Projects](#flagship-projects)
- [Skills Matrix](#skills-matrix)
- [Patents](#patents--intellectual-property)
- [Selected Publications](#selected-publications)
- [Awards & Recognition](#awards--recognition)
- [Career Timeline](#career-timeline)
- [Contact](#contact)

---

## Who I Am

I am a **Principal Scientist and Research Leader** with 40 years of experience across academic teaching, national research, and clinical AI product development. My career has been defined by building systems that bridge the gap between research insight and clinical reality.

**Three things that set me apart from most data scientists:**

**1. I understand clinical workflows from the inside.**
I have spent years working directly with radiologists, neurologists, cardiologists, and emergency physicians — not just supplying models, but co-designing the tools they use. I know what it takes for an AI system to actually fit into a clinical decision process.

**2. I build end-to-end engineering pipelines.**
From raw DICOM acquisition to feature extraction, ML model training, validation, and deployment — I have designed and implemented complete pipelines. I have also managed IT infrastructure, multi-site data workflows, and HPC environments.

**3. I think at regulatory and IP scale.**
With 15 granted patents (5 licensed to industry), experience with NHIC and A*STAR grant frameworks, and work contributing to commercial product revenue, I understand what it takes to move from algorithm to deployable, protected, and monetisable clinical product.

---

## Flagship Projects

### 🧠 Project 1: Stroke Clinical AI System (iStrokeSuite / Stroke CAD)

**Problem:** Stroke is a time-critical emergency. Radiological assessment is slow and variable under pressure. Singapore needed a deployable tool for emergency room use.

**What I built:**
- Multi-module stroke CAD covering ischemic, hemorrhagic, probabilistic, and emergency room workflows
- Automated segmentation of infarcted brain tissue from DWI/CT volumes
- Atlas-assisted interpretation integrated with clinical PACS systems
- Deployed across Singapore health clusters

**Technical approach:** Custom DWI segmentation algorithms, energy-measure-based infarct detection, probabilistic atlas alignment, DICOM-integrated deployment

**Outcome:** Asian Innovation Award finalist. RSNA Certificate of Merits. Deployed in clinical use.

**Patents:** US8369598 · US8125223 · SG163063 · EP2089851 · SG151426

---

### 🧬 Project 2: SG Normative Brain Template & Volumetry Atlas

**Problem:** All existing brain atlases were built on Western Caucasian populations. Asian brains have different morphological norms. Clinical neuroassessment tools using these atlases were systematically miscalibrated for Singaporean patients.

**What I built:**
- Deep learning framework to construct a population-specific brain reference template for Singapore
- Automated volumetry pipeline normalised against an Asian ageing cohort
- Designed to integrate with existing clinical neuroimaging workflows

**Technical approach:** Deep learning-based segmentation and registration, template construction, population-based normalisation, NUS/clinical data pipelines

**Outcome:** NHIC Innovation Grant recipient. Ongoing at CIRC, NUS (2025–present).

---

### 🔬 Project 3: Schizophrenia Subtype Classification via Neuroimaging

**Problem:** Schizophrenia is clinically heterogeneous. One-size-fits-all treatment fails a significant proportion of patients. No validated neuroimaging biomarker framework existed for Singapore's patient population.

**What I built:**
- ML pipeline for binary classification of normal vs. schizophrenia subjects from MRI data
- Unsupervised clustering to identify biologically distinct subtypes
- Feature extraction and selection pipeline from structural/functional neuroimaging

**Technical approach:** SVM, clustering (k-means/hierarchical), neuroimaging feature extraction (cortical thickness, volumetrics, connectivity), cross-validation

**Outcome:** Published in peer-reviewed journals. Enabled personalised treatment protocols.

---

### 🏃 Project 4: AI Framework for Sarcopenic Obesity & Metabolic Profiling

**Problem:** Singapore's ageing population faces a dual burden of sarcopenia and obesity — often co-occurring in ways that evade standard clinical assessment. No validated AI framework existed for population-scale phenotyping.

**What I built:**
- Multimodal clinical AI pipeline for automated body composition analysis
- Integration with metabolic profiling from population health data
- Designed for geriatric clinical workflows in Singapore's health clusters

**Technical approach:** Multi-modal data fusion (imaging + clinical lab + wearable), ensemble ML, body composition segmentation from MRI/CT, clinical API integration

---

### 🫀 Project 5: Multi-site Cardiac MRI Analysis Application

**Problem:** Cardiac MRI protocols vary across research sites and clinical centres, making aggregated analysis unreliable. Multi-centre cardiac studies needed standardised, automated workflows.

**What I built:**
- Cross-site cardiac MRI analysis application supporting diverse study types
- Standardised image acquisition and analysis workflows
- Capable of handling multiple cardiac conditions and acquisition protocols

**Technical approach:** DICOM-compliant multi-site pipeline, cardiac segmentation, volumetric and functional parameter extraction, quality control automation

---

### 📐 Project 6: Brain Atlas Landmark Registration

**Problem:** Standard MRI brain atlas registration was inaccurate for non-standard brain morphologies, impacting the reliability of all downstream neuroimaging analysis.

**What I built:**
- Novel anatomical landmark detection framework for anterior/posterior commissures
- Geometrical fitting approach for improved atlas alignment
- Adopted in multi-centre neuroimaging studies

**Technical approach:** Intensity-based landmark detection, geometric fitting algorithms, multi-resolution registration, automated commissure localisation

**Patents:** US7783090 · US8311359 · US8045775 · SG150019 · SG147488

---

## Skills Matrix

### Artificial Intelligence & Machine Learning
| Skill | Level | Applied In |
|---|---|---|
| Deep Learning (CNN, U-Net, ResNet) | Expert | Brain template, stroke segmentation |
| Classical ML (SVM, RF, Ensemble) | Expert | Schizophrenia classification, radiomics |
| Unsupervised Learning & Clustering | Expert | Patient subtype discovery |
| Radiomics Feature Engineering | Expert | Clinical decision support systems |
| Transfer Learning | Advanced | Clinical imaging with limited data |
| Model Validation & Clinical Benchmarking | Expert | All clinical deployments |

### Medical Imaging & Signal Processing
| Skill | Level | Applied In |
|---|---|---|
| MRI Analysis (structural, functional, diffusion) | Expert | Brain atlas, stroke, schizophrenia |
| CT Image Analysis | Expert | Stroke CAD, body composition |
| DICOM Pipeline Engineering | Expert | Multi-site clinical deployment |
| Biomedical Signal Processing | Expert | EEG, cardiac, metabolic signals |
| Image Segmentation | Expert | Brain, cardiac, stroke, fat compartments |
| Registration & Atlas Methods | Expert | Brain atlas landmark work |

### Engineering & Deployment
| Skill | Level | Applied In |
|---|---|---|
| Python | Advanced | All recent ML/AI projects |
| MATLAB | Expert | Signal processing, legacy clinical systems |
| SQL | Advanced | Clinical database management |
| Docker / Containerisation | Advanced | Clinical tool deployment |
| Linux / HPC | Advanced | Large-scale imaging computation |
| REST API design | Advanced | Clinical system integration |
| AWS / Cloud Infrastructure | Working | Research compute environments |
| Git / Version Control | Advanced | All software projects |

### Clinical & Regulatory
| Skill | Level | Applied In |
|---|---|---|
| Clinical workflow design | Expert | All clinical product development |
| HL7 / DICOM standards | Advanced | PACS integration, multi-site systems |
| IP filing & patent strategy | Expert | 15 granted patents, 5 licensed |
| Grant writing (NHIC, A*STAR, NRF) | Expert | ~S$1M secured |
| Clinical trial data management | Advanced | Multi-site cardiac, neuro studies |
| Research ethics & governance | Expert | All clinical studies |

---

## Patents & Intellectual Property

**15 Patents Granted · 5 Licensed to Industry**

| Year | Title | Patent No. | Jurisdiction |
|---|---|---|---|
| 2013 | Mobile-based framework for clinical emergencies | SG183115 | Singapore |
| 2013 | Identifying pathological regions in MRI (stroke) | EP2089851 | Europe |
| 2013 | Discriminating infarcts from artifacts in MRI | SG163063 | Singapore |
| 2013 | Identifying ischemic stroke regions in MRI | US8369598 | USA |
| 2012 | Registering brain images by aligning reference ellipses | US8311359 | USA |
| 2012 | Segmenting infarct in diffusion weighted imaging | US8125223 | USA |
| 2011 | Localisation of brain commissure landmarks | US8045775 | USA |
| 2011 | Locating a mid-sagittal plane | US7783132 | USA |
| 2010 | Anterior/posterior commissure detection | US7783090 | USA |
| 2010 | Atlas-assisted MRI diffusion/perfusion interpretation | US7783132 | USA |
| 2019 | Fat compartment segmentation in abdominal MRI | PCT/SG2019/050160 | PCT |
| 2020 | Deep learning stroke segmentation in CT | SBIC/Z/11595 | Filed |

---

## Selected Publications

**56 Peer-Reviewed Journal Articles · 100+ Conference Papers**

### Representative Journal Publications

- Stroke CAD system design and validation — *IEEE Transactions / Scientific Reports*
- Neuroimaging biomarkers for schizophrenia subtype classification — *Frontiers in Behavioural Neuroscience*
- Radiomics feature extraction for clinical decision support — *MDPI / AI in Medical Imaging*
- Brain atlas landmark detection and registration — *MAGMA / IJCARS*
- Population health analytics in metabolic disease — *Multiple venues*

### Conference Highlights (Selected)
- **9 Keynote Addresses** at international conferences
- Presentations at RSNA (Radiological Society of North America)
- Radiological Society of Singapore, Asia-Pacific Signal Processing conferences
- European Society of Radiology
- Singapore Congress of Radiology 

### Editorial & Review
- **Editorial Board:** MDPI · AI in Medical Imaging · Frontiers in Behavioural Neuroscience
- **Reviewer:** IEEE · MAGMA · IJCARS · Scientific Reports · MDPI

---

## Awards & Recognition

| Award | Year | Context |
|---|---|---|
| Asian Innovation Award — **Finalist** | 2010 | Stroke CAD System |
| RSNA **Certificate of Merits** | Multiple | Stroke CAD, neuroimaging work |
| **DAAD Fellowship** | — | International research excellence |
| National Merit Scholarship | — | Academic distinction |
| RadiologyAsia Award | — | Clinical imaging innovation |
| SGCR-WIRES Recognition | — | Research contribution |

---

## Career Timeline

```
2025–Present  Lead, Quantitative Imaging & Data-Driven Modelling
              Clinical Imaging Research Centre (CIRC), NUS

2022–2024     Principal Scientist II
              Bioinformatics Institute (BII), A*STAR

2021–2022     Principal Investigator
              Institute of Bioengineering & Bioimaging (IBB), A*STAR

2015–2021     Group Leader, Clinical Data Analytics & Radiomics
              Singapore Bioimaging Consortium (SBIC), A*STAR

2005–2015     Research Scientist
              Singapore Bioimaging Consortium (SBIC), A*STAR

2003–2005     Senior Post-Doc Research Fellow
              Bioinformatics Institute (BII), A*STAR

1986–2003     Selection Grade Lecturer (17 years)
              Sri Jayachamarajendra College of Engineering, Mysore, India

1986          Engineer Trainee — Neyveli Lignite Corporation / Bells Controls
```

---

## Contact

- 📧 **Email:** bhanuprakash.kn@gmail.com
- 💼 **LinkedIn:** [bhanu-prakash-kn-b6b9314](https://www.linkedin.com/in/bhanu-prakash-kn-b6b9314/)
- 🌏 **Location:** Singapore (PR) · Available with 2 months notice
- 🤝 **Open to:** Data Science Engineering roles · Clinical AI · Medical Imaging · Healthcare AI systems

---

*This portfolio is grounded in documented, deployed, and patent-protected work. Every project listed here has been validated in a clinical or research environment.*
