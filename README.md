<div align="center">

# Ronny Lim

**Machine Learning & Computer Vision Engineer**  
*Building end-to-end perception, custom OCR, semantic search, and real-time inference systems—from dataset curation and PyTorch model training to quantized ONNX Runtime and CTranslate2 deployment.*

[![GitHub](https://img.shields.io/badge/GitHub-Xreactives-181717?style=flat-square&logo=github)](https://github.com/Xreactives)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Profile-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Yreactives)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ronny-xreact)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:zreactives@gmail.com)

</div>

---

### What I Build

I specialize in practical **Computer Vision**, **Custom OCR**, and **Applied NLP**—taking models from raw data curation and PyTorch training all the way to low-latency production runtimes (`ONNX Runtime`, `CTranslate2`, `FastAPI`, and `Streamlit`).

---

### Featured Project

#### 🀄 [Real-Time Japanese Visual Novel Translator](https://github.com/Xreactives/realtime-japanese-visual-novel-translator)
> **Offline, zero-configuration screen translation overlay (~300–450 ms end-to-end latency)** combining a `1280px` full-screen YOLO UI/text detector, a custom CRNN + CTC Japanese OCR recognizer, SudachiPy morphological normalization, and Sugoi V4 neural machine translation.

| Layer | Engineering Highlights |
| :--- | :--- |
| **1. Data & Active Learning** | Engineered a **6-stage data curation pipeline**: automated bounding-box cropping, perceptual-hash deduplication, silver prelabeling, a custom Tkinter audit GUI, synthetic Japanese font augmentation (TRDG), and CTC loss-based noisy-label mining. |
| **2. Vision & OCR Models** | Trained a full-screen `1280px` YOLO detector (filtering logos, sprites, and toolbars) paired with a custom CRNN + CTC Japanese text recognizer trained on curated + synthetic game typography. |
| **3. Quantized Runtime** | Exported vision models to **ONNX Runtime** with dynamic cuBLAS probing and automatic CPU INT8 fallback, alongside **Sugoi V4 (CTranslate2)** FP16/INT8 offline translation. |
| **4. OS-Level Overlay** | Eliminated screen-capture feedback loops and coordinate drift on Windows using `WDA_EXCLUDEFROMCAPTURE`, live bounding-box masking, and Per-Monitor DPI awareness. |

---

### More Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| [**Visual Novel Text Detector**](https://github.com/Xreactives/visual-novel-text-detector) | Visual novel UI text region detector and OCR engine achieving **99% mAP@50 at 2 ms** inference speed. | `Ultralytics YOLO26n` `EasyOCR` `OpenCV` |
| [**Japanese CRNN Text Recognition**](https://github.com/Xreactives/japanese-crnn-text-recognition) | Custom Japanese text recognizer (`CNN + LSTM + MultiheadAttention`) trained on the **ETL dataset** with an on-screen translator GUI. | `PyTorch` `CRNN` `Attention` `Tkinter` |
| [**AI Image Detector**](https://github.com/Xreactives/ai-image-detector) | Full-stack synthetic image classification service with a REST inference API and interactive web interface. | `PyTorch` `FastAPI` `Streamlit` |
| [**QuestMatch AI**](https://github.com/Xreactives/questmatch-ai) | Semantic video game recommendation engine retrieving titles via dense text embeddings and cosine similarity. | `Sentence Transformers` `NLP` `Streamlit` |

---

### Technical Stack

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>👁️ Computer Vision & OCR</strong><br><br>
      • PyTorch & Torchvision<br>
      • Ultralytics YOLO<br>
      • Custom CRNN (CTC / Attention)<br>
      • OpenCV & Pillow<br>
      • EasyOCR & TRDG
    </td>
    <td valign="top" width="33%">
      <strong>🧠 NLP & Inference</strong><br><br>
      • ONNX Runtime (CUDA / CPU)<br>
      • CTranslate2 (FP16 / INT8)<br>
      • Sentence Transformers<br>
      • SudachiPy & Hugging Face<br>
      • Quantization & Graph Export
    </td>
    <td valign="top" width="33%">
      <strong>🛠️ Backend & Deployment</strong><br><br>
      • Python, NumPy, Pandas<br>
      • FastAPI & REST APIs<br>
      • Streamlit & Tkinter GUIs<br>
      • Label Studio & Active Learning<br>
      • Docker, Render & Git
    </td>
  </tr>
</table>

---

<div align="center">
  <sub><i>Open to Machine Learning, Computer Vision, and AI Engineering opportunities.</i></sub>
</div>
