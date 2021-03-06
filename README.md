# Visual-Pivot
[EMNLP 2020] Using Visual Feature Space as a Pivot Across Languages

### Abstract 
Our work aims to leverage visual feature space to pass information across languages. We show that models trained to generate textual captions in more than one language conditioned on an input image can leverage their jointly trained feature space during inference to pivot across languages. We particularly demonstrate improved quality on a caption generated from an input image, by leveraging a caption in a second language. More importantly, we demonstrate that even without conditioning on any visual input, the model demonstrates to have learned implicitly to perform to some extent machine translation from one language to another in their shared visual feature space. We show results in German-English, and Japanese-English language pairs that pave the way for using the visual world to learn a
common representation for language.

### Requirements
- Python 3
- Pytorch > 1.0

### Data
- [Multi30k-Task2](https://github.com/multi30k/dataset/tree/master/data/task2)  
- [STAIR](https://github.com/STAIR-Lab-CIT/STAIR-captions) 

### Training: image captioning task


### Inference: 
