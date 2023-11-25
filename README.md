# SpokenHPG: A Dataset for AI-Enhanced Near-Miss High-Pressure Gas Incident Reporting

This dataset is an extension of the HPGIncident dataset from [Inoue et al., 2023](https://github.com/Cinnamon/incident-ai-dataset). It contains data for three tasks, including Automatic Speech Recognition (ASR), Named Entity Recognition (NER), and Cause-Effect Extraction (CE). The dataset leverages a use case in the gas industry in which AI systems can assist onsite and offsite workers in making near-miss incident reports effectively. A demonstration can be found in [our prototype](https://bit.ly/incident-ai-demo), which is only operated from 9 AM to 5 PM due to cost efficiency.


## Data structure
```
data
├── ASR
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

As for ASR task, the audio and transcription are located in the [Huggingface Datasets](https://huggingface.co/datasets/cin-model/spoken-HPG-incident)


## License
Our dataset is released under the [Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) license](LICENSE).

## Reference
If you use this dataset, please cite the following paper:
```

```