# CSEMOTIONS: High-Quality Mandarin Emotional Speech Dataset

[Paper](https://huggingface.co/papers/2508.02038) | [Code](https://github.com/AIDC-AI/Marco-Voice)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**CSEMOTIONS** is a high-quality Mandarin emotional speech dataset designed for expressive speech synthesis, emotion recognition, and voice cloning research. The dataset contains studio-quality recordings from six professional voice actors across seven carefully curated emotional categories, supporting research in controllable and natural language speech generation.


## Dataset Summary

- **Name:** CSEMOTIONS
- **Total Duration:** ~10 hours
- **Speakers:** 10 (5 male, 5 female) native Mandarin speakers, all professional voice actors
- **Emotions:** Neutral, Happy, Angry, Sad, Surprise, Playfulness, Fearful
- **Language:** Mandarin Chinese
- **Sampling Rate:** 48kHz, 24-bit PCM
- **Recording Setting:** Professional studio environment
- **Evaluation Prompts:** 100 per emotion, in both English and Chinese

## Dataset Structure

Each data sample includes:

- **audio**: The speech waveform (48kHz, 24-bit, WAV)
- **transcript**: The transcribed sentence in Mandarin
- **emotion**: One of {Neutral, Happy, Angry, Sad, Surprise, Playfulness, Fearful}
- **speaker_id**: An anonymized speaker identifier (e.g., `S01`)
- **gender**: Male/Female
- **prompt_id**: Unique identifier for each utterance


## Intended Uses

CSEMOTIONS is intended for:

- Expressive text-to-speech (TTS) and voice cloning systems
- Speech emotion recognition (SER) research
- Cross-lingual and cross-emotional synthesis experiments
- Benchmarking emotion transfer or disentanglement models

## Dataset Details

| Property                | Value                                 |
|-------------------------|---------------------------------------|
| Total audio hours       | ~10                                   |
| Number of speakers      | 6 (3♂, 3♀, anonymized IDs)           |
| Emotions                | Neutral, Happy, Angry, Sad, Surprise, Playfulness, Fearful |
| Language                | Mandarin Chinese                      |
| Format                  | WAV, mono, 48kHz/24bit                |
| Studio quality          | Yes                                   |

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

## Download and Usage

To use CSEMOTIONS with [🤗 Datasets](https://huggingface.co/docs/datasets):

```python
from datasets import load_dataset

dataset = load_dataset("AIDC-AI/CSEMOTIONS")
```

## Acknowledgements

We would like to thank our professional voice actors and the recording studio staff for their contributions.


## License

The project is licensed under the Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0, SPDX-License-identifier: Apache-2.0).

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

## Disclaimer
                                     
We used compliance checking algorithms during the training process, to ensure the compliance of the trained model and dataset to the best of our ability. Due to the complexity of the data and the diversity of language model usage scenarios, we cannot guarantee that the dataset is completely free of copyright issues or improper content. If you believe anything infringes on your rights or contains improper content, please contact us, and we will promptly address the matter.
                                     
---
