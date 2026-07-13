# RUHSOLD++

RUHSOLD++ is an extended version of the Roman Urdu Hate-Speech and Offensive Language Detection (RUHSOLD) dataset.

The dataset accompanies the paper **“Towards Explainable Hate Speech Detection in Roman Urdu,”** accepted at the **International Joint Conference on Neural Networks (IJCNN)**. The final publication details and citation will be added once the paper is available online.

## Dataset

RUHSOLD++ extends the original RUHSOLD dataset by:

* introducing hate-intensity labels on a five-point scale;
* adding samples collected after a temporal gap from the original dataset; and
* supporting the evaluation of hate-speech detection models over time.

For binary classification, the five-point intensity labels should be grouped as follows:

* **Class 0:** scores 1–2
* **Class 1:** scores 3–5

Please use the provided training, validation, and test splits when reporting results to support fair and reproducible comparisons.

## Original RUHSOLD Dataset

The original RUHSOLD dataset is available at:

https://github.com/haroonshakeel/roman_urdu_hate_speech

## Citation

Until then, please cite this dataset repository:

```bibtex
@inproceedings{towards_explainable_roman_urdu,
  title     = {Towards Explainable Hate Speech Detection in Roman Urdu},
  author    = {[Ubaid Azam*, Hammad Rizwan*, Faizad Ullah, Ali Faheem, Faisal Kamiran, Asim Karim]},
  booktitle = {Proceedings of the International Joint Conference on Neural Networks},
  year      = {2026},
  note      = {Accepted; publication forthcoming}
}
```

The citation will be updated after the official proceedings record and DOI become available.

## Responsible Use

This dataset contains hateful, offensive, abusive, and potentially distressing language. It is intended for research purposes only. Users should handle the data responsibly and avoid reproducing or amplifying harmful content outside legitimate research contexts.

