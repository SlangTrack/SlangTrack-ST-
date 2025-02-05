# SlangTrack (ST) - A Dataset for Context-Aware Slang Detection  

Welcome to the **SlangTrack (ST) Dataset**, the first dataset uniquely designed to emphasize words that exhibit both **slang and non-slang contexts**. It enables a **binary classification system** to distinguish between these dual senses, addressing the challenges of **context-dependent slang detection** in **Natural Language Processing (NLP)**. This dataset provides **rich contextual examples** for each usage, supporting both **linguistic research** and **computational applications**.

---

## 📌 Key Features
- **Unique Words**: 48,508  
- **Total Tokens**: 310,170  
- **Average Post Length**: 34.6 words  
- **Average Sentences per Post**: 3.74  

These features ensure a **robust contextual framework** for accurate slang detection and **semantic analysis**.

---

## 🔍 Significance of the Dataset

✔ **Unified Annotation**  
The dataset maintains **consistent annotations** across the corpus, achieving **high Inter-Annotator Agreement (IAA)** for reliability.  

✔ **Addressing Limitations**  
Unlike previous corpora that lacked **clear differentiation** between slang and non-slang meanings, this dataset provides **illustrative examples for each sense**.  

✔ **Comprehensive Coverage**  
Unlike earlier datasets that primarily supported **dictionary-style entries**, this dataset incorporates **historical (COHA) and contemporary (Twitter) sources** with multiple senses for each **target word**.  

✔ **Focus on Dual Meanings**  
The dataset includes words with **at least one slang** and **one dominant non-slang** sense, facilitating **in-depth linguistic exploration**.  

✔ **Applicability to Research**  
By covering **both historical and modern contexts**, the dataset enables the study of **slang's semantic evolution** and its impact on **NLP applications**.

---

## 🎯 Target Word Selection

Each target word in the dataset was **carefully chosen** based on the following criteria:  
✅ It appears in both the **Slang SD Wordlist** and the **Corpus of Historical American English (COHA)**.  
✅ Each word has **2 to 8 distinct senses**, including both **slang and non-slang** meanings.  
✅ Cross-referenced using **trusted sources**, such as:  
  - Green's Dictionary of Slang  
  - Urban Dictionary  
  - Online Slang Dictionary  
  - Oxford English Dictionary  
✅ Words must have **at least one slang and one dominant non-slang sense**.  
✅ **Proper nouns are excluded** to maintain linguistic relevance and focus.

---

## 📂 Data Sources and Collection

### **1️⃣ Corpus of Historical American English (COHA)**
- **Historical examples** were extracted from a **cleaned** version of COHA (CCOHA).  
- Data spans **1980–2010**, capturing **semantic evolution** over time.  

### **2️⃣ Twitter**
- Twitter was chosen for its **dynamic, real-time communication**, providing **rich contemporary slang** examples.  
- For each target word, **1,000 examples** were collected from **tweets (2010–2020)**, reflecting **modern usage**.  

---

## 📊 Data Statistics

The table below provides a breakdown of the total number of instances categorized as **slang** or **non-slang** for each target keyword in the **SlangTrack (ST) Dataset**.

| **Keyword**  | **Non-slang** | **Slang** | **Total** |
|-------------|--------------|----------|----------|
| BMW        | 1083         | 14       | 1097     |
| Brownie    | 582          | 382      | 964      |
| Chronic    | 1415         | 270      | 1685     |
| Climber    | 520          | 122      | 642      |
| Cucumber   | 972          | 79       | 1051     |
| Eat        | 2462         | 561      | 3023     |
| Germ       | 566          | 249      | 815      |
| Mammy      | 894          | 154      | 1048     |
| Rodent     | 718          | 349      | 1067     |
| Salty      | 543          | 727      | 1270     |
| **Total**  | **9755**     | **2907** | **12662** |

---

## 📝 Sample Texts from the Dataset

The table below showcases both **slang** and **non-slang** usage of the **target keywords** with **contextual examples**.

| **Example Sentences** | **Target Keyword** | **Category** |
|----------------------|-------------------|-------------|
| Today, I heard, for the first time, a short scientific talk given by a man dressed as **a rodent**...! An interesting experience. | Rodent | Slang |
| The scientist studied the behaviour of **rodents** in controlled environments. | Rodent | Non-Slang |
| Mom was totally hating on my dance moves. She's so **salty**. | Salty | Slang |
| Greater than this one that washed between the shores of Florida and Mexico. He balanced between the breakers and the turning tide. Small particles of sand churned in the waters around him, and a small fish swam against his leg, a momentary dark streak that vanished in the surf. He began to swim. Buoyant in the **salty** water, he swam a hundred meters to a jetty that sent small whirlpools around its barnacle rough pilings. | Salty | Non-Slang |
| I baked a fresh batch of **brownies** for the school fundraiser. Hope they sell out fast! | Brownie | Non-Slang |
| The **climbers** have made it clear that they want to take a good part of the responsibility, and they’ve been cooperative in helping to educate other climbers about ethical behavior, said Longden. | Climber | Non-Slang |

---

## 🔖 Licenses

The **SlangTrack (ST) Dataset** is built using a combination of **licensed and publicly available corpora**.  
All data has been **preprocessed, anonymized, and randomized** to comply with licensing agreements while preserving linguistic integrity.  
Some source corpora, such as **COHA, require a paid license and restrict redistribution**, but our processed dataset is **legally shareable and publicly available** for **research and development purposes**.

---

## 📥 Download & Citation

To access the dataset, visit the **[SlangTrack Repository](https://github.com/Afnan-aloraini/SlangTrack-ST)**.

---

## 📩 Contact

For any questions or further information, please contact:  

📧 **Afnan Aloraini** - [afnan.aloraini@postgrad.manchester.ac.uk](mailto:afnan.aloraini@postgrad.manchester.ac.uk)

