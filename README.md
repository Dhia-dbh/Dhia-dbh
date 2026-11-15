<div align="center">

# Dhia Ben Hamouda

### AI Engineer · Machine Learning · LLM Systems · Automation

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=4A8FA8&center=true&vCenter=true&width=680&lines=I+ship+ML+from+notebook+to+API;1%2C000%2B+tracked+experiments+on+a+4+GB+laptop+GPU;I+write+down+the+results+that+fail+too" alt="I ship ML from notebook to API. 1,000+ tracked experiments on a 4 GB laptop GPU. I write down the results that fail too." />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhiabenhamouda-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/dhiabenhamouda)
[![Email](https://img.shields.io/badge/Email-dhiabenhamouda.pro@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:dhiabenhamouda.pro@gmail.com)
[![CV](https://img.shields.io/badge/CV-PDF-111111?logo=readthedocs&logoColor=white)](./BenHamouda_Dhia-CV.pdf)
![Based in Sousse, Tunisia](https://img.shields.io/badge/Based_in-Sousse,_TN-555555)
![Open to AI and Software Engineering roles](https://img.shields.io/badge/Open_to-AI_%26_Software_Engineering_roles-3B7890)

</div>

I'm a computer science engineer from Sousse, Tunisia. I build AI systems that people use at work:
document automation, LLM evaluation and decision support, from the model to the API and the interface.

I trained as a software engineer and planned to stay one. Then six months in a research lab at
TU Chemnitz showed me that I enjoy an open question as much as a working build, so now I do both.

## 📍 My path so far

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'cScale0': '#2C4A6B', 'cScaleLabel0': '#ffffff', 'cScale1': '#2F5876', 'cScaleLabel1': '#ffffff', 'cScale2': '#326680', 'cScaleLabel2': '#ffffff', 'cScale3': '#35748A', 'cScaleLabel3': '#ffffff', 'cScale4': '#38818D', 'cScaleLabel4': '#ffffff', 'cScale5': '#3A8C88', 'cScaleLabel5': '#ffffff'}}}%%
timeline
    2021 : 🎓 Started computer science engineering at ISIMM
    2022 : 🥇 IEEEXtreme, 1st place at my university
    2023 : ☁️ Microsoft Azure AI Fundamentals certified
    2024 : 👑 Top of my class, 1st of 57
         : 🏆 3 hackathon first prizes
         : ⚙️ OZEOL, AI automation engineer intern
    2025 : 🤖 Proxym Group, junior AI engineer intern
         : 🧠 EEG Foundation Challenge
    2026 : 🇩🇪 DAAD scholarship, thesis at TU Chemnitz
         : 🎓 Graduated with highest honours
         : 🧠 EEG Foundation Challenge, second year
```

| 🏆 Competitions | 👑 Academics | ⚙️ Automation | 🧪 Experiments |
|:---:|:---:|:---:|:---:|
| 15+ hackathons, 3 first prizes, and 1st at my university in IEEEXtreme | 1st of 57, graduated with highest honours | About 50% less document-processing time at OZEOL | 1,000+ ML training runs tracked and written up |

## 👋 Who are you looking for?

Click a box to open it. Everything stays on this page.

<table><tr><td>
<details>
<summary><h3>🔬 A Research Associate / PhD candidate &nbsp;·&nbsp; click to open</h3></summary>

> 📄 My [motivation letter](./BenHamouda_Dhia-Motivation_letter.pdf) covers my research interests and my reasons for pursuing a PhD.
> Write to me by [email](mailto:dhiabenhamouda.pro@gmail.com) or on [LinkedIn](https://linkedin.com/in/dhiabenhamouda) and I'll send the rest of my documents, including my transcripts.

### Research interests

- 🧠 **EEG neural decoding.** Models that hold up across participants and recording sessions, and that can show which features they rely on.
- 🤖 **Efficient agentic systems.** Making small language models reliable through system design, tool use and evaluation instead of scale.
- 🔋 **Machine learning for batteries.** Data-driven and physics-informed state estimation from impedance spectroscopy.

### Research experience

**Engineering thesis** · Technische Universität Chemnitz, Measurement and Sensor Technology · 02/2026 – 07/2026 · DAAD KOSPIE scholarship

*Comparative Analysis of Electrochemical Impedance Spectroscopy Representations for Machine-Learning-Based State-of-Charge Estimation of Lithium-Ion Batteries*

- Compared five representations of impedance spectra, alone and combined, with conventional ML and CNN architectures.
- Evaluated every model leave-one-cell-out, so each was tested on a battery cell it had never seen.
- Used SHAP and Grad-CAM to find the spectral regions the models rely on, and matched them to electrochemical processes.

### Independent project: EEG Foundation Challenge (2025 and 2026)

I have entered this international competition two years in a row, on my own, with a laptop that has a
4 GB GPU and Kaggle's free T4s.

**2025 · Reaction-time decoding.** The task was to predict how fast someone responds from two seconds of
129-channel EEG. I built the pipeline with MNE-Python and an attention-based regressor in PyTorch. The
result was an nRMSE of 1.00, no better than always predicting the average, and I had let the test set
steer the learning-rate schedule. I took two rules into the next year: fix the evaluation before
touching the model, and write down the results that fail.

**2026 · BCI decoding (Track 02), in progress.** The task is to tell which of three mental tasks a person
is doing (imagining a movement, subtracting numbers, generating words) from four seconds of 41-channel
EEG. The model is scored on people it has never seen and on later sessions of people it has.

The competition is still running, so I'm keeping the details for later. So far I have designed and
compared these families of models:

- compact convolutional networks that learn temporal and spatial filters
- recurrent and transformer models on top of convolutional features
- spectral models built on frequency-band power
- two-branch models that combine a learned view of the signal with a spectral one
- pretrained EEG foundation models with different heads and fine-tuning strategies
- self-supervised pretraining with several objectives
- ensembles of the above

I'll publish the full results and what I learned from them after the final deadline.

</details>
</td></tr></table>

<table><tr><td>
<details>
<summary><h3>💼 An AI / Software Engineer &nbsp;·&nbsp; click to open</h3></summary>

### Experience

**Research Intern, Machine Learning** · Technische Universität Chemnitz · Chemnitz, Germany · 02/2026 – 07/2026
- Built a framework that compares five data representations for estimating battery state of charge, with every model tested on cells it had never seen.
- Explained the models' predictions with SHAP and Grad-CAM.

**Junior AI Engineer (Internship)** · Proxym Group · Sousse, Tunisia · 06/2025 – 08/2025
- Built an LLM-as-a-Judge prototype that evaluates SQL with a Performer–Judge workflow. It evaluated 162 internal queries, with a reported 12% reduction in query runtime.
- Prototyped a credit decision-support tool that combines rules, ML and LLM reasoning, served through FastAPI with a React interface. A human reviews every recommendation.

**AI Automation Engineer (Internship)** · OZEOL · Sousse, Tunisia · 06/2024 – 09/2024
- Cut average document-processing time by about 50% by combining OCR, language detection and NLP classification for multilingual files.
- Delivered extraction and normalisation through a Flask API and a React interface, with reported extraction precision above 85% across PDF, Word, Excel and image inputs.

### Projects

- [**BtalaLos**](https://github.com/Dhia-dbh/BtalaLos): a self-hosted job-search workspace with AI-tailored CVs and cover letters, PDF export and application tracking (TypeScript)
- [**doc-flash**](https://github.com/Dhia-dbh/doc-flash): a FastAPI endpoint that returns your code with LLM-written docstrings and comments
- [**EducationAi**](https://github.com/Dhia-dbh/EducationAi): built from scratch in under 12 hours; won 1st prize at the Code of Duty hackathon
- [**AI-Powered-PDF-to-Excel**](https://github.com/Dhia-dbh/AI-Powered-PDF-to-Excel-Transformation): turns PDF tables and fields into spreadsheets
- **AWS three-tier deployment**: Angular and Node.js on AWS with Auto Scaling and RDS; server setup automated with Bash, PM2 and systemd behind Nginx

### How I run an ML project

These come from my EEG Foundation Challenge work, described in the research box above.

- **Evaluation first.** Cross-validation by participant, with checkpoints frozen before any test score is read.
- **Everything tracked.** More than 1,000 training runs logged in MLflow across 50+ experiment campaigns, each with a written verdict.
- **Built to a budget.** Trained on 4 GB of GPU memory, with inference kept inside the competition's time limit.
- **Tested before it ships.** I replay the organisers' Docker scoring pipeline locally before every upload.
- **Automated.** Scripts split the work across two Kaggle GPUs, resume after interruptions and package the results.

### Certifications

- **DeepLearning.AI**: Deep Learning Specialization · Natural Language Processing Specialization
- **NVIDIA**: Fundamentals of Deep Learning · Building Transformer-Based NLP Applications · AI for Predictive Maintenance
- **AWS Academy**: Cloud Foundations · Cloud Security Foundations
- **Microsoft**: Azure AI Fundamentals (AI-900)
- **Meta**: Front-End Developer Professional Certificate

</details>
</td></tr></table>

## 🧰 Stack

**🧪 Models and experiments**

<p>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn" height="36" alt="Python, PyTorch, TensorFlow, scikit-learn" />
<img src="./assets/icons/mlflow.svg" height="36" alt="MLflow" title="MLflow" />
<img src="./assets/icons/huggingface.svg" height="36" alt="Hugging Face" title="Hugging Face" />
<img src="./assets/icons/kaggle.svg" height="36" alt="Kaggle" title="Kaggle" />
<img src="./assets/icons/mne.svg" height="36" alt="MNE-Python" title="MNE-Python" />
</p>

**🤖 LLM apps and APIs**

<p>
<img src="./assets/icons/langchain.svg" height="36" alt="LangChain" title="LangChain" />
<img src="https://skillicons.dev/icons?i=fastapi,flask,react,nodejs,ts,postgres,mysql" height="36" alt="FastAPI, Flask, React, Node.js, TypeScript, PostgreSQL, MySQL" />
</p>

**⚙️ Automation and deployment**

<p>
<img src="https://skillicons.dev/icons?i=docker,aws,azure,linux,bash,nginx,git" height="36" alt="Docker, AWS, Azure, Linux, Bash, Nginx, Git" />
</p>

## 🎓 Education

**Engineering Degree in Computer Science** (Diplôme National d'Ingénieur) · ISIMM, University of Monastir, Tunisia · 09/2021 – 10/2026
Highest honours (Mention Excellent) · 1st of 57 in 2024 · Software Engineering specialisation

**Languages:** Arabic (native) · English (C1) · French (B2) · German (B1)

---

<div align="center">

**Contact:** [dhiabenhamouda.pro@gmail.com](mailto:dhiabenhamouda.pro@gmail.com) · [linkedin.com/in/dhiabenhamouda](https://linkedin.com/in/dhiabenhamouda) · Sousse, Tunisia

</div>
