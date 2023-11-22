# SpokenHPG: A Dataset for AI-Enhanced Near-Miss High-Pressure Gas Incident Reporting

This dataset is an extension of HPGIncident dataset from [Inoue et al., 2023](https://github.com/Cinnamon/incident-ai-dataset).
It contains data for three tasks, including Automatic Speech Recognition (ASR), Named Entity Recognition (NER), and Cause-Effect Extraction (CE). 


## Data structure
```
data
├── ASR
│   ├── README.md
│   ├── test.tsv
│   └── train.tsv
├── CE
│   ├── test
│   │   ├── 1985-009.ann
│   │   ├── 1985-009.id
│   │   ├── 1985-009.txt
│   │   ├── ...
│   └── train
│       ├── ...
├── NER
│   ├── test
│   │   ├── 1985-009.ann
│   │   ├── 1985-009.id
│   │   ├── 1985-009.txt
│   │   ├── ...
│   └── train
│       ├── ...
```
As for NER and CE tasks, each incident report (sample) includes three files
- `*.txt` contains transcription by utterances
- `*.id` contains id for corresponding utterances
- `*.ann` contains annotation in [BRAT](https://brat.nlplab.org/) format.

As for ASR task, the folder `/data/ASR` contains only transciption due to large size of audio data.
Please contact administration in Cinnamon AI for accessing audio files.


## License
Our dataset is released under the Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) license.

## Reference
If you use this dataset, please cite the following paper:
```

```