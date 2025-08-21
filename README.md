
# Masked VAE for Missing Data Imputation

A deep generative approach to fill missing values in IoT, industrial, and fintech datasets using **Masked Variational Autoencoders (VAE)**.

---

## 🧠 Project Overview

In real-world applications like IoT, industrial automation, and financial transactions, data often comes with **missing values** due to sensor faults, latency, or logging failures. This project presents a **Masked VAE-based architecture** designed to handle partially observed datasets and perform **accurate and context-aware imputations**.

The model learns data distributions while masking the missing entries, enabling robust and intelligent recovery of missing information.

---

## 🚀 Applications

This project is tailored for:

- **IoT Systems**: Sensor networks in smart homes or smart factories, where real-time data loss can affect monitoring and automation.
- **Industrial Monitoring**: Equipment data streams, SCADA systems, and manufacturing logs that may experience intermittent gaps.
- **Fintech**: Financial transaction records, credit scoring systems, or time-series stock data where entries are incomplete.

Masked VAE helps to restore integrity in such datasets — boosting performance in downstream tasks like forecasting, anomaly detection, and decision-making.

---

## 🛠️ Features

- ✅ Handles both random and non-random missing patterns  
- ✅ Probabilistic modeling with uncertainty estimation  
- ✅ Scalable to high-dimensional tabular data  
- ✅ Customizable masking strategy  
- ✅ Built and tested in Jupyter Notebook  

---

## 📁 Repository Structure

```

Masked\_Vae/
│
├── notebook55e81a0cef.ipynb     # Main implementation and experiments
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md                    # You're here!

```

---

## 📒 How It Works

- A **masking mechanism** is used to simulate missing values in the input.  
- A **VAE** is trained with these masked inputs to learn the latent distribution.  
- During inference, the model generates the most likely values for the missing parts by sampling from the latent space.  

This is more effective than simple interpolation or MICE-based methods, as it learns from global data patterns.

---

## 📊 Example Use Case

Say you have an industrial temperature sensor network with 20% of the data missing due to transmission issues. Running this model:

- Reconstructs missing sensor values using contextual clues  
- Maintains data quality for anomaly detection  
- Avoids costly downtime or misreporting  

---

## 💡 Motivation

> "In real-world data science, *clean data is rare.* This project reflects my interest in building AI systems that **learn from imperfect data** — making them practical and production-ready."

As a Data Scientist with a strong interest in applied machine learning, this project showcases my skills in:

- Probabilistic deep learning  
- Handling real-world data irregularities  
- Building robust, interpretable solutions for industry  

---

## 📜 License

This project is open-sourced under the MIT License.

---

## 🙌 Let's Connect

Feel free to reach out if you're working on missing data problems, generative models, or if you want to collaborate on applied AI research.

- 👤 **Sai Krishna Chaudhary Chundru**  
- 📧 [cchsaikrishnachowdary@gmail.com](mailto:cchsaikrishnachowdary@gmail.com)  
- 🔗 [GitHub](https://github.com/sAI-2025)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/sai-krishna-chowdary-chundru)  

---

