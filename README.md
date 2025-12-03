# Predicting Homologous Recombination Deficiency and Treatment Responses using a Computed Tomography-based Foundation Model: A Preclinical Study

### Overview
This is the repository of paper "Predicting Homologous Recombination Deficiency and Treatment Responses using a Computed Tomography-based Foundation Model: A Preclinical Study". Homologous recombination deficiency (HRD) can lead to genomic instability, increased cancer susceptibility, and enhanced sensitivity to DNA-targeting therapies. Although radiomics has been used for various medical applications, its application in animal studies remains largely unexplored, primarily due to the typically limited availability of preclinical data. In this study, we applied a state-of-the-art foundation model (FM) on preclinical computed tomography (CT) images in mice, aiming to: (i) distinguish HRD status within isogenic xenografts, and (ii) predict differential therapeutic responses of CP-506, a novel hypoxia-activated DNA-crosslinking agent. The dataset comprises micro-CT scans of 307 mice with balanced HRD status, collected both before and after CP-506 or control treatment. The FM demonstrated robust HRD classification performance, achieving an AUC of 0.88 on the test set, which significantly outperformed the handcrafted radiomics and supervised deep learning (sDL). The highest AUC (0.91) was achieved in the consensus subgroup (61.42%) between sDL and FM. Additionally, HRD-related features predicted DNA damage and growth delay following the treatment. Interpretability analysis indicated the important role of texture heterogeneity in HRD classification. Therefore, these results suggest that FM successfully overcomes the data scarcity in animal studies and enables HRD classification and treatment response prediction from preclinical CT imaging.



##
Code and data will be uploaded upon publication.

## Citation

@article{kuang5381282predicting,
  title={Predicting Homologous Recombination Deficiency and Treatment Responses Using a Computed Tomography-Based Foundation Model: A Preclinical Study},
  author={Kuang, Sheng and Schuitmaker, Lesley and Wu, Min and Salahuddin, Zohaib and van der Wiel, Alexander and van de Laak, Jella and Lieuwes, Natasja and Biemans, Rianne and Jung, Jennifer and Yaromin, Ala and others},
  journal={Available at SSRN 5381282}
}
