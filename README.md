# Age-Synthesis

This is my project for age synthesis. The purpose of the research is trying to design a system for aging image.

## Advantages

The advantage of the study is that we can generate the data by ourself in oder for GAN training since the state of art datasets such as CACD are susally imbalance.

## flowchart 
We have three steps for the experiments
- Train gender and age dataset.
- Using pretrained classifier to generate pair dataset.
- Train GAN model by pair dataset.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contribution
continuing

## Reference 
[stylegan2-distillation](https://github.com/EvgenyKashin/stylegan2-distillation)
