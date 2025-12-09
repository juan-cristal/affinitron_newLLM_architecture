# Affinitron

Affinitron is a tool that analyzes text to build spectral signatures of words based on their context and usage patterns, and synthesizes them as audio.

## Features

- **Text Analysis**: Tokenization and sliding-window co-occurrence analysis.
- **Spectral Signatures**: Estimates partials and amplitudes for words.
- **Tempo Estimation**: Analyzes word frequency over simulated time-slices.
- **Affinity Graph**: Builds a graph of word relationships based on harmonic overlap and tempo compatibility.
- **Audio Synthesis**: Hear the "sound" of words based on their calculated signatures.

## Installation

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Open `affinitron.ipynb` in Jupyter Notebook or JupyterLab to run the analysis and hear the audio synthesis.

```bash
jupyter notebook affinitron.ipynb
```

## License

MIT
