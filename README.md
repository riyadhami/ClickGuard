# ClickGuard: A Trustworthy Adaptive Fusion Framework for Clickbait Detection
<p align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
</p>

ClickGuard is a deep learning-based framework designed to accurately detect clickbait headlines and enhance online content credibility. By integrating **syntactic** and **semantic** features through a **Syntactic-Semantic Adaptive Fusion Block (SSAFB)** and leveraging a **hybrid CNN-BiLSTM architecture**, ClickGuard achieves high accuracy in classifying clickbait and non-clickbait content.

## 📝 Key Features

- Combines **BERT embeddings** with structural language features through a **Syntactic-Semantic Adaptive Fusion Block (SSAFB)** to better understand the context and structure of headlines.
- Uses a **hybrid CNN-BiLSTM architecture** to capture both local patterns and long-range dependencies in text, improving the model's ability to detect subtle clickbait cues.
- Achieves **96.93% accuracy** on multiple datasets while ensuring transparency and reliability through explainability tools like **LIME** and **Permutation Feature Importance (PFI)**.


## 📊 Datasets
ClickGuard is evaluated on three publicly available datasets:
1. **Dataset 1:** News headlines from platforms like BuzzFeed, Upworthy, and The Guardian.
2. **Webis Clickbait Corpus 2017**
3. **Clickbait Challenge 2017 Dataset**

For more details on the methodology, experiments, and results, please refer to the [paper](#).

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE.md) file for details.
