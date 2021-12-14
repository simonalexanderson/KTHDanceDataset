# KTHDanceDataset

This repository contains dance data recorded for the paper "Probabilistic autoregressive dance generation with multimodal attention https://dl.acm.org/doi/10.1145/3478513.3480570" published at SIGGRAPH Asia 2021. Please see the project page https://metagen.ai/transflower for code and links to additional dance data used in the paper.

The dataset consists of audio (numpy format) and motion capture data (bvh). The motion was recorded with 17 Optitrack Prime 41 cameras. The street dance parts contains three styles: Hiphop, Krumping and Popping, and includes fingers and hinged toes, performed by dancer Mario Perez Amigo to his own music. The casual dancing does has fixed hands and feet and was performed to various pop music tunes. All data was retargeted to a uniform skeleton. 

The naming of the clips follow the AIST Dance Database:

```
prefix_genre_situation_camera_dancer_music_choreography.bvh
```

Note that the important aspects are genre, dancer and music. The other tags are added to comply with the AIST naming convention ("Situation" is allways set to sFM (Advanced dance), "camera" to cAll, and "choreography" to a increasing serial number).

# TERMS OF USE

Please read carefully the following terms and conditions and any accompanying documentation before you download and/or use the KTH Dance Dataset. By downloading and/or using the dataset, you acknowledge that you have read these terms and conditions, understand them, and agree to be bound by them. You also acknowledge that all MUSIC AUDIO has their own Copyright Holders and is not subjected to this license. After downloading the data, you shall at all times be responsible for ensuring the data is stored securely.
**Non-commercial use**
The KTH Dance Dataset is free to use for research purposes by academic institutes, companies, and individuals. Use for commercial purposes is not permitted without prior written consent. This includes, without limitation, incorporation in a commercial product, use in a commercial service, or training machine learning algorithms for commercial purposes. If you are interested in using KTH Dance Dataset for commercial purposes or non-research purposes, please contact simonal@kth.se in advance.

**No redistribution**
Unauthorized redistribution of any content of the database is prohibited.

**Attribution**
Please clearly indicate the name of the dataset, "KTH Dance Dataset", when using the data. When mentioning this database in an academic paper, please cite the following paper as a reference:

```
@article{10.1145/3478513.3480570,
author = {Valle-P\'{e}rez, Guillermo and Henter, Gustav Eje and Beskow, Jonas and Holzapfel, Andre and Oudeyer, Pierre-Yves and Alexanderson, Simon},
title = {Transflower: Probabilistic Autoregressive Dance Generation with Multimodal Attention},
year = {2021},
issue_date = {December 2021},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {40},
number = {6},
issn = {0730-0301},
url = {https://doi.org/10.1145/3478513.3480570},
doi = {10.1145/3478513.3480570},
journal = {ACM Trans. Graph.},
month = {dec},
articleno = {195},
numpages = {14},
keywords = {normalising flows, machine learning, glow, generative models, dance, transformers}
}
```
The street dances were performed by Mario Perez Amigo to music by Mario Perez Amigo. Please attribute when original motion or music is used in videos.

**Disclaimers**
Any use of the KTH Dance Dataset or any supplementary code is at your own risk. We do not guarantee the quality of the database, which may contain errors such as noisy motion data or audio/motion synchronization issues. If you find any errors, please contact simonal@kth.se to help in improving the database.
