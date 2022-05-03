# CopyMTL: Copy Mechanism for Joint Extraction of Entities and Relations with Multi-Task Learning

## Environment

python3

GPU

pytorch 1.8.1

## Modify the Data path

This repo initially contain webnlg, you can run the code directly.
And for NYT dataset you first have to download the dataset and in copy the data to data/nyt/seq2seq_re/*.json.
And then change the dataset in config.json to NYT

## Run
### Train
`python main.py --gpu 0 --mode train --cell lstm --decoder_type one`
### Test
`python main.py --gpu 0 --mode test --cell lstm --decoder_type one`



