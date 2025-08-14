<p align="center">
  <img src="assets/marco-voice-logo-3.png" alt="Marco-Voice Ecosystem" width="200">
</p>

# Marco-Voice: A Unified Framework for Expressive Speech Synthesis with Voice Cloning

<p align="center">🎧 Empowering Natural Human-Computer Interaction through Expressive Speech Synthesis 🤗</p>

<div align="center">
<img src="https://img.shields.io/badge/License-Apache%202.0-green.svg" alt="License">
<img src="https://img.shields.io/github/issues/AIDC-AI/Marco-Voice?color=red" alt="Open Issues">
<img src="https://img.shields.io/github/issues-closed/AIDC-AI/Marco-Voice?color=green" alt="Closed Issues">
<img src="https://img.shields.io/github/stars/AIDC-AI/Marco-Voice?color=yellow" alt="Stars">
<img src="https://img.shields.io/badge/python-3.10-purple.svg" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-2.0-blue.svg" alt="PyTorch"> 
<!-- [![Paper](https://img.shields.io/badge/Paper-PDF-%23B31B1B)](https://arxiv.org/abs/2508.02038) -->
<!-- [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE) -->
<!-- [![HuggingFace Dataset](https://img.shields.io/badge/Dataset-HuggingFace-orange)](https://huggingface.co/datasets/AIDC-AI/CSEMOTIONS) -->
<!-- ![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue) -->
<!-- ![PyTorch 2.0+](https://img.shields.io/badge/PyTorch-2.0%2B-red) -->

</div>
<p align="center"></p>

<div align="center">

<!-- **Affiliations:** -->

⭐ _**AI Business**_ ⭐

[_**Alibaba International Digital Commerce**_](https://aidc-ai.com)

:octocat: [**Github**](https://github.com/AIDC-AI/Marco-Voice)  🤗  [**Hugging Face**](https://huggingface.co/datasets/AIDC-AI/CSEMOTIONS) 📝  [**Paper**](https://arxiv.org/abs/2508.02038) 🧑‍💻 [**Model**]() 🗂️  [**Data**](https://github.com/AIDC-AI/Marco-Voice/tree/main/Dataset) 📽️  [**Demo**]()

</div>

## 📖 Overview

<!-- > **Voice Cloning  · Emotion Control 😄**
 -->

🎯 This project presents a multifunctional speech synthesis system that integrates **voice cloning**, **emotion control**, and **cross-lingual synthesis** within a unified framework. Our goal is to address longstanding challenges in achieving highly expressive, controllable, and natural speech generation that faithfully preserves speaker identity across diverse linguistic and emotional contexts.

<div align="center">
<img src="assets/marco_vocie_fig_v3.jpeg" alt="System Architecture" width="850">
</div>

Our approach introduces an effective speaker-emotion disentanglement mechanism with in-batch contrastive learning, enabling independent manipulation of speaker identity and eemotional style, as well as rotational emotional embedding integration method for smooth emotion control. To support comprehensive training and evaluation, we construct CSEMOTIONS, a high-quality emotional speech dataset containing 10 hours of Mandarin speech from six professional speakers across seven emotional categories. Extensive experiments demonstrate that our system, Marco-Voice, achieves substantial improvements in both objective and subjective metrics. Comprehensive evaluations and analysis were conducted, results show that Marco-Voice delivers competitive performance in terms of speech clarity and emotional richness, representing a substantial advance in the field of expressive neural speech synthesis.

## Audio Samples

Below are sample outputs from our TTS system demonstrating different emotional expressions, with three different speakers:

### Neutral

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">
    
[Speaker001_Neutral_0.webm](https://github.com/user-attachments/assets/2750293e-f6e6-4255-80ba-3c1e500f675e)

</td>
<td align="center">
    
[Speaker002_Neutral_0.webm](https://github.com/user-attachments/assets/5e2dc40f-922f-46f5-a8f1-3238980ccc3a)

</td>
<td align="center">
    
[Speaker003_Neutral_0.webm](https://github.com/user-attachments/assets/caaf9a1f-96e3-473d-af28-a935622d0fac)

</td>
</tr>
</table>

**Natural, conversational tone**

---

### Happy

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Happy_0.webm](https://github.com/user-attachments/assets/64f53e6b-566e-4836-9863-349fe7a3ae88)

</td>
<td align="center">

[Speaker002_Happy_0.webm](https://github.com/user-attachments/assets/0a6caeca-9aaa-491b-b719-fc9c1db7a885)

</td>
<td align="center">

[Speaker003_Happy_0.webm](https://github.com/user-attachments/assets/6592d4d7-644e-4966-a06a-341d2d85ed70)

</td>
</tr>
</table>

**Cheerful and upbeat expression**

---

### Sad

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Sad_0.webm](https://github.com/user-attachments/assets/5d03d07b-7131-4f95-a23d-937efe462644)

</td>
<td align="center">

[Speaker002_Sad_0.webm](https://github.com/user-attachments/assets/f34e94d7-c031-4ce4-9741-07250d825bae)

</td>
<td align="center">

[Speaker003_Sad_0.webm](https://github.com/user-attachments/assets/6ef30c36-09fc-4fb0-a8c4-2c9ce32d6173)

</td>
</tr>
</table>

**Melancholic and subdued tone**

---

### Angry

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Angry_0.webm](https://github.com/user-attachments/assets/5c470ef2-2e75-4acd-af40-920260917d0d)

</td>
<td align="center">

[Speaker002_Angry_0.webm](https://github.com/user-attachments/assets/b9385c6f-d0ac-437f-8cdb-1d16de9179f5)

</td>
<td align="center">

[Speaker003_Angry_0.webm](https://github.com/user-attachments/assets/7fff8327-b0f1-457d-822c-b709910da502)

</td>
</tr>
</table>

**Intense and forceful delivery**

---

### Fearful

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Fearful_0.webm](https://github.com/user-attachments/assets/4491ba91-fa4f-4414-859f-8e4115b5d0d3)

</td>
<td align="center">

[Speaker002_Fearful_0.webm](https://github.com/user-attachments/assets/747c9754-a2ba-4e2f-8493-ae663949e52e)

</td>
<td align="center">

[Speaker003_Fearful_0.webm](https://github.com/user-attachments/assets/f9903704-ea55-4783-9928-8cd09d6a16ad)

</td>
</tr>
</table>

**Anxious and trembling voice**

---

### Surprise

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Surprise_0.webm](https://github.com/user-attachments/assets/26b69322-b4e3-455c-aedd-323b5d72319e)

</td>
<td align="center">

[Speaker002_Surprise_0.webm](https://github.com/user-attachments/assets/c056780a-40a2-452c-a314-391889fd6a33)

</td>
<td align="center">

[Speaker003_Surprise_0.webm](https://github.com/user-attachments/assets/4b63436f-efac-4cf1-b817-e6fbc0ec90c7)

</td>
</tr>
</table>

**Excited and astonished expression**

---

### Playfulness

<table>
<tr>
<td align="center"><b>Speaker001</b></td>
<td align="center"><b>Speaker002</b></td>
<td align="center"><b>Speaker003</b></td>
</tr>
<tr>
<td align="center">

[Speaker001_Playfulness_0.webm](https://github.com/user-attachments/assets/4afae8fa-5efc-4adc-9e3c-e10c0bd873b8)

</td>
<td align="center">

[Speaker002_Playfulness_0.webm](https://github.com/user-attachments/assets/82ed45b9-939c-4345-8ce1-62b92ec90c6e)

</td>
<td align="center">

[Speaker003_Playfulness_0.webm](https://github.com/user-attachments/assets/793108c5-28d0-4851-a0b1-2008de4522da)

</td>
</tr>
</table>

**Playful and teasing tone**

---

We welcome any suggestions from the community to our project and we will continue to improve this project. 

我们欢迎社区对我们的项目提出任何建议，我们将持续改进和提升这个项目。

## 📌 Main Contributions

### 1. Marco-Voice Model:
- We develop a speaker-emotion disentanglement mechanism that separates speaker identity from emotional expression, enabling independent control over voice cloning and emotional style. We also proposed to employ in-batch contrastive learning to further disentangle speaker identity with emotional style feature.
-  We implement a rotational emotion embedding integration method to obtain emotional embeddings based on rotational distance from neutral embeddings. Finally, we introduce a cross-attention mechanism that better integrates emotional information with linguistic content throughout the generation process.
### 2. CSEMOTIONS Dataset:
- We construct CSEMOTIONS, a high-quality emotional speech dataset containing approximately 10.2 hours of Mandarin speech from six professional native speakers (three male, three female), all with extensive voice acting experience. The dataset covers seven distinct emotional categories. All recordings were made in professional studios to ensure high audio quality and consistent emotional expression.
- We also develop 100 evaluation prompts for each emotion class across both existing datasets and CSEMOTIONS in English and Chinese, enabling thorough and standard assessment of emotional synthesis performance across all supported emotion categories.


## 📁 Datasets

### CSEMOTIONS Dataset
### Specifications

| Property                | Specification                                      |
| ----------------------- | -------------------------------------------------- |
| Duration                | ~10 hours                                          |
| Speakers                | 10 professionals (5♂, 5♀)                        |
| Emotions                | Neutral, Happy, Angry, Sad, Surprise, Playfulness, Fearful |
| Languages               | Mandarin                                           |
| Sampling Rate           | 48kHz/16bits                                        |
| Recording Environment   | Professional studio                                |
| Evaluation Prompts      | 100 per emotion (EN/ZH)                            |

### Emotion Distribution

| Label    | Duration | Sentences |
| -------- | -------- | --------- |
| Sad      | 1.73h    | 546       |
| Angry    | 1.43h    | 769       |
| Happy    | 1.51h    | 603       |
| Surprise | 1.25h    | 508       |
| Fearful  | 1.92h    | 623       |
| Playfulness   | 1.23h    | 621       |
| Neutral  | 1.14h    | 490       |
| **Total**| **10.24h**| **4160**  |


### Public Datasets Integration

| Dataset      | Hours | Speakers | Languages | Emotion Types |
|--------------|-------|----------|-----------|---------------|
| ESD          | 29    | 20       | EN/ZH      | 5             |
| LibriTTS     | 585+  | 2,456    | EN         | Neutral       |
| AISHELL-3    | 85    | 218      | ZH         | Neutral       |

## 🛠️ Implementation Details

### Training Configuration
```yaml
hardware: 8× NVIDIA A100 (80GB)
optimizer: Adam (lr=1e-5, β1=0.9, β2=0.98)
scheduler: Cosine decay with warmup
batch_size: 32 per GPU
loss_weights:
  orthogonality: 0.1
  contrastive: 0.5
  TTS: 1.0 (recon + spectral + adversarial)
```


## 🚀 Getting Started

### Installation
```bash
conda create -n marco python=3.8
conda activate marco
git clone https://github.com/yourlab/marco-voice.git
cd marco-voice
pip install -r requirements.txt
```


### Training & Finetuning
```python
# Prepare Dataset
# Example data processing scripts, and you may tailor your own one along with your own data formula, you should have utt2spk, spk2utt, wav.scp and text at the end
python Utils/prepare_data.py data_path path_to_save # path to data, include *.wav and *.txt
# prepare open source data
python Marco-Voice/Utils/prepare_opensource_data.py json_file_path

# Once your datasets are prepared, you can start the training process.
# training basic model
bash Marco-Voice/Training/run_training.sh
# training emosphere model 
bash Marco-Voice/Training/run_training_emosphere.sh

# training modified  f5-tts with emosphere， Configure the environment according to f5-tts

cd Marco-Voice/Models/F5-TTS
#prepareing data , data format, wav.scp , content should look like : wav_path:text
python src/f5_tts/train/datasets/prepare_csv_wavs.py inp_dir outp_dir #
accelerate launch src/f5_tts/train/train.py --config-name src/f5_tts/configs/F5TTS_Base_train.yaml

# for training seamlessm4t ,you need to change the data path in training.py file

bash Marco-Voice/Training/train.sh seamless
```
### Evaluation

#### 🎯 Objective Evaluation

We use the following metrics for objective evaluation:

  - **Emotion Classification Accuracy (ECA)**: Measures preservation of emotional content.
  - **Word Error Rate (WER)**: Measures transcription accuracy.
  - **Speaker Similarity (SIM)**: Quantifies speaker identity preservation.
  - **DNS-MOS**: Evaluates speech quality (0-5 scale).

#### 🛠️ Tools & Implementation

#### 1. Emotion Classification Accuracy (ECA)
- **Tool**: [`emotion2vec`](https://huggingface.co/emotion2vec/emotion2vec_plus_large), as implemented in [`seed-tts-eval`](https://github.com/BytedanceSpeech/seed-tts-eval?tab=readme-ov-file#metrics)
- **Description**: Measures the accuracy of emotion recognition in synthesized or processed speech, comparing predicted emotions to ground-truth labels.
- **Method**:
    - Extract emotion embeddings using the fine-tuned `emotion2vec` model.
    - Classify emotions for both reference and test utterances.
    - Compute accuracy or F1-score based on alignment with reference emotions.
- **Language Support**: Primarily designed for English; performance for other languages may vary depending on model coverage.

#### 2. Word Error Rate (WER)
- **English ASR**: `Whisper-large-v3` (HuggingFace)
- **Mandarin ASR**: `Paraformer-zh` (ModelScope)
- **Supported Languages**:
    - Common: English (en), Mandarin (zh)
    - Minor languages (if compatible ASR models are available)
- **Error Types**: Insertion, deletion, substitution

#### 3. Speaker Similarity (SIM)
- **Primary Tool**: [`SpeechBrain`](https://speechbrain.github.io/) (higher reliability)
- **Alternative**: [`ESPNet`](https://espnet.github.io/) (more features)
- **Method**:
    - Extract speaker embeddings using verification models
    - Compute cosine similarity between test utterances and reference samples

#### 4. DNS-MOS
- **Tool**: [DNSMOS](https://github.com/microsoft/DNS-Challenge.git)
- **Output**: MOS score (0–5) for speech quality
- **Language Support**: Universal (no language-specific training required)


#### Input Examples

```json
{
  "uttr_001": {
    "text": "今天天气真好",
    "audio_path": "data/audio/happy_001.wav",
    "style_label": "happy",
    "language_id":  'ch',
  },
  "uttr_002": {
    "text": "这让我很失望",
    "audio_path": "data/audio/sad_005.wav",
    "style_label": "sad",
    "language_id":  'ch'
  }
} 

bash Evaluation/cal_metrix.sh path_to_json_file path_to_output
```
📌 Notes
  Prefer SpeechBrain over ESPNet for SIM due to stability
  Ensure audio paths are absolute or relative to the working directory
  Use language_id to auto-select ASR models
  

### Basic Synthesis
```python
from Models.marco_voice.cosyvoice_rodis.cli.cosyvoice import CosyVoice
from Models.marco_voice.cosyvoice_emosphere.cli.cosyvoice import CosyVoice as cosy_emosphere

from Models.marco_voice.cosyvoice_rodis.utils.file_utils import load_wav

# Load pre-trained model
model = CosyVoice('trained_model/v4', load_jit=False, load_onnx=False, fp16=False)
emo = {"伤心": "Sad", "恐惧":"fearful", "快乐": "Happy", "惊喜": "Surprise", "生气": "Angry", "戏谑":"jolliest"} 
prompt_speech_16k = load_wav("your_audio_path/exam.wav", 16000)
emo_type="开心"
if emo_type in ["伤心", "恐惧"]:
    emotion_info = torch.load("./assets/emotion_info.pt")["zhu"][emo.get(emo_type)]
else:
    emotion_info = torch.load("./assets/emotion_info.pt")["song"][emo.get(emo_type)]
# Voice cloning with discrete emotion
for i, j in enumerate(model.synthesize(
    text="今天的天气真不错，我们出去散步吧！",
    prompt_text="",
    reference_speech=prompt_speech_16k,
    emo_type=emo_type,
    emotion_embedding=emotion_info
)):
  torchaudio.save('emotional_{}.wav'.format(emo_type), j['tts_speech'], 22050)

# Continuous emotion control
model_emosphere = cosy_emosphere('trained_model/v5', load_jit=False, load_onnx=False, fp16=False)

for i, j in enumerate(model_emosphere.synthesize(
    text="今天的天气真不错，我们出去散步吧！",
    prompt_text="",
    reference_speech=prompt_speech_16k,
    emotion_embedding=emotion_info,
    low_level_emo_embedding=[0.1, 0.4, 0.5]
)):
  torchaudio.save('emosphere_{}.wav'.format(emo_type), j['tts_speech'], 22050)



### More Features
# Cross-lingual emotion transfer
for i, j in enumerate(model.synthesize(
    text="hello, i'm a speech synthesis model, how are you today? ",
    prompt_text="",
    reference_speech=prompt_speech_16k,
    emo_type=emo_type,
    emotion_embedding=emotion_info
)):
  torchaudio.save('emosphere_ross_lingual_{}.wav'.format(emo_type), j['tts_speech'], 22050)
```

  

## 📊 Benchmark Performance

We conducted a blind human evaluation with four annotators. The Likert scale ranges from 1 to 5 for all metrics, except for Speaker Similarity, which is rated on a scale from 0 to 1.

### Voice Cloning Evaluation
| Metric               | CosyVoice1 | CosyVoice2 | Marco-Voice |
|----------------------|------------|------------|-------------|
| Speech Clarity       | 3.000      | 3.770      | **4.545**   |
| Rhythm & Speed       | 3.175      | 4.090      | **4.290**   |
| Naturalness          | 3.225      | 3.150      | **4.205**   |
| Overall Satisfaction | 2.825      | 3.330      | **4.430**   |
| Speaker Similarity   | 0.700      | 0.605      | **0.8275**  |

### Emotional Speech Generation Evaluation
| Metric               | CosyVoice2 | Marco-Voice |
|----------------------|------------|-------------|
| Speech Clarity       | 3.770      | **4.545**   |
| Emotional Expression | 3.240      | **4.225**   |
| Rhythm & Speed       | 4.090      | **4.290**   |
| Naturalness          | 3.150      | **4.205**   |
| Overall Satisfaction | 3.330      | **4.430**   |

### Direct Comparison (A/B Tests)
| Compared System | Marco-Voice Win Rate |
|-----------------|----------------------|
| CosyVoice1      | 60% (12/20)          |
| CosyVoice2      | 65% (13/20)          |

### Objective Metrics Analysis

#### LibriTTS Dataset (English)
| System           | WER ↓  | SS (SpeechBrain) ↑ | SS (ERes2Net) ↑ | Del&Ins ↓ | Sub ↓  | DNS-MOS ↑ |
|------------------|--------|--------------------|------------------|-----------|--------|-----------|
| CosyVoice1       | 12.1   | 64.1               | 80.1             | 413       | 251    | 3.899     |
| CosyVoice1*      | 58.4   | 61.3               | 64.2             | 2437      | 2040   | 3.879     |
| Marco-Voice   | **11.4** | 63.2             | 74.3             | **395**   | **242**| 3.860     |

#### AISHELL-3 Dataset (Mandarin)
| System           | WER ↓  | SS (SpeechBrain) ↑ | SS (ERes2Net) ↑ | Del&Ins ↓ | Sub ↓  | DNS-MOS ↑ |
|------------------|--------|--------------------|------------------|-----------|--------|-----------|
| CosyVoice1       | **3.0** | **10.7**             | 73.5             | **11.0**  | **97.0**| 3.673     |
| CosyVoice1*      | 23.3   | 10.6               | 54.5             | 170       | 674    | **3.761**     |
| Marco-Voice   | 17.6   | 10.4              | **73.8**         | 218       | 471    | 3.687     |

*Implementation Notes:*  
- **CosyVoice1*** indicates continued training of the base model on the same dataset used by Marco-Voice, continual SFT on base model would naturally incur general performance degradation:  
  - Worse WER (58.4 vs 12.1 in LibriTTS, 23.3 vs 3.0 in AISHELL)  
  - Speaker similarity preservation challenges (SS-ERes2Net drops to 64.2/54.5 from 80.1/73.5)  
- Marco-Voice achieves better WER (11.4 vs 58.4) and speaker similarity (74.3 vs 64.2) than CosyVoice1* in LibriTTS despite added emotional control capabilities

## 📈 Analysis Studies

### Duration Impact on Emotion Recognition
<img src="assets/duration_impact.png" alt="Duration Impact" width="600">


### Gender Bias Analysis
<img src="assets/gender_performance_comparison.png" alt="Gender Analysis" width="600">



## 📜 Citation
```bibtex
@misc{tian2025marcovoicetechnicalreport,
      title={Marco-Voice Technical Report}, 
      author={Fengping Tian and Chenyang Lyu and Xuanfan Ni and Haoqin Sun and Qingjuan Li and Zhiqiang Qian and Haijun Li and Longyue Wang and Zhao Xu and Weihua Luo and Kaifu Zhang},
      year={2025},
      eprint={2508.02038},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2508.02038}, 
}
```

## License
The project is licensed under the Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0, SPDX-License-identifier: Apache-2.0).

---
## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=AIDC-AI/Marco-Voice&type=Date)](https://star-history.com/#AIDC-AI/Marco-Voice&Date)
