# Leveraging Whisper ASR with LLM Fine-Tuning for End-to-End Multi-Lingual Speech Dialect Classification in Dravidian Languages

## Overview
This project addresses speech variations caused by regional dialects, specifically focusing on Dravidian languages such as Tamil, Malayalam, and Kannada. We have created a dialect-specific speech corpus for these languages (currently not open-sourced) and utilized the pre-trained Whisper ASR model. We applied advanced fine-tuning techniques, including Low-Rank Adaptation (LoRA) and Quantized-LoRA (QLoRA), for multi-class classification of dialects.

This repository provides information about sample audio files for each dialect within the aforementioned Dravidian languages. It includes metadata such as the number of dialects per language, the number of speech utterances, duration in hours and minutes, the number of unique speakers, and the average duration per utterance for each language. Detailed information about the data collection process is illustrated in the figure below. ![](https://raw.githubusercontent.com/Dialect-ICASSP/Dialects/main/DataCreation-Flow.png) 


## The detailed meta-data information for all three languages are given in the table below.

### Data Statistics for Tamil

| Languages | Dialects    | No. of Utterances | Duration (in hours) | Duration (in minutes) | Male Speakers | Female Speakers | Total Unique Speakers | Average Duration per Utterance |
|-----------|-------------|-------------------|----------------------|------------------------|---------------|-----------------|------------------------|----------------------------------|
| Tamil     | Chennai     | 1799              | 5.00                 | 300                    | 65            | 28              | 93                     | 10                               |
| Tamil     | Coimbatore  | 2188              | 6.08                 | 364.8                  | 15            | 6               | 21                     | 10                               |
| Tamil     | Madurai     | 2480              | 6.89                 | 413.4                  | 52            | 17              | 69                     | 10                               |
| Tamil     | Thoothukudi | 1840              | 5.11                 | 306.6                  | 68            | 34              | 102                    | 10                               |

