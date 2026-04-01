<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=60A5FA&center=true&vCenter=true&lines=Compression+Algorithms+Tool;Data+Compression+Analysis;Python+GUI+Project+📊" />
  <br><br>
  <img src="https://img.shields.io/badge/🎓-Academic%20Project-1E40AF?style=for-the-badge&logo=university&logoColor=white" />
  <img src="https://img.shields.io/badge/⚡-5%20Algorithms-3B82F6?style=for-the-badge&logo=code&logoColor=white" />
</div>

---

## <div align="center"><b style="color:#1E40AF">📊 Project Overview</b></div>

**Compression Algorithms Comparison Tool** is a **Python-based desktop application** that allows users to analyze and compare multiple **lossless compression techniques**.

It provides a hands-on way to understand how different algorithms behave on real text data using **Information Theory metrics**.

<div align="center">
  <img src="https://img.shields.io/badge/🧠-Information%20Theory-60A5FA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/📉-Compression%20Analysis-3B82F6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🖥️-Tkinter%20GUI-1E40AF?style=for-the-badge" />
</div>

---

## ✨ **Key Features**

| Feature | Description |
|--------|------------|
| 📝 Text Input | Enter any custom text for compression |
| ⚙️ Multi-Algorithm | Compare 5 compression algorithms |
| 📊 Detailed Metrics | Entropy, efficiency, compression ratio |
| 🧠 Educational | Learn how each algorithm works |
| 🖥️ GUI Interface | Simple and interactive Tkinter UI |

---

## 🧮 **Algorithms Implemented**

- 📌 **Golomb Encoding**
- 📌 **LZW (Lempel-Ziv-Welch)**
- 📌 **Run-Length Encoding (RLE)**
- 📌 **Huffman Coding**
- 📌 **Arithmetic Encoding**

---

## 📊 **Metrics Calculated**

- Compression Ratio  
- Entropy  
- Efficiency  
- Average Code Length  
- Bits Before / After Encoding  
- Symbol Probability Distribution  

---

## 🖥️ **System Flow**

```mermaid
graph TD
    A[📝 User Input Text] --> B[⚙️ Encoding Algorithms]
    B --> C[📌 Golomb]
    B --> D[📌 LZW]
    B --> E[📌 RLE]
    B --> F[📌 Huffman]
    B --> G[📌 Arithmetic]
    
    C --> H[📊 Metrics Calculation]
    D --> H
    E --> H
    F --> H
    G --> H
    
    H --> I[📈 Results Display (Tkinter GUI)]
