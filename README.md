# MIL Meets Intervention: A Data-Driven Causal Intervention Framework for Reducing Representation Bias in WSI Classification
# Download pre trained features
For downloading pre trained features, please refer to IBMIL: https://github.com/HHHedo/IBMIL
# Training
* for ABMIL, DSMIL and ILRA-MIL:
  
  `
    python train_tcga.py --model [abmil/dsmil/ilra]
  `
* for DTFD-MIL:

    `
    python train_tcga_DTFD.py
  `
  
An example with feature extractor of ImageNet-pretrained ResNet-18, MIL model of abmil, dataset of Camelyon16:

 `
     python train_tcga.py --model abmil
`

It is worth noting that the training model obtained in the last epoch will be automatically used for testing.
