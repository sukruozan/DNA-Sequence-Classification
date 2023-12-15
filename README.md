# Project Name: DNA Sequence Classification

## Overview
ExampleProject is a comprehensive solution for [specific problem or functionality]. It's designed to be easy to use, yet powerful and flexible.

## Features
- Feature 1: Description
- Feature 2: Description
- Feature 3: Description

## Quick Start
```bash
git clone https://github.com/sukruozan/dna-sequence-classification.git
```
### Dataset Composition by Species

| Species    | Train Size | Test Size |
|------------|------------|-----------|
| Chimpanzee | 1345       | 337       |
| Human      | 3504       | 876       |
| Dog        | 656        | 164       |
| **Total**  | **5505**   | **1377**  |

### Distribution of Gene Family Samples by Species

| Gene Family                 | Class Label | Chimpanzee | Human | Dog  | **Total** |
|-----------------------------|-------------|------------|-------|------|-----------|
| G protein coupled receptors | 0           | 234        | 531   | 131  | **896**   |
| Tyrosine kinase             | 1           | 185        | 534   | 75   | **794**   |
| Tyrosine phosphatase        | 2           | 144        | 349   | 64   | **557**   |
| Synthetase                  | 3           | 228        | 672   | 95   | **995**   |
| Synthase                    | 4           | 261        | 711   | 135  | **1107**  |
| Ion channel                 | 5           | 109        | 240   | 60   | **409**   |
| Transcription factor        | 6           | 521        | 1343  | 260  | **2124**  |


### Comparison of Compression Algorithms in DNA Sequence Classification

| Algorithm | Computation Time (seconds) | Accuracy | Recall | Precision | F1 Score |
|-----------|----------------------------|----------|--------|-----------|----------|
| Gzip      | 1735.81                    | 0.962    | 0.962  | 0.963     | 0.962    |
| Snappy    | 1726.49                    | 0.932    | 0.932  | 0.933     | 0.932    |
| Brotli    | 12551.60                   | 0.966    | 0.966  | 0.967     | 0.966    |
| LZ4       | 1618.27                    | 0.942    | 0.942  | 0.943     | 0.942    |
| Zstandard | 1560.72                    | 0.930    | 0.930  | 0.935     | 0.931    |
| BZ2       | 2657.35                    | 0.924    | 0.924  | 0.924     | 0.924    |
| LZMA      | 9486.67                    | 0.958    | 0.958  | 0.958     | 0.958    |

### Performance Metrics of Compression Algorithms on DNA Sequence Classification for Different Species

| Algorithm | Chimpanzee Accuracy | Chimpanzee Precision | Chimpanzee Recall | Chimpanzee F1 Score | Human Accuracy | Human Precision | Human Recall | Human F1 Score | Dog Accuracy | Dog Precision | Dog Recall | Dog F1 Score |
|-----------|---------------------|----------------------|-------------------|---------------------|----------------|-----------------|--------------|----------------|--------------|---------------|------------|--------------|
| Gzip      | 0.997               | 0.997                | 0.997             | 0.997               | 0.944          | 0.945           | 0.944        | 0.944          | 0.988        | 0.989         | 0.988      | 0.988        |
| Snappy    | 0.994               | 0.994                | 0.994             | 0.994               | 0.943          | 0.944           | 0.943        | 0.943          | 0.744        | 0.748         | 0.744      | 0.745        |
| Brotli    | 1.000               | 1.000                | 1.000             | 1.000               | 0.947          | 0.950           | 0.947        | 0.948          | 0.994        | 0.994         | 0.994      | 0.994        |
| LZ4       | 0.997               | 0.997                | 0.997             | 0.997               | 0.944          | 0.946           | 0.944        | 0.944          | 0.817        | 0.829         | 0.817      | 0.819        |
| Zstandard | 0.994               | 0.994                | 0.994             | 0.994               | 0.900          | 0.909           | 0.900        | 0.901          | 0.963        | 0.967         | 0.963      | 0.963        |
| BZ2       | 0.985               | 0.985                | 0.985             | 0.985               | 0.893          | 0.894           | 0.893        | 0.893          | 0.963        | 0.966         | 0.963      | 0.964        |
| LZMA      | 1.000               | 1.000                | 1.000             | 1.000               | 0.936          | 0.937           | 0.936        | 0.936          | 0.988        | 0.989         | 0.988      | 0.988        |


## Usage
Here's a quick example:
```python
from exampleproject import Example
example = Example()
example.run()
```
## Link to the URL
[Demystify DNA Sequencing with Machine Learning](https://www.kaggle.com/code/nageshsingh/demystify-dna-sequencing-with-machine-learning/notebook)

## Documentation
For detailed documentation, visit [ExampleProject Docs](https://exampleproject.com/docs).

## Requirements
- Python 3.6+
- Other dependencies listed in `requirements.txt`

## Installation
The libraries can be installed manually. But if you want you can try with `requirements.txt` file shared in this repository.
```bash
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for more information.

## Code of Conduct
Please read our [Code of Conduct](CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

## License
ExampleProject is licensed under the [MIT License](LICENSE).

## Support
If you need help or have a question, raise an issue or contact me at sukruozan@gmail.com.

## Contributors
- [Sukru Ozan](https://sukruozan.com)


## Tables for Comparison or Data
| Feature       | Description                |
|---------------|----------------------------|
| Feature 1     | Detailed description here. |
| Feature 2     | Detailed description here. |



## References
1. Article or paper title. [Link](http://example.com)
2. Another relevant article. [Link](http://example.com)
