# Biosignals: 
## Electromyography (EMG) Deep Learning Pipelines
This repository contains deep learning pipelines for processing and training models on electromyography (EMG) data. It currently features two major datasets: the Ninapro Database 2 (DB2) and the High-Density sEMG 65-Hand Gestures Database.

## Repository Structure
The repository is organized as follows:

- **EMG Folder**: Contains two subfolders for separate deep learning pipelines:
  - **Ninapro DB2**: This subfolder includes Jupyter notebooks that implement deep learning pipelines for processing and training models using the Ninapro DB2 data. The pipelines train Multi-Layer Perceptron (MLP), Convolutional Neural Networks (CNN), and CNN combined with Long Short-Term Memory (LSTM) models.
  - **HD sEMG 65**: This subfolder contains Jupyter notebooks that implement deep learning pipelines for processing and training models using the HD sEMG 65 data. The pipelines train Convolutional Neural Networks (CNN) and Transformer-based models.

## Datasets

### Ninapro Database 2 (DB2)
- **Description**: The Ninapro DB2 dataset consists of EMG signals collected from 12 active double-differential wireless electrodes using the Delsys Trigno Wireless EMG system. The electrodes are placed around the forearm in strategic locations to capture muscle activity. The dataset contains data from 40 subjects with 6 repetitions of 17 movements with each repetition being 5 seconds separated by 3-second rest periods.
- **Data Source**: [Ninapro DB2 Data](https://ninapro.hevs.ch/instructions/DB2.html)
- **Reference Paper**: [Ninapro DB2 Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4421935/)

### High-Density sEMG 65-Hand Gestures
- **Description**: This dataset consists of EMG signals recorded from 20 able-bodied volunteers aged between 25 and 57 years, using a Quattrocento (OT Bioelettronica) biomedical amplifier system. The data is recorded using high-density sEMG electrodes with a total of 64 contacts arranged in an 8 × 8 matrix, covering a wide range of muscle activity across the forearm. The recording protocol consisted of 66 hand movements (65 unique movements and one repeated twice), with 5 repetitions separated by 5-second rest periods.
- **Data Source**: [HD sEMG 65 Data](https://springernature.figshare.com/collections/A_database_of_high-density_surface_electromyogram_signals_comprising_65_hand_gestures_performed_in_an_isometric_manner/5090861)
- **Reference Paper**: [HD sEMG 65-Hand Gestures Paper](https://www.nature.com/articles/s41597-021-00843-9)



