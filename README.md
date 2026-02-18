# Empirical_FM_DL_LLM
We empirically compare formal methods, deep learning, and LLMs on public benchmarks, analyze accuracy, efficiency, and scalability, and derive actionable insights for hybrid vulnerability detection frameworks.


Will add steps for Data Annotations.


### Taxonomy figure can be found with the name "Taxonomy_Final.png"

### The baseline results obtained for different deep learning baselines over different datasets are shared in the folder "DL_Baseline_Outputs"

## DATASETS

The detailed information about dataset is available at the following external link due to space constraints:

https://cciitpatna-my.sharepoint.com/:f:/g/personal/halder_iitp_ac_in/IgDmV7HZqkSdTLNL9VEt6UQpAdMEKjZVTEYUTgKpxcoK6S0?e=rP0Chz

The structure within all folders are consistent and organized into three subfolders:

1. **SolidityFiles_Data** – Contains the Solidity smart contract source files.
2. **FM_Tools_result** - Contains the experimental results of individual tools on the respective dataset.

3. **Labelling** – Contains two CSV files:

        i) labelled_....csv: Provides the final labels for each contract address, indicating the presence (1) or absence (0) of specific vulnerabilities.

        ii) revised_....csv: Contains tool-specific labelling results, showing which tools detected which vulnerabilities.


## Baselines Video

To evaluate learning-based vulnerability detection under realistic and reproducible conditions, we benchmark a carefully curated set of representative deep learning models proposed between 2019 and 2024. Guided by the taxonomy illustrated in "Taxonomy_Final.png", the following section presents the selected baselines along with a sample video demonstrating their execution.

1. **VULHUNTER** : To run this baseline and replicate results use the link : (https://drive.google.com/file/d/1415FFUASsI7mDIAUytIlLLHGH4KLthJP/view)
2. **AMEVuldetector** : To run this baseline and replicate results use the link : (https://youtu.be/ZxTVXA39YXA)
3. **CrossModality** : To run this baseline and replicate results use the link : (https://www.loom.com/share/0fab2244a13549db97776d3163637e36?sid=6cc011b3-704c-4002-8595-bb5e8ccbf535)
4. **CLEAR** : To run this baseline and replicate results use the link : (https://drive.google.com/drive/folders/16VnSajm6nmPIUQWqowAQ0-x04lEYSM9-?usp=sharing)
5. **MTL_EFEVD** : To run this baseline and replicate results use the link : (https://drive.google.com/file/d/1Dh5aTfbKU_w2HHQPVNGaW8RT8mFfySil/view)
6. **MEVD** : To run this baseline and replicate results use the link : (https://drive.google.com/file/d/1E3XiwwPGIGfTlMkQZw3GMxo8jTMU50dJ/view)


