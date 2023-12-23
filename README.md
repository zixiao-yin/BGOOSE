![bgoose_withtext](https://github.com/zixiao-yin/BGOOSE/assets/55424621/8ffcad88-94af-4d89-a34a-aa9ad6195cbb)
# Hi there! :swan::swan::swan: 
- **BGOOSE** stands for **B**asal **G**anglia **O**scillation-based m**O**del for **S**leep-stage **E**stimation. [1] <br />
- _BGOOSE_ :swan: contains a sleep decoding model with an input of **local field potential signals** recorded from basal ganglia structures (i.e., subthalamic nucleus and globus pallidus internus), and an output of **three-class sleep stage labels** (i.e., NREM, REM and wakefulness). <br />
- _BGOOSE_ :swan: is trained on the **largest to date** :star: synchronized basal ganglia LFP - PSG dataset in a cohort of 141 patients with movement disorders including Parkinson’s disease, Essential Tremor, Dystonia, Essential Tremor, Huntington’s disease and Tourette’s syndrome. <br />
- Within-cohortly, the generalized _BGOOSE_ :swan: model achieved over **80% average accuracy** across patients and across disease conditions, even in the presence of recordings from different basal ganglia targets. :open_mouth: <br />
- In out-of-cohort validations, _BGOOSE_ :swan: still achieves around **75% sleep staging accuracy** :dart: on two external datasets (the Tsinghua dataset [2]) and the UCSF dataset [3]) recorded at different postoperative time points and using different DBS devices.<br />

# Installation
- Sorry that due to the limited time I currently have :disappointed:, it’s not possible for me to organize BGOOSE into a neat python package. Having that said, the main function of the BGOOSE can still be utilized by downloading the pretrained BGOOSE :swan: model (https://osf.io/mt72e/). A demo data can also be downloaded at the same website.

# Basic Usage
- Please check the jupyter notebook (BGOOSE - demo.ipynb) for a demo usage of BGOOSE. For any question or suggestion please find my contact information at [my GitHub profile](https://github.com/zixiao-yin). :smiley:

# Reference
- [1] Yin, Z. X. et al. Generalized sleep decoding with basal ganglia signals in multiple movement disorders. Not yet published (2024)
- [2] Chen, Y. et al. Automatic Sleep Stage Classification Based on Subthalamic Local Field Potentials. IEEE Trans Neural Syst Rehabil Eng 27, 118–128 (2019). <br />
- [3] Anjum, M. F. et al. Multi-night naturalistic cortico-basal recordings reveal mechanisms of NREM slow wave suppression and spontaneous awakenings in Parkinson’s disease. bioRxiv (2023)
