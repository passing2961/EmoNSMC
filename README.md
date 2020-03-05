# EmoNSMC

Korean large emotion labeled dataset (EmoNSMC)


[here]: https://github.com/passing2961/KMRE

*Note: We improved this dataset more precisely, called the KMRE dataset. You can access the extension version of EmoNSMC in [here]. Thus, we recommend the KMRE dataset.* 

## Features

- The EmoNSMC dataset has seven types of emotions
  - Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Neutral
  
  
- Each file was stored in the pickle module

```python
import pickle as pc

with open('data/{file_name}', 'rb') as f:
    data = pc.load(f)
```

## Citation

If you want to use our resource, please cite our paper.

```
"EmoNSMC: Distant Supervision 을 이용한 한국어 감정 태깅 데이터셋 구축", 이영준, 최호진.
```
