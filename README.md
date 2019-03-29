# Generating Music Using Long Short-Term Memory

## Austin Guo, Edward Chu, Gopi Suresh, Carter Wu

Link to Google Drive directory (contains the sample raw outputs and post processed outputs): https://drive.google.com/drive/folders/1MD0SO4UD0_KdrTsLZaOp7jTEK6OKY2Xr?usp=sharing

## Abstract
Due to the success of Long Short-Term Memory (LSTM) architectures in generating thematic sequential time-series text output[​2]​, we investigate the effectiveness of various preprocessing techniques and LSTM architectures in generating rock, folk, and electronic dance music (EDM). We propose generating music using a probabilistic multilabel model of note representation and a CNN-LSTM architecture, Dropout, and Recurrent Dropout.

## Data
Data for each dataset (EDM, Rock, Folk) were collected from various free sources online and aggregated together. Data augmentation was performed for the EDM dataset initially, but performance was not improved and output MIDI quality was decreased, so training using this dataset was discarded.