# CTG 후처리 모듈을 활용한 Zero-Shot Open-Vocabulary Segmentation 개선 연구

본 저장소는 Contrastive Top-K Guidance(CTG) 후처리 모듈을 활용하여  
Zero-Shot 환경에서 Open-Vocabulary Segmentation 성능을 향상시키는 실험 코드와 재구현 코드를 포함합니다.

---

## 📦 Installation

아래 명령어로 저장소를 클론하고 서브모듈을 포함해 환경을 설치할 수 있습니다.

```bash
!git clone --recurse-submodules https://github.com/AI-AYJ/AI-AYJ-CTG.git
%cd AI-AYJ-CTG/GEM
!pip install -e .


## 📋 Requirements

다음 라이브러리들이 필요합니다.

- torch >= 1.9.0  
- torchvision  
- regex  
- ftfy  
- tqdm  
- huggingface_hub  
- sentencepiece  
- protobuf  
- timm  
- einops  
- open_clip_torch <= 2.23.0  
- opencv-python  
- matplotlib  
- numpy  
- requests  
- torchmetrics  

---

## 📂 Datasets

본 연구에서는 다음 세 가지 데이터셋을 사용했습니다.

### **Pascal VOC**
다운로드:  
https://host.robots.ox.ac.uk/pascal/VOC/

### **ADE20K**
다운로드:  
https://groups.csail.mit.edu/vision/datasets/ADE20K/

### **OpenImages V7**
다운로드:  
https://storage.googleapis.com/openimages/web/download.html

---

## 🧪 Run on Pascal VOC

아래 노트북을 실행하여 Pascal VOC 실험을 재현할 수 있습니다.

- `PascalVOC_재구현_코드.ipynb`
- `PascalVOC_+CTG_코드.ipynb`
- `PascalVOC+heatmap_코드.ipynb`

---

## 🧪 Run on ADE20K

- `ADE20K_재구현_코드.ipynb`
- `ADE20K+CTG_코드.ipynb`
- `ADE20K+heatmap코드.ipynb`

---

## 🧪 Run on OpenImages V7

- `Openimagesv7_재구현_코드.ipynb`
- `openimagesv7+CTG_코드.ipynb`

---
