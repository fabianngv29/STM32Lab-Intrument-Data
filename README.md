# STM32Lab-Intrument-Data
This repository contains the complete dataset used in the educational evaluation of the STM32Lab, an integrated microcontroller learning platform designed to improve hands-on laboratory performance in microcontroller course.
The study follows a **quasi-experimental design** comparing:

- **Control Group** → Blue Pill and breadbords (traditional)
- **Experimental Group** → STM32Lab (integrated PCB)

The dataset enables complete reproducibility of the statistical and qualitative analyses of the study.

# Data
### **1. Pre and Post Learning Surveys (Pre.csv, Post.csv)**
These files contain responses to 17 Likert-scale items (Q1–Q17) and three open-response items (Q18–Q20).  
The survey measures student perceptions of competencies such as:

- Microcontroller fundamentals  
- Programming in C and Assembly  
- Debugging and troubleshooting  
- Peripheral configuration (GPIO, ADC, PWM, UART, I²C)  
- Datasheet interpretation  
- Autonomous learning  
- Readiness for interdisciplinary embedded-systems projects  

**Columns:**

- `Group` → 1 = Control, 2 = Experimental  
- `q1`–`q17` → Likert responses (1–5)  
- `q18`, `q19`, `q20` → open-ended answers  

**Uses:**  
Pre/post analysis, item-level gain computation, global improvement evaluation, qualitative coding.

---

### **2. Laboratory Logs (Logs.xlsx)**

This file contains **10 sheets**, each corresponding to one laboratory practice.  
Logs include real-world performance metrics captured during hands-on sessions.

**Columns:**

- `Group` (1 = Control, 2 = Experimental)  
- `Time (min)`  
- `Observed participation`  
- `Common difficulties`  
- Error categories:
  - `Errors: Hardware/Connection`
  - `Errors: Prototype/Assembly`
  - `Errors: Firmware/Configuration`
  - `Errors: Conceptual/Logical`
- `Total Errors`
- `Practice notes`

**Uses:**  
Time-on-task analysis, error distribution per group, difficulty profiling, comparative performance evaluation.

---
### **3. MSLQ Survey (MSLQ.csv)**

Results from a subset of the **Motivated Strategies for Learning Questionnaire (MSLQ)**,  
which assesses motivational and self-regulated learning behaviors.

Includes Likert 1–5 items evaluating:

- Intrinsic motivation  
- Task value  
- Self-efficacy  
- Cognitive strategy use  
- Self-regulation  

**Uses:**  
Correlation with learning gains, motivational profiling, regression models, multi-dimensional learning analysis.

---

## 🎯 Purpose of the Dataset

This dataset supports:

- Pre/post statistical comparisons  
- Computation of normalized and relative learning gains  
- Analysis of laboratory performance (time, errors, participation)  
- Cross-analysis between motivation (MSLQ) and learning outcomes  
- Replication of all study figures, tables, and statistical models  
- Publication-quality visualizations and reproducible research workflows  

---

## 🛠 Recommended Tools

- Python + Colab / Jupyter  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy, StatsModels (optional)

---

# Paper related and citation
Link to paper: 

## 👤 Author
Alejandra Cepeda-Argüelles, Fabián García-Vázquez, Héctor A. Guerrero-Osuna, Perla C. Miranda-Barreras, Jesús A. Nava-Pintor, Luis F. Luque-Vega, Emmanuel Lopez-Neri, Ma. del Rosario Martínez-Blanco

# Acknowledgements
The authors want to thank the Mexican Secretariat of Science, Humanities, Technology and Innovation (SECIHTI by its initials in Spanish) for its support to the National Laboratory of Embedded Systems, Advanced Electronics Design and Micro Systems (LN-SEDEAM by its initials in Spanish), project numbers 282357, 293384, 299061, 314841, 315947, and 321128 and scholarship numbers 1012274.
