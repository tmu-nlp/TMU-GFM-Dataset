# TMU-GFM-Dataset
A dataset for GEC metrics with manual evaluations of grammaticality, fluency, and meaning preservation for system outputs.  
More detail about the creation of the dataset can be found in [Yoshimura et al. (2020)](https://www.aclweb.org/anthology/2020.coling-main.573.pdf).

# File format
The are 9 columns in the tmu-gfm-dataset.

1. **source:** source sentence.
2. **output:** system output sentence.
3. **grammer:** Grammaticaliry annotations by 5 annotators.
4. **fluency:** Fluency annotations by 5 annotators.
5. **meaning:** Meaning Preservation annotations by 5 annotators.
6. **system:** Which system the output sentence is from.
7. **ave_g:** Average grammer score.
8. **ave_f:** Average fluency score.
9. **ave_m:** Average meaning score.
