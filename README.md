# f-AnoGAN_for_VUMC

## What is TEP (Tumor Educated Platelets)?
For the past few years, biomarker known as TEP (Tumor Educated Platelets) has been in the spotlight as a prospective biomarker for liquid biopsies.

In 2018, Best et al. revealed that platelet transcriptomes — transcriptomes are the sum total of the messenger RNA molecules expressed from the genes of an organism — can be used for cancer diagnosis. Not all platelet transcriptomes but certain types, namely the Tumor Educated Platelets, which show significant differences in expression levels between cancer patients and healthy could be used as biomarkers for cancer diagnosis.

In their research, Best et al. showed a 96% accuracy in distinguishing cancer from healthy patients with 4% false negative rates, and 8% false positive rates. In an independent study on NSCLC classification using TEP, the authors achieved 88% accuracy for late-stage cancer and 81% accuracy for locally advanced cancer.

## f-AnoGAN implementation
In this repository, the f-AnoGAN, a GAN(Generative Adversarial Network)-based anomaly detection model, will be implemented to classify anomalous (i.e., cancerous) samples. 
However, f-AnoGAN is fundamentally an image classification model but the VUMC dataset that we have is tabular in format. Therefore, in order to align the data format, IGTD (Image Generator for Tabular Data) was implemented prior to model training and testing in conjuction with other data preprocessing steps. 


