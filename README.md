# Ghana NLP Notebooks

A curated collection of Jupyter notebooks for Natural Language Processing tasks focused on Ghanaian languages. This repository provides ready-to-use examples, tutorials, and research implementations for the Ghana NLP community.

---

## Available Notebooks

### Machine Translation (MT)
Notebooks for translating between Ghanaian languages and English/other languages.

| Notebook | Description | Open in Colab |
|----------|-------------|---------------|
| `twi_english_translation.ipynb` | Baseline Twi ↔ English translation using transformers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/mt/twi_english_translation.ipynb) |
| `multilingual_ghanaian_mt.ipynb` | Multilingual translation for 5+ Ghanaian languages | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/mt/multilingual_ghanaian_mt.ipynb) |
| `mt_evaluation_metrics.ipynb` | BLEU, chrF++, and custom evaluation for low-resource MT | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/mt/mt_evaluation_metrics.ipynb) |

### Text-to-Speech (TTS)
Notebooks for synthesizing speech from text in Ghanaian languages.

| Notebook | Description | Open in Colab |
|----------|-------------|---------------|
| `StyleTTS2_Twi_Finetune_working_final.ipynb` | Fine-tuning Style TTS English Base with a Twi Dataset | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/tts/StyleTTS2_Twi_Finetune_working_final.ipynb) |
| `ga_tts_data_preparation.ipynb` | Data preprocessing for Ga TTS dataset creation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/tts/ga_tts_data_preparation.ipynb) |
| `tts_evaluation.ipynb` | MOS evaluation and audio quality assessment | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/tts/tts_evaluation.ipynb) |

### Automatic Speech Recognition (ASR)
Notebooks for transcribing Ghanaian language audio to text.

| Notebook | Description | Open in Colab |
|----------|-------------|---------------|
| `twi_asr_whisper.ipynb` | Fine-tuning Whisper for Twi ASR with code-switching | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/asr/twi_asr_whisper.ipynb) |
| `multilingual_ghanaian_asr.ipynb` | Wav2Vec 2.0 for multiple Ghanaian languages | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/asr/multilingual_ghanaian_asr.ipynb) |
| `asr_data_augmentation.ipynb` | Audio augmentation techniques for low-resource ASR | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/asr/asr_data_augmentation.ipynb) |

### 🛠️ Data Generation
Notebooks for synthetic data generation in Ghanaian languages.

| Notebook | Description | Open in Colab |
|----------|-------------|---------------|
| `prestine_twi_dataset_generation.ipynb` | Generating high quality multifaceted Twi text for training models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/datagen/prestine_twi_dataset_generation.ipynb) |
| `dataset_statistics.ipynb` | Analyzing dataset distributions and quality | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/utils/dataset_statistics.ipynb) |

---

## Quick Start

### Running on Google Colab (Recommended)
Click any **"Open in Colab"** badge above to run the notebook immediately with free GPU/TPU access. No local setup required!

### Running Locally
```bash
# Clone the repository
git clone https://github.com/GhanaNLP/notebooks.git
cd notebooks

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter lab
```

---

## Contributing

We welcome contributions! To add a new notebook:

1. Create your notebook in the appropriate task folder (`mt/`, `tts/`, `asr/`, or `utils/`)
2. Ensure it has a clear description and runs end-to-end on Colab
3. Add the **Open in Colab** badge (see template below)
4. Update this README with the new entry
5. Submit a Pull Request

### Colab Badge Template
```markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhanaNLP/notebooks/blob/main/FOLDERNAME/FILENAME.ipynb)
```

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


**Made with ❤️ for Ghanaian languages**
