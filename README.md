# Knowledge Distillation and Transfer Learning based Fear Level Detection in Humans

<p align="center">
    <img src="https://img.shields.io/badge/Techniques-Knowledge%20Distillation%2C%20Transfer%20Learning-brightgreen" alt="Knowledge Distillation and Transfer Learning">
    <img src="https://img.shields.io/badge/Data-DEAP%2C%20ASCERTAIN%20Datasets-blue" alt="DEAP, ASCERTAIN Datasets">
    <img src="https://img.shields.io/badge/Models-CNN%2C%20LSTM%2C%20GRU-orange" alt="ML Models">
</p>

---

## 📌 Overview
Identifying human fear states using deep learning represents a significant stride in **affective computing**, with potential applications in:
- 🏥 Healthcare (mental health monitoring, stress analysis)  
- 🎮 Virtual Reality (immersive experience adaptation)  
- 🤖 Human-Computer Interaction (emotion-aware AI systems)  

This research leverages **Knowledge Distillation (KD)** and **Transfer Learning (TL)** to build efficient and accurate models that classify fear levels using **EEG and physiological signals**.

---

## 🧠 Key Features
- Utilizes **Convolutional Neural Networks (CNNs)**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Units (GRU)** for feature classification.  
- Employs **Knowledge Distillation (KD)** to transfer knowledge from large teacher models to smaller student models, reducing computational costs while maintaining performance.  
- Applies **Transfer Learning (TL)** to improve generalization across datasets with varying distributions.  
- Optimized for deployment on **edge devices** with limited computational resources.  

---

## 📊 Datasets
- **[DEAP Dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/)** → EEG signals labeled with valence-arousal emotional states.  
- **[ASCERTAIN Dataset](https://ascertain-dataset.github.io/)** → Physiological and behavioral signals labeled with continuous emotional states.  

---

## 🔬 Methodology
<img width="870" height="490" alt="image" src="https://github.com/user-attachments/assets/842bd154-8f44-4405-96e9-da0af67ca93b" />

1. **Feature Extraction:**  
   - EEG signals are decomposed into different frequency bands using band pass filtering
   - Selected PPS channels: hEOG, vEOG, zEMG(Electromyography), tEMG, GSR, Respiration, Plethysmograph, Temperature

2. **Knowledge Distillation (KD):**  
   - Student models trained with KD achieve **2–3% higher accuracy** compared to standard models.  
   - Enables compact models suitable for low-resource deployment.  

3. **Transfer Learning (TL):**  
   - Enhances adaptability across different datasets.  
   - Improves generalization for models trained on DEAP and ASCERTAIN.  

---

## 🚀 Results
- **CNNs** achieved the highest classification accuracy.  
- **KD-enhanced student models** demonstrated efficiency improvements with only minor accuracy trade-offs.  
- **LSTM and GRU models** proved effective in modeling temporal dependencies of EEG signals.  
- Proposed framework shows strong potential for **practical applications in real-time systems**.  

---

## 📂 Repository Contents
<ul>
    <li><code>Emotion_recognition_using_dp.ipynb</code> - The complete Jupyter notebook with Method-1 code implementation for fear level detection using CNN, LSTM, GRU.</li>
    <li><code>DEAP_and_ ASCERTAIN.ipynb</code> - The notebook with Method-1 code implementation for fear level detection using CNN and GRU on DEAP and ASCERTAIN datasets.</li>
     <li><code>method-2.ipynb</code> - The complete Jupyter notebook with Method-2 code implementation for fear level detection using CNN</li>
    <li><code>Project_Report.pdf</code> - Detailed project report.</li>
    <li><code>Project_Presentation.pptx</code> - Summary presentation for quick understanding.</li>
</ul>

## 📖 Usage
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/Pranav-raja/knowledge-distillation-and-transfer-learning-based-fear-level-detection-in-humans.git</code></pre>
    </li>
    <li>Install required dependencies, Or use Google Colab
    </li>
    <li>Run the Jupyter Notebook:
        <pre><code>jupyter notebook fear_level_KD.ipynb</code></pre>
        Or upload the ipny file to Google Colab.
    </li>
</ol>

## 📝 Authors
<p>
    Developed by <b>Pranavraja S</b> and <b>Selvakumar T</b>. Contributions are welcome!
</p>
