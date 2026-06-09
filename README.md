# 🌾 Automated Grain Counting

<div align="center">
    
### **Automated Grain Counting** | **Advanced CV Pipeline** | **Easy Deployment**

⭐ **Star this repo if it helps you!** ⭐

🔥 **Share it with the community!** 🔥

[![Share on X](https://img.shields.io/badge/Share_on-X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/intent/tweet?text=Check%20out%20this%20amazing%20Rice%20Detection%20project!%20🌾🤖%20Perfect%20for%20agriculture%20and%20research!%20https://github.com/Mushrum-mmb/Simple_Rice_Detection%20%23ComputerVision%20%23Agriculture%20%23OpenCV)
[![Share on Facebook](https://img.shields.io/badge/Share_on-Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/Mushrum-mmb/Simple_Rice_Detection)
[![Share on LinkedIn](https://img.shields.io/badge/Share_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/Mushrum-mmb/Simple_Rice_Detection)
[![Share on Reddit](https://img.shields.io/badge/Share_on-Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/submit?title=Amazing%20Rice%20Detection%20Computer%20Vision%20Project&url=https://github.com/Mushrum-mmb/Simple_Rice_Detection)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Gallery](#-gallery)
- [Local Usage](#️-local-usage)
- [Google Colab Usage](#-google-colab-usage)
- [How It Works](#-how-it-works)
- [Contributing](#-contributing)
- [License](#-license)

</details>

---

## 🚀 About

<div align="center">

**🌾 Revolutionary Computer Vision for Agricultural Applications!**

</div>

This cutting-edge computer vision application automatically detects and counts rice grains in images using a sophisticated hybrid approach that combines the **watershed algorithm** with **advanced contour detection**. Perfect for agricultural research, quality control, and grain analysis!

<div align="center">

| **Algorithm** | **Framework** | **Author** | **Interface** |
|:---:|:---:|:---:|:---:|
| **Watershed + Contour** | Gradio | [Mushrum-mmb](https://github.com/Mushrum-mmb/) | Web-based |

</div>

### 🌟 **Key Highlights:**
- **Advanced hybrid detection** algorithm
- **Accurate grain counting** even for touching grains
- **Visual processing pipeline** with step-by-step breakdown
- **User-friendly web interface** with instant results
- **Cloud-ready** for Google Colab deployment
- **Cross-platform compatibility**

---

## 📸 Gallery

<div align="center">

### 🔍 **See the Magic in Action!**

*Examples of successful rice grain detection and counting*

<img src="https://github.com/user-attachments/assets/506cf60d-e081-4e38-9aaf-42ed5f5fb257" alt="Rice Detection Example 1" width="45%"/>
<img src="https://github.com/user-attachments/assets/be6f8423-81b6-4008-ae29-de91a8ad1eac" alt="Rice Detection Example 2" width="45%"/>

*Computer Vision Pipeline Overview*

<img width="1647" height="994" alt="image" src="https://github.com/user-attachments/assets/f15eef3e-1ea0-4455-8c9f-745a7d355198" />


</div>

---

## ✨ Features

<div align="center">

### **What Makes This Special?**

</div>

| Feature | Description | Benefit |
|---------|-------------|---------|
| **Advanced Detection** | Hybrid watershed + contour algorithm | Accurate detection of touching grains |
| **Visual Pipeline** | Complete image processing workflow | Transparent and debuggable process |
| **Automatic Counting** | Smart grain enumeration and labeling | Instant quantitative results |
| **Process Visualization** | Step-by-step processing breakdown | Educational and debugging value |
| **Web Interface** | Gradio-powered user-friendly UI | No technical knowledge required |
| **Cloud Compatible** | Google Colab ready deployment | Perfect for low-spec devices |

<div align="center">

### 🎯 **Perfect For:**
**Agricultural Research** • **Quality Control** • **Educational Projects** • **Computer Vision Learning**

</div>

---

## ▶️ Local Usage

<div align="center">

### 🚀 **Launch Your Rice Detector in 3 Simple Steps!**

</div>

**Step 1:** Clone the repository
```bash
git clone https://github.com/Mushrum-mmb/Automated-Grain-Counting.git
```

**Step 2:** Navigate to project directory
```bash
cd Automated-Grain-Counting
```

**Step 3:** Launch the application
```bash
python rice_detector.py
```

<div align="center">

### 🎉 **Your Automated Grain Counting is Ready!**
Open the provided link in your browser and start analyzing rice images!

<img width="1049" height="159" alt="image" src="https://github.com/user-attachments/assets/8c3cd42c-a70b-4f44-a19f-c66b51b4d3b7" />


</div>

---

## 💻 Google Colab Usage

<div align="center">

### ☁️ **Perfect for Everyone!** 🌤️

[![Open In Colab](https://img.shields.io/badge/Open_in-Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1uSx4NkhXVZqAetb9ug3tsZRLJ2CWwNpo?usp=sharing)

</div>

Experience the power of cloud computing! Our Google Colab notebook provides instant access to rice detection capabilities without any local setup.

<details>
<summary>📖 <strong>Quick Colab Guide (Click to expand)</strong></summary>

**Step 1:** Run the Gradio installation cell
![Colab Installation](https://github.com/user-attachments/assets/85778e45-9bdf-4b05-a9d8-48efedd338f6)

**Step 2:** Execute the final cell and start detecting! 🎉

**That's it!** No uploads, no complex setup - just pure rice detection power in the cloud!

</details>

---

## 🔧 How It Works

<div align="center">

### 🏗️ **Computer Vision Pipeline Overview**

</div>

Our sophisticated system processes images through multiple intelligent stages:

<div align="center">

```mermaid
graph TD
    A[Input Image] --> B[Pre-processing]
    B --> C[Noise Removal]
    C --> D[Watershed Segmentation]
    D --> E[Grain Counting]
    E --> F[Result Visualization]
    F --> G[Final Output]
```

</div>

| Stage | Process | Technology |
|-------|---------|------------|
| **Pre-processing** | Contrast enhancement & segmentation | OpenCV image processing |
| **Noise Removal** | Morphological operations | Erosion, opening, dilation |
| **Watershed** | Advanced grain separation | Distance transform + markers |
| **Counting** | Intelligent grain enumeration | Contour detection + centroid |
| **Visualization** | Result presentation | Annotation + statistics |

---

## 🤝 Contributing

<div align="center">

### 💡 **Help Improve Agricultural Technology!**

[![Contributors Welcome](https://img.shields.io/badge/Contributors-Welcome-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mushrum-mmb/Simple_Rice_Detection/issues)

</div>

Join our mission to advance agricultural computer vision! Here's how you can contribute:

- **Report bugs** and suggest improvements
- **Test with different rice varieties** and share results
- **Improve documentation** and add tutorials
- **Optimize algorithms** for better accuracy
- **Add support for other grains** (wheat, barley, etc.)
- **Star the repo** to show support!

### 🌟 **Ideas for Enhancement:**
- Mobile app development
- Integration with IoT devices
- Batch processing capabilities
- Quality assessment features
- Multi-language support

---

## 📜 License

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

</div>
