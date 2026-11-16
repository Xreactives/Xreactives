<div align="center">

# Ronny Lim

**Machine Learning & Computer Vision Engineer**  
*Building end-to-end perception, custom OCR, semantic search, and real-time inference systems—from dataset curation and PyTorch model training to quantized ONNX Runtime and CTranslate2 deployment.*

[![GitHub](https://img.shields.io/badge/GitHub-Xreactives-181717?style=flat-square&logo=github)](https://github.com/Xreactives)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Yreactives-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Yreactives)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ronny--xreact-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ronny-xreact)
[![Email](https://img.shields.io/badge/Email-zreactives@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:zreactives@gmail.com)

</div>

---

### What I Build

I specialize in practical **Computer Vision**, **Custom OCR**, and **Applied NLP**—taking deep learning models from peer-reviewed research and active-learning dataset curation all the way to low-latency production runtimes (`ONNX Runtime`, `CTranslate2`, `FastAPI`, and `Streamlit`).

* 📄 **Published Research:** *“Enhanced Convolutional Recurrent Neural Network for Vertical Japanese Text Recognition”* — **IJECSA (2025)**
* 🎓 **Education & Credentials:** B.Sc. in Computer Science (STMIK Pontianak) • **CertNexus CAIA** • **IELTS 6.5**
* 📍 **Location & Availability:** Pontianak, Indonesia • Open to **Singapore Relocation (EP / S Pass)** & **Remote**

---

### Featured Project

#### 🈁 [Real-Time Japanese Visual Novel Translator](https://github.com/Xreactives/realtime-japanese-visual-novel-translator)
> **Offline, zero-configuration screen translation overlay (~300–450 ms end-to-end latency)** unifying a custom `1280px` YOLO UI/text detector (`99% mAP@50`), an adapted version of my IJECSA-published CRNN + CTC Japanese OCR architecture, SudachiPy morphological normalization, and Sugoi V4 neural machine translation.

<!-- Uncomment once you upload demo.gif to this profile repo or link it from your project repo:
<div align="center">
  <img src="https://raw.githubusercontent.com/Xreactives/realtime-japanese-visual-novel-translator/main/assets/demo.gif" alt="Real-Time Visual Novel Translator Demo" width="760" />
</div>
-->

| Layer | Engineering Highlights |
| :--- | :--- |
| **1. Data & Active Learning** | Engineered a **6-stage data curation pipeline**: automated bounding-box cropping, perceptual-hash deduplication, silver prelabeling, a custom Tkinter audit GUI, synthetic Japanese font augmentation (`TRDG`), and CTC loss-based noisy-label mining. |
| **2. Vision & OCR Models** | Unified my custom **YOLO UI/text detector** (`99% mAP@50`, filtering logos, sprites, and toolbars) with my **IJECSA-published CRNN (`CNN + LSTM + MultiheadAttention`)** Japanese OCR recognizer adapted onto curated + synthetic game typography. |
| **3. Quantized Runtime** | Exported PyTorch vision models (`.pt` / `.pth`) to **ONNX Runtime** with dynamic cuBLAS probing and automatic CPU INT8 fallback, alongside **Sugoi V4 (`CTranslate2`)** FP16/INT8 offline translation. |
| **4. OS-Level Overlay** | Eliminated screen-capture feedback loops and coordinate drift on Windows using `WDA_EXCLUDEFROMCAPTURE`, live bounding-box masking, and Per-Monitor DPI awareness. |

---

### More Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| [**Visual Novel Text Detector**](https://github.com/Xreactives/visual-novel-text-detector) | Visual novel UI text region detector (**99% mAP@50 at 2 ms**) and OCR engine whose trained `.pt` weights power the detection stage of the Real-Time VN Translator. | `Ultralytics YOLO26n` `EasyOCR` `OpenCV` |
| [**Japanese CRNN Text Recognition**](https://github.com/Xreactives/japanese-crnn-text-recognition) | Undergraduate thesis & IJECSA-published Japanese OCR architecture (`CNN + LSTM + MultiheadAttention`) trained on the ETL dataset—later adapted as the OCR engine in the Real-Time VN Translator. | `PyTorch` `CRNN` `Attention` `Tkinter` |
| [**AI Image Detector**](https://github.com/Xreactives/ai-image-detector) | Full-stack synthetic image classification service pairing a low-latency REST inference backend with an interactive web interface. | `PyTorch` `FastAPI` `Streamlit` `Docker` |
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
  <sub><i>Open to Machine Learning, Computer Vision, and AI Engineering opportunities in Singapore & Remote.</i></sub>
</div>
